# Open-AI-Whisper-ASR-Web-UI-Demo-With-Gradio
A web demo of Open AI's Automatic Speech Recognition system WHISPER using Gradio.

This project is cloned from an already existing implementation by [@amrrs](https://github.com/amrrs)'s [this repo](https://github.com/amrrs/openai-whisper-webapp).

Run this colab with a GPU instance and it will give you a [Gradio](https://github.com/gradio-app/gradio) Web App which will be active for 24 hrs after you model stops running.

## Whisper

Whisper is an ASR (Automatic Speech Recognition) model built and trained by Open AI on at least 82 languages including 3 mainstream local Pakistani languages (Urdu, Punjabi, Sindhi). The WER (Word Error Rate) for Urdu is tiny bit lesser than Hindi. Sindhi and Punjabi have relatively poorer WER. The lesser the WER, the better.
It is a transcription model, means it returns text from an audio after detecting its language. So it can be used for multiple tasks like audio captioning etc.

I highly recommend you read the pdf provided in this repo, it's from Open AI's official github repo of `Whisper`, the docs and usage are relatively trivial and simple to understand. The link to official repository is also provided in description.
