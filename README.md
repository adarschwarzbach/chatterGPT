# GPT & Azure Audio Assistant
![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)
![Azure Cognitive Services](https://img.shields.io/badge/Azure-Cognitive%20Services-blue)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-blue)
![Python Threading](https://img.shields.io/badge/Python-Threading-blue)
![SoundDevice](https://img.shields.io/badge/SoundDevice-library-blue)
![PyDub](https://img.shields.io/badge/PyDub-library-blue)
![Scipy](https://img.shields.io/badge/Scipy-library-blue)

## We all wish that Siri was better... 

The first step to fixing that problem is creating an assistant that is a lot "smarter" and more conversational then Siri. 

Leveraging a **GPT endpoint**, along with **Azure's Cognitive Services** and a couple of **Python libraries**, I was able to make a first stab at this.

### Here's what I did:
- Wrote a script to record the user speaking.
- Transcribed the recording with  **Azure**.
- Sent a request to **gpt-3.5** with the transcription
- Created a spoken recording of the gpt response, once again using Azure's Cognitive Services.
- Incorporated **multithreading** to speed things up. 

![Project Image](https://modellma2.files.wordpress.com/2015/09/screen-shot-2015-10-14-at-14-11-58.png) 