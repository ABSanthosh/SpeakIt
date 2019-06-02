## SpeakIt
A speaker to read out the text either for Youtube or for anything!

# Objective
1.The main objective of the application is to utilise new libraries and produce a voice reading the given data.                                
2.User can also save the voice to the local device.                                                               
3.This allows the user to set desired speed to read the given data.                                                                 
4.This Beta version also support a lister which can type text which user read to the computer.(still under development)                                                                                      

# Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install pyttsx3
pip3 install --upgrade speechrecognition
pip install winspeech
pip install comtypes
```
# Visuals

![speakit](https://user-images.githubusercontent.com/24393343/58765835-a61bbb00-8594-11e9-9061-cbabec6af9ce.jpg)
 
# Run Locally
1. Method-1
* Clone the repo.
* Open the file and extract it.
* Edit the .py File in any editor and run it.


# Requirnments

```bash
import datetime
import os
import pyttsx3
import socket
import speech_recognition as srr
import sys
import threading
import time
import win32com.client as wincl
import winspeech

from comtypes.client import CreateObject
from tkinter import *
from tkinter import PhotoImage
from tkinter import filedialog
from tkinter import messagebox

```
    
