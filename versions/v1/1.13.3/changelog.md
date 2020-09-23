# v1.13.3

### 🚪Zoom Sign-in
 - Zoom updated their sign-in flow so we needed to change a few things on our end. OAuth is much prettier now (no thanks to reCAPTCHA).

### 🦗Bug Squashing
 - Macro was occasionally crashing due to a Node streaming bug. We've made some changes with API calls that will prevent this from happening in the future.
 - Meetings with / characters in the name were returning 404s with Google Drive even when url encoded. A workaround was added to fix this.
