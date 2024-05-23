# Face Recognition Using Python for Windows

## Introduction
This repository contains a project for Face Detection and Face Recognition using Python 3.11. The project is designed to recognize and identify individuals based on their facial features.

## Getting Started
To start using this project, follow these steps:

1. Download the project files as a zip.
2. Uninstall any existing version of Python and install Python 3.11.
3. Download the `dlib` Python package from [here](https://github.com/eddiehe99/dlib-whl/blob/main/dlib-19.24.1-cp311-cp311-win_amd64.whl).
4. Extract the downloaded files and open a terminal in the extracted folder.
5. Run the following command to install the required packages:

```bash
pip install -r requirements.txt
```

6. Create a subfolder named `known_persons` in the same level as that of `capture_faces.py`.
7. Add photos of known individuals into the `known_persons` directory. Make sure each photo is of a different individual.
8. Open the `crime_history_samples.csv` file in your desired CSV editor.
9. Add sample data to the `crime_history_samples.csv` file. The names mentioned in the first column of the CSV should match with the names of the individuals in the `known_persons` directory.
10. Run the `capture_faces.py` script by executing the command `python capture_faces.py` in the terminal.

### Caution
- Only use `.jpg` or `.png` pictures.