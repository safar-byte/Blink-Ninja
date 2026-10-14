<div align="center">

# 👁️ Blink Ninja

**How long can you go without blinking? A webcam staring contest that runs entirely in your browser.**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MediaPipe](https://img.shields.io/badge/MediaPipe_FaceMesh-0097A7?style=flat-square&logo=google&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

</div>

## How it works

Blink Ninja tracks 468 facial landmarks with **MediaPipe FaceMesh** and computes the **Eye Aspect Ratio (EAR)** for each eye on every frame — the ratio of the eye's vertical openings to its width. When the EAR drops below a threshold, your eye is closed: the timer stops and your eye-open time is shown.

- Everything runs locally in the browser; no video leaves your machine.
- Single file, no build step, no server.

## Play

1. Open `index.html` in a modern browser (Chrome recommended).
2. Allow camera access.
3. Click **Start**, look at the camera and keep your eyes open as long as you can.

## Tuning

If blinks are missed or triggered too easily, adjust `EAR_THRESHOLD` (default `0.26`) in `index.html` — higher values detect a closed eye sooner.

## Troubleshooting

Camera not working? Check the browser's site permissions, and on Windows make sure *Settings → Privacy → Camera* allows desktop apps / your browser.

## Author

**Muhammed Safar** — [@safar-byte](https://github.com/safar-byte)
