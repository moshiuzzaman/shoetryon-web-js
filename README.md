# shoetryon-web-js

- Go to https://developer.deepar.ai, sign up, create the project and the Web app, copy the license key and paste it to `index.html` (instead of `your_license_key_goes_here` string)
- Download the SDK from https://developer.deepar.ai/downloads and copy the following files to the `lib` folder:
  - `deepar.js`
  - `deepar.wasm`
  - `foot-detector-android.bin`
  - `foot-detector-ios.bin`
  - `foot-model.obj`
  - `foot-tracker-android.bin`
  - `foot-tracker-ios.bin`
  - `libxzimgPoseEstimation.wasm`
- Open the terminal in the project root
- Run `python server.py`
- Open http://localhost:8888 in your browser
