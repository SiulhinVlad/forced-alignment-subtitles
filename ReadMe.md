# Forced Alignment for Subtitle Generation  

The purpose of this tutorial is to demonstrate how subtitles can be automatically generated using **forced alignment** between a plain transcript and its corresponding audio file. This method aligns a pre-written transcript to the audio using phonetic information and word timing.

This guide introduces the [BAS Web Services](https://clarin.phonetik.uni-muenchen.de/BASWebServices/) and shows how to process the output from BAS Web Service (`.TextGrid` file) using Python to create subtitles (`.srt` file). All code is provided along with step-by-step explanations, making it accessible even to users with no prior programming experience. However, careful attention to the instructions is advised.

---

### Language Support

The alignment process is based on phonetic transcription (G2P → MAUS), and many major European languages are supported. For unsupported languages like Ukrainian, a language-independent model (`X-SAMPA`) is available, and a custom phoneme mapping file (`Ukrainian.lmao`) is provided together with other files.

---

### Credits

The audio files used in this tutorial were kindly provided by Machteld Venken.  
All necessary files can be found inside the `content` folder of this tutorial.

---

## How to Use

The Jupyter notebook in this tutorial is designed to run in **Google Colab**, it frees users from the need in local Python environment.  
To open the notebook in Colab, [click here](https://colab.research.google.com/drive/1DoSlNzXMA7YobjJ_vZp1-Mtvk0dKOqu5?usp=sharing).

Alternatively, you may run the notebook locally on your own machine using Jupyter. For this, make sure to install all required dependencies and configure your Python environment accordingly.

To understand how it works you may download files from **content** folder and practice on them.

---

## Software Requirements

This tutorial was developed using **Python 3.9.0** and requires the following libraries:

- `python-docx`

To install the required libraries manually:

```bash
pip install python-docx
```
---

## Questions

If you have any questions, feedback, or run into issues while following this tutorial, feel free to contact me:

[vladyslav.siulhin@uni.lu](mailto:vladyslav.siulhin@uni.lu)
