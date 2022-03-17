# SCREEN RECORDER

### AIM

To build a screen recorder using Python pyautogui.

### PURPOSE

Screen Recorder is a project that is used to record your screen and saves it as a video file.

### DESCRIPTION

- This code enables us to record screen easily.
- Recorded file will be saved as "Recording.avi"
- Libraries imported :
    - `pyautogui`
    - `CV2`
    - `numpy`

### WORKFLOW

- Imported required libraries i.e.,`pyautogui`,`CV2`,`numpy`.

- Resolution is set to 1920x1080.

- Framerate is set to 60.0 mps.

- Created a video object and an empty window, resized this window and named it as LIVE.

- PyautoGUI is used to take screenshots.

- Numpy will convert those screenshots into an array.

###  COMPILAION STEPS

- Download the file screen_recorder.py

- Run the file screen_recorder.py, let's start recording our screen.

- Install pyautogui, CV2, numpy libraries.

- After clicking run, it takes continuous screenshots and makes it into an array, out.write will convert this as a video.

- The screen will continue to record until we press `q`.

- Finally, recorded file will be saved as "Recording.avi".

### OUTPUT

![Screen Recorder]()

### AUTHOR

Prathima Kadari
