# GPT-Based Audio Assistant

![GitHub last commit](https://img.shields.io/github/last-commit/adarschwarzbach/chatterGPT)
![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)
![Python Threading](https://img.shields.io/badge/Python-Threading-blue)
![Azure Cognitive Services](https://img.shields.io/badge/Azure-Cognitive%20Services-blue)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-blue)
![SoundDevice](https://img.shields.io/badge/SoundDevice-library-blue)
![PyDub](https://img.shields.io/badge/PyDub-library-blue)
![Scipy](https://img.shields.io/badge/Scipy-library-blue)


![Project Image](https://modellma2.files.wordpress.com/2015/09/screen-shot-2015-10-14-at-14-11-58.png)  <!-- Replace with your project image URL -->

## We all wish that Siri was a bit better... 
The first step to fixing that problem is creating an assistant that is a lot "smarter" and more conversational then Siri. Enter OpenAI's ChatGPT. Using a GPT endpoint, Azure's Cognitive Services and a couple of Python libraries I wrote a script to record the user speaking, transcribe the recording, send a request to gpt-3.5 and then play the recording back. I also used threads to make things run a bit faster. 

