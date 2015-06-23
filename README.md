# linux-logos
This is a small collection of tools used to quickly replace/rebrand a linux distribution.

# Details
Rebrand a linux distribution's logo package with a custom logo:
*1. Download a centos-logos, redhat-logos, or fedora-logos package(NOTE: scan logos only used the other logos packages for reading, it does not copy/use any copyright names or images from them)
*2. Extract the contents of package
*3. Extract the "logos directory" from the logos tarball
*4. Provide a "new logo image"
5. Point scan-logos script at "new logo image" and "logos directory"
6. A new directory structure will be created with the specified names
7. After the directories are created, they are filled with the correct size, format, and image file
8. When the script finishes it's now safe to use the resulting directory structure for release
