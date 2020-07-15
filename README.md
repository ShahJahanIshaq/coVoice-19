# covidVoice
covidVoice is a simple voice assistant tracker of COVID-19 deaths and cases of each country that uses speech recognition and regex search patterns, along with basic web scraping techniques. Also, it updates the data with a single command.
To set up:
# Installation of libraries
You'll need Python 3 installed with pip. Run:
`
pip install pyttsx3
`
`
pip install pywin32
`
`
pip install speechRecognition
`
`
pip install requests
`
To install PyAudio, visit the following link and download the version of PyAudio that is appropriate for your system:
https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio <br>
Then navigate to the folder where the file is downloaded, via the Command Prompt and run:
`
pip install {name of the file downloaded}
`
# Commands
- **"update"**: Updates the data. This might take a few moments. <br>
- Any question related to deaths **or** cases with the name of any country **OR** 'total' deaths **or** cases : Returns the required number as speech. <br>
- **"stop"**: Stops the execution of the program. <br>
# Examples
"How many cases are there in China?"<br>
"How many total deaths worldwide?"<br>
"Hoe many deaths are there in USA?"

