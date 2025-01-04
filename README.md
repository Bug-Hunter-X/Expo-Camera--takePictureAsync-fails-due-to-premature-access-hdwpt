# Expo Camera: Premature Access to takePictureAsync

This repository demonstrates a common error when using the Expo Camera API: attempting to use `takePictureAsync` before the camera has fully initialized.  The bug.js file showcases the problematic code, resulting in an error. The bugSolution.js file presents the corrected version.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app (requires Expo CLI).
4. Observe the error message in the bug.js version.
5. Compare the corrected behavior in bugSolution.js.