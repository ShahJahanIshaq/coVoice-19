# covid_voice
covid_voice is a simple voice assistant tracker of COVID-19 deaths and cases of each country that uses speech recognition and regex search patterns, along with basic web scraping techniques. Also, it updates with a single command.
To set up:
# Installation of libraries
You'll need Python 3 installed with pip. Run:
```
pip install pyttsx3
```
```
pip install pywin32
```
```
pip install speechRecognition
```
```
pip install requests
```
To install PyAudio, visit the following link and download the version of PyAudio that is appropriate for your system:
https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio
Then run:
```
pip install pyaudio
```
# Commands
**"update"**: Updates the data. This might take a few moments.
Any question related to deaths **or** cases with the name of any country **OR** 'total' deaths **or** cases : Returns the required number as speech.
**"stop"**: Stops the execution of the program.
