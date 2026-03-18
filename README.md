# Hey there, I'm Gourav Singh Rajput 👋

I'm a **Electronics & Communication Engineering** student from **Indore, India**, currently in my first/second year. I spend most of my time at the intersection of computer vision, AI, and hardware — writing code that interacts with the real world through cameras, sensors, and signals.

I'm not just learning from tutorials. I build things — real, working projects that combine multiple technologies together. My current obsession is designing **AI-powered smart glasses** with retinal projection and an LLM brain, from scratch.

---

## 🧠 What I actually know

### Computer Vision
This is my strongest area. I work with **OpenCV** and **MediaPipe** regularly — not just calling functions, but understanding what's happening underneath. I know how to:
- Set up and manage a real-time video capture pipeline (frame capture, flipping, resizing, color space conversion)
- Work with **MediaPipe Face Mesh** — 468 facial landmarks, `refine_landmarks`, multi-face detection, and extracting specific landmark coordinates by index
- Work with **MediaPipe Hands** — up to 4 hands simultaneously, 21 landmarks per hand, detecting individual finger states using landmark position comparisons
- Implement the **Eye Aspect Ratio (EAR)** algorithm from scratch using `numpy.linalg.norm` to calculate distances between eye landmarks and detect blinks vs drowsiness
- Draw on a live canvas using finger tracking — line drawing, erase gestures, hover indicators
- Use **bitwise operations** (`cv2.bitwise_and`, `cv2.bitwise_or`) to blend a drawing canvas over a live webcam frame
- Use trigonometry (`math.cos`, `math.sin`, `math.radians`) to render dynamic visual effects that respond to hand geometry in real time
- Run **multiple MediaPipe models simultaneously** in a single frame loop (face mesh + hand tracking together)

### Python
Python is my primary language. Beyond the basics, I'm comfortable with:
- Writing clean, modular code with functions and logical structure
- Using **NumPy** for array math and vector distance calculations
- Using **Pygame** for audio playback and event handling inside CV applications
- Managing multi-window OpenCV applications with secondary popups and overlays
- Working with video files as input (`cv2.VideoCapture` on file paths, frame seeking with `CAP_PROP_POS_FRAMES`)
- Understanding frame-level timing, `cv2.waitKey`, and building smooth real-time loops

### AI & LLM Integration
I understand how modern AI APIs work and how to use them in applications:
- Familiar with the **Anthropic Claude API** and **OpenAI API** — making requests, handling responses, building conversational loops
- Understanding of **prompt engineering** — how to write system prompts, structure context, and get consistent outputs
- Aware of how to combine **speech-to-text (Whisper)**, **LLM APIs**, and **text-to-speech** into a full voice assistant pipeline
- Currently studying how to run lightweight models on edge devices (Raspberry Pi)

### Electronics & Hardware (ECE Background)
Being an ECE student gives me an edge most software-only developers don't have:
- Basics of **circuit design**, signal processing, and embedded systems
- Working knowledge of **Arduino** — GPIO, sensors, serial communication
- Understanding of **I2S protocol** for digital audio (microphones and amplifiers)
- Learning **Raspberry Pi** for running Python-based AI projects on embedded hardware
- Interest in **MEMS technology** — micro-electromechanical mirrors used in laser scanning displays and AR optics

### Creative & Content Skills
- **Video editing** — short-form content, Reels, YouTube videos
- **Thumbnail design** — eye-catching graphics for YouTube creators
- Comfortable with screen recording, demo creation, and presenting technical work visually

---

## 🔭 What I'm working towards

I'm currently designing **AI smart glasses** — a wearable device with:
- A wake-word activated LLM assistant (Claude / GPT API)
- MEMS laser retinal projection for a heads-up display
- On-device computer vision via a mini camera
- Voice I/O with a MEMS microphone and micro speaker
- Raspberry Pi Zero 2W as the brain

This project is what's pushing me to learn hardware, embedded systems, optics, and AI all at once.

---

## 📚 Currently learning

- Raspberry Pi Zero 2W — Python on embedded Linux
- Whisper (OpenAI) for on-device / API speech recognition
- MEMS mirror drive circuits and laser modulation
- LiPo battery management for wearable projects
- Building full voice assistant pipelines end to end

---

## 📫 Let's connect

## LinkedIn : https://www.linkedin.com/in/gourav-singh-rajput-a54511324/
## Email : gsrajput24sept@gmail.com
---

*"ECE student by degree, computer vision developer by choice, hardware hacker by obsession."*
