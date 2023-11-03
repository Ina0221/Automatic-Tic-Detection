# Automatic-Tic-Detection
This Python-based tool steps forward to automatic detection of hyperkinetic behavior (tics) in a Tourette syndrome rat model.
After evaluating the coordinates tracked by SLEAP (Pereira et al., 2022), this tool analyzes the body parts' velocities.
Input files are manually evaluated csv files, a hp5 file generated by SLEAP, and optionally a video file for rough evaluation of motion matching to automatic/manual scoring.
The Victor-Purpura distance can be determined to compare manually assessed tics (ground truth) with automatically scored tics. The closer to 0, the more similar the scorings are. 


