======== Module project notes ===========

Place your GoogleService-Info.plist in this folder and rebuild the project in order to link this module to your project.

===================

Files in this folder are copied directly into the compiled product directory
when the iOS app is compiled:

    <project-dir>/build/iphone/build/Products/<Debug-iphonesimulator|Release-iphoneos>/<app name>.app/

Place your module's iOS bundles and localization files in this folder.

Files in this directory are copied directly on top of whatever files are already
in the build directory, so please be careful that your files don't clobber
essential project files or files from other modules.
