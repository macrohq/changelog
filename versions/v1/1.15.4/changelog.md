# v1.15.4

### 🪲Bug Fixes
 - On occasion for meetings with more than 6 people, the extra videos were not rendering in the Macro UI. This has been remedied!
 - The app share functionality could cause some meetings to crash. We've improved the reliability of screenshare and now allow you to share different screens as well.
 - When a meeting ends, the app attempts to do some cleanup which did not work for some users. Now, the app cleans up after itself for everyone!
 - The post-meeting emails were not sending depending on how the user exits the Macro app. The app now waits to make sure the email was sent before quitting.
 - End-to-end encryption has been rolled out and does not yet support Macro. We now will launch the normal Zoom client if you join an E2EE meeting.
