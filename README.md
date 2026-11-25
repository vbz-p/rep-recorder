# Rep Recorder

Camera-based rep counter that runs in the browser. Record one rep of any movement, save it, and the app counts how many times you repeat it.

- Pose detection: MediaPipe Pose Landmarker (runs on-device)
- Features: joint angles + wrist height, weighted by which joints move most
- Matching: dynamic time warping against the saved rep

Flow: 1) Record — stand in a T-pose, countdown starts when your full body is visible, do 2–3 reps, hold still. 2) Review — 3D playback, trim to exactly one rep (auto-find or drag handles). 3) Count.

Open over HTTPS on a phone (GitHub Pages) and allow camera access.
