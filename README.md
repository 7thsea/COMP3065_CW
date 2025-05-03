# Person Tracking from Videos
This project implements a person tracking application from video files, with a graphical user interface for interaction.

## Project Overview

The project performs automatic person tracking on selected video demos. Users can interact with the system via a graphical interface to select and process different test videos.

## Getting Started

### How to Run

Execute the `Ui_main.py` file to launch the GUI.


## Important Notes
After each test, the program generates an output video named output.mp4 in the temp_output directory.

Before selecting a new demo (e.g., demo2), make sure to rename the previously generated output.mp4 to avoid it being overwritten.

### Recommended testing workflow:

Select demo1 and let the processing complete.

Navigate to the temp_output folder and rename output.mp4 to something like demo1_output.mp4.

Run the program again and select demo2.

Repeat for other demos as needed.
