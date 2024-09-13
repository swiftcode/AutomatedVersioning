# Automated Version Numbers

A script that automatically updates the version number when a build is performed.  It sets `$(CURRENT_PROJECT_VERSION)` and `$(MARKETING_VERSION)`.

The two files (Config.xcconfig and version.sh) should be dropped in \$SRCROOT/\$PROJECT_NAME.  

The build might not work if ENABLE_USER_SCRIPT_SANDBOXING is set to YES in `Build Setting` -> `Build Options`  Set this value to NO.

In Build Phases -> Run Script, drop the contents of the script (both lines) in the text box for Shell.

Note: Script is from an article at https://medium.com/@mateuszsiatrak/automating-build-number-increments-in-xcode-with-custom-format-a-practical-guide-bcc90a19f716

