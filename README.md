# SVGKit

SVGKit without non-system dependencies.


## System Dependency

libxml


## Trouble Shooting

If you see:

``
+[NSCharacterSet SVGWhitespaceCharacterSet]: unrecognized selector sent to class
``

Then edit you project's Build Settings, add

``
-force_load $(PROJECT_DIR)/...../libSVGKit.a
``

to `Other Linker Flags`


