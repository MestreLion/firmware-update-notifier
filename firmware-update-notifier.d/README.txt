Put your *.conf watch files here. Example:

# My Desktop Motherboard YYZ-2112
# Comments like the above are (mostly) ignored, and can be used as a device description

# Use the line below (with the comment!) to specify the current firmware version
# VERSION: 1.2.3 Build 20240102

# Only the first VERSION line found is used, allowing to keep a version history
# VERSION: 1.1 (factory firmware)
# VERSION: 1.0 (first release on the website)

# Non-commented lines must follow Debian Watch format, see uscan(1) for syntax

version=4
https://www.example.com/us/support/download/yyz-2112/ \
	https://static.example.com/upload/firmware/YYZ2112_?(.*)\.zip
