# Rep Recorder

Camera-based rep counter that runs in the browser. Record one rep of any movement, save it, and the app counts how many times you repeat it.

- Pose detection: MediaPipe Pose Landmarker (runs on-device)
- Features: joint angles + wrist height, weighted by which joints move most
- Matching: dynamic time warping against the saved rep

Open `index.html` over HTTPS on a phone (e.g. GitHub Pages) and allow camera access.
