## This basic code structure covers the essential steps:
1. Listening: The assistant listens to the user using the microphone and Google's speech recognition service.
2. Processing: It processes the recognized text to trigger specific actions based on the command received.
3. Speaking: The assistant responds by converting text into speech using the text-to-speech engine.

## After dividing the code into three parts(Listen.py, process.py và speak.py), merge the code back into a file named VirtualAssistant.py and run it..

## Installation
### For windows users
(run those in command prompt/cmt/terminal)
For the robot to listen to our voice/speech
`pip install speechRecognition`

To speak out, or text to speech
`pip install pyttsx3`

### For linux users
Learn all the above commands on terminal. Make sure to use `pip3`, because in linux `pip` refers for `python2` and `pip3` refers to `python3`.
Install these too - 
`pip3 install pyAudio`

In case any error pops up install this -
`pip3 install portAudio`
