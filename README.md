
# Tutorials and code examples on using ollama. 

This is the github repo for the Sensemakers meetups on ollama.
You can find information, code examples and tutorials here. 

First, download & install ollama from [www.ollama.com](http://www.ollama.com). 

### The dream: building an avatar chatbot with ollama.
In three meetups we'll be working on building a personalised chatbot. The chatbot is able to answer questions based on your documents. You can also personalize the chatbot. 

### Schedule
We have planned 3 meetups each with a seperate topic:

1. 17 April: starting with ollama and python 
2. 15 May: Chat with your documents using Langchain
3. 19 June: Personalise your chatbot / use your own model 

They will be hosted at the OBA library at Oosterdokseiland from 19 - 21h. See [www.oba.nl](https://www.oba.nl) for location & info. We will meet at the OBA Junior Lab in the basement. 

On the first wednesday of the month there will be a 'Do it yourself together' meetup, where you can work on your code. There is some support, but it's mostly DIY. Dates are May 1st and June 5th, also at OBA 19h.

## Meetup 1: 17 april: ollama basics and python

### Notebooks 17 april
1. ollama.ipynb - Chat with an LLM, stream the response, use vision models and create a front end!
2. ollama_llava_challenge.ipynb - use LLaVA to describe images 

### Video's for meetup 1
[Sam Witteveen's Playlist on ollama](https://www.youtube.com/watch?v=Ox8hhpgrUi0&list=PL8motc6AQftnHhi2X8M3rqEFwERPVup4c&index=5) Sam Witteveen's Playlist on ollama. 6 video's from intro to hard.

[Gradio tutorial](https://www.youtube.com/watch?v=eE7CamOE-PA) This tutorial helps you create chat interface including audio and images using Gradio. 

### Other docs for 17 april:
- Ollama cheat sheet (see repo)
- Slides presentation (see repo)

## Meetup 2: 15 May: 

Topics:
1. Recap of first meetup
2. Downloading models from Huggingface
3. A deeper look at Vision Language Models
4. Retrieval Augmented Generation from scratch
5. Show and tell

### Notebooks 15 may
All notebooks from first meetup.

1. Use ollama.ipynb from first lesson but now with another model
2. ollama_llava_self_driving_car.ipynb. See how good Llava is in recognizing traffic situations. It does not make same mistakes as some self driving car. Progress!
3. RAG_basics_from_scratch.ipynb
4. Bonus: ollama_RAG_exercises.ipynb

### Video:
(Intro to huggingface)[https://www.youtube.com/watch?v=jBFFUwL0TyY]
(Intro to RAG with ollama)[https://www.youtube.com/watch?v=V1Mz8gMBDMo]

## Meetup 3: 19 june: personalize your chatbot + quantization

###

### Speech-2-text and Text-2-Speech (medium to hard)
Wouldn't it be cool to talk to your device and listen to the answer from ollama? You can do this with speech-to-text (STT) and text-to-speech (TTS). 

Here are some recommended libraries in python:
- STT: use OpenAi's Whisper. See [https://pypi.org/project/openai-whisper/](https://pypi.org/project/openai-whisper/ ) for the python package. distil-whisper is a faster and better alternative. You can find it [here](https://github.com/huggingface/distil-whisper)
- TTS: a new model Parler is making the rounds. I've not yet tested it, but you can find it [here](https://github.com/huggingface/parler-tts). An alternative is pyTTSx3, which you can find [here](https://pypi.org/project/pyttsx3/).

If you do this, it would be cool to share your results & code with others so they can use it!

### More on vision language models
We will talk about more on 
## Other Links
- [www.sensemakersams.org](https://www.sensemakers.org) - Sensemakers website
- [www.meetup.com](https://www.meetup.com/sensemakersams/events/298443520/)  Link to Meetup 
- [slack channel](https://app.slack.com/client/T050EM77B/C06U9U221T6) Sensemakers Slack channel for questions

