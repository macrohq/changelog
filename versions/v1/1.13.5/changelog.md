# v1.13.5

### 🏫 Window Size Cache
 - When you resize the Macro window, switch to collab mode, and switch back to meeting mode, the window now retains the same size and location you had it in before. No need to resize again each and every time!

### 🚫 Error Handling
 - Macro is a reactive app and a lot of things can happen when Zoom users join and leave. We've added some additional error handling for some edge cases that should make the experience better for everyone!

### 🕷️ Bug Fixes
 - Firebase was attempting to initialize twice or more for some users. We restricted this to only happen once!
 - Updated the CSS for the Zoom login page after they changed their format again.
 - Fixed an issue with destroyed windows in Electron that prevented Macro from exiting properly.
