# SimpleAssist
SimpleAssist is a Very basic voice assistant built in python just for fun and learning purpose.<br/>
It is based on WolframAlpha and Wikipedia Api and also has Speech to Text Recognization.<br/>
This is made as a task for GSOC Internet Archive Organization.

## Getting Started
To run SimpleAssist follow the below steps

### You'll have to install following things
It require python 2.7<br/>
Install these packages<br/>
**Dependency**
```
PythonWx - sudo apt-get install python-wxgtk3.0
Espeak - sudo apt-get install espeak python-espeak
Wikipedia - sudo pip install git+https://github.com/lucasdnd/Wikipedia.git
WolframAlpha - sudo pip install wolframalpha
SpeechRecognition - sudo pip install SpeechRecognition
Pyaudio - sudo apt-get install portaudio19-dev python-all-dev python3-all-dev && sudo pip install pyaudio
Monotonic -sudo pip install monotonic
```

#### To Run the project type
```
python simpleassist.py
```
Now you can interact with it either with voice or by enteing the text into the GUI box hit enter to run your query
It will show you result within few seconds.

![This is how it works](https://github.com/savannahar68/SimpleAssist/blob/master/simpleassist.gif)

It can do following things,<br/>
Perform simple and complex maths (Gives result if syntax is correct check wolframalpha for syntaxes)<br/>
Simple Query (Who is Presons Name)<br/>
It can answer Math , science , physics, give you food nutrition details, tech world, life science etc<br/>
[The syntax should be valid check wolfromalpha for syntax]
