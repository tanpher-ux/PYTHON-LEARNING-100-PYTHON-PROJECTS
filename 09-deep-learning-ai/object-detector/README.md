# Object Detector

**Category:** [Deep Learning & AI](../README.md) &nbsp;·&nbsp; **Stack:** YOLO (ultralytics) / OpenCV &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

Detects and draws bounding boxes around objects in images or video.

## Flow Diagram

```
Image/video frame -> pretrained detection model -> bounding boxes + class labels -> draw overlay
```

## How to Build It

1. Install: `pip install ultralytics opencv-python`\n2. Load a pretrained YOLO model\n3. Run inference on an image: `model(image)`\n4. Draw returned bounding boxes and labels with OpenCV\n5. Extend to video by looping over frames from `cv2.VideoCapture`\n6. Optionally fine-tune on a custom dataset

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Deep Learning & AI](../README.md) · [All 100 Projects](../../README.md)
