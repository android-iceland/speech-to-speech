# speech-to-speech

[If you don't know how to install python](https://youtu.be/Ebh157e3FkQ)<br>

# Step 1<br>
```
pip install -r requirements.txt
```


#### If you can't install pyaudio on Windows. <br>
Choose the PYAUDIO version according to your PYTHON version.<br>
Assume you are using python 3.10 the download<br>  
PyAudio‑0.2.11‑cp310‑cp310‑win_amd64.whl (here 'cp310' mean for python 3.10)<br>
[Download Whl file](https://www.lfd.uci.edu/~gohlke/pythonlibs/)<br>
Example:
```
pip install PyAudio‑0.2.11‑cp310‑cp310‑win_amd64.whl
```
---
# Step 2<br>
## Run nix tts api to get natural text to speech <br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/android-iceland/speech-to-speech/blob/main/nix_tts_api.ipynb) <br>
Then copy the url from google colab.<br>
The url will look like this :<br> 
https://45654.gradio.app/

---
# Step 3<br>

open ```app.py``` and change the url="your_url from google colab"

---
# Step 4<br>
Open cmd and run 
```
python app.py
```

