# Automated Version Numbers

A script that automatically updates the version number when a build is performed.  It sets `$(CURRENT_PROJECT_VERSION)` and `$(MARKETING_VERSION)`.

The two files (Config.xcconfig and version.sh) should be dropped in \$SRCROOT/\$PROJECT_NAME.  

The build might not work if ENABLE_USER_SCRIPT_SANDBOXING is not set to NO in `Build Setting` -> `Build Options`


Note: Script is from an article at https://medium.com/@mateuszsiatrak/automating-build-number-increments-in-xcode-with-custom-format-a-practical-guide-bcc90a19f716

