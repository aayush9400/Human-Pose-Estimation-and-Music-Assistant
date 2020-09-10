# Human-Pose-Estimation-and-Music-Assistant
These tasks were done for Meraaki Learning.

# Task 1
There are two parts to the program.
## Libraries Required
1. OpenCV
2. Numpy
3. skimage
4. matplotlib
### To Run
After importing the required modules run all cells in the Meraaki Task 1 (Pose).ipynb
## Working: Part 1 & Part 2
### Part 1 (Teacher Side)
The first one is catered for the Teacher side which would be used to identify and record the sequence. 
- The program saves a frame every 2 sec which gives the teacher time to move onto the next step and displays a message as soon as a frame is captured. 
- Also, it simultaneously saves the frames as a video that can be distributed to the students along with the frames which highlight the pose which can be used to perfect the dance step.
### Part 2 (Student Side)
This would be used for comparing the dance steps with the teachers'. 
- This part can be used by the student to compare their pose with the teachers, which gives out the Similarity Percentage. 
- The frames of the student can be created using the functions in Part 1

# Task 2
## Libraries Required
1. mido
2. wave
3. librosa
4. pydub
5. pretty_midi
### To Run
After importing the required modules run all cells in the Meraaki Task 2 (Audio).ipynb
## Working:
- The program reads both the midi file and the user's recorded wav file and converts both of them into notes that were played, which can be further compared with each other to find out how correctly the user is playing and notify them note by note whether what they played was correct or not.
- Also, it plots the notes onto a graph which is similar to sheet music
