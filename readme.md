# Using Google’s Speech-to-Text API with Python
*Step-by-step instruction and python syntax for utilizing the Google Cloud Platform speech transcription service*

> ## **Please see my [blog post](https://gretteljuarez.medium.com/using-googles-speech-to-text-api-with-python-e436dc6cb944) for a detailed walkthrough.**

![](./images/jason-rosewell-ASKeuOZqhYU-unsplash.jpg)
Photo by <a href="https://unsplash.com/@jasonrosewell?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jason Rosewell</a> on <a href="https://unsplash.com/s/photos/microphone?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

This project details steps to implement the Google Speech-to-Text API using python and tips learned in the process. There are 3 methods of transcription with Google’s API. This notebook focuses on the ```asynchronous recognition``` type using the REST API. Requests are made to the API and a response is returned in the form of a JSON.

The high level steps walked through in the notebook are:
- Set up Google Cloud services
- Prepare/Transcribe file

## Set up Google Cloud services

1. Create Speech-to-Text service
2. Verify API setup
3. Create Google Cloud storage

## Prepare/Transcribe file

1. Meet file requirements
2. Upload file to storage bucket
3. Transcribe
4. Write transcript to file
5. Delete file from bucket
6. Put it all together

## Additionally, code is provided for:
- Using beta API for multiple speakers
- Using beta API for word timestamps


# File Organization:
- ```images``` - dir containing image on this readme
- ```outputs``` - dir containing sample outputs from notebook
- ```Speech-to-text.pdf``` - presentation delivered in [Metis bootcamp](https://www.thisismetis.com/)
- ```fold_in_the_cheese.mp4``` - sample file used in jupyter notebook for transcription
- ```speech_recognition.ipynb``` - notebook containing steps and syntax for working with google cloud speech-to-text API
