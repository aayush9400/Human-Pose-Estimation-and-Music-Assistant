
---

# Human-Pose-Estimation-and-Music-Assistant

This repository contains two tasks: human pose estimation for dance instruction and a music assistant for comparing user-played notes with MIDI files.

---

## Task 1: Human Pose Estimation

### Overview
This task is divided into two parts: 
1. **Teacher Side**: Record and save dance poses.
2. **Student Side**: Compare student poses with teacher poses to evaluate similarity.

### Libraries Required
To run this task, ensure you have the following libraries installed:
- `OpenCV`
- `NumPy`
- `skimage`
- `matplotlib`

### How to Run
1. Open the `Meraaki Task 1 (Pose).ipynb` file.
2. Import the required libraries.
3. Run all cells in the notebook.

### Working
#### Part 1: Teacher Side
- Captures and records the teacher's dance poses.
- **Key Features**:
  - Saves a frame every 2 seconds, allowing the teacher time to transition to the next pose.
  - Displays a notification when a frame is captured.
  - Saves captured frames as a video file, which can be shared with students.
  - Highlights key body poses in the frames to help students refine their movements.

#### Part 2: Student Side
- Compares student poses against the recorded teacher poses.
- **Key Features**:
  - Computes a similarity percentage between the student's pose and the teacher's pose.
  - Frames for the student’s side can be generated using the functions provided in Part 1.

---

## Task 2: Music Assistant

### Overview
This task compares a user’s audio recording with a reference MIDI file to evaluate performance accuracy.

### Libraries Required
To run this task, ensure you have the following libraries installed:
- `mido`
- `wave`
- `librosa`
- `pydub`
- `pretty_midi`

### How to Run
1. Open the `Meraaki Task 2 (Audio).ipynb` file.
2. Import the required libraries.
3. Run all cells in the notebook.

### Working
- **Audio Analysis**:
  - Reads the MIDI file and the user’s recorded `.wav` file.
  - Extracts and converts the notes from both files.
  - Compares the user’s performance with the MIDI reference and provides feedback on accuracy.
  
- **Visualization**:
  - Generates a graph plotting the user’s notes alongside the MIDI reference.
  - The graph resembles sheet music, making it easier to visually track errors and improvements.

---

### Notes
- Ensure that all required libraries are properly installed before running the notebooks.
- For any issues or enhancements, feel free to open an issue or submit a pull request.

--- 

