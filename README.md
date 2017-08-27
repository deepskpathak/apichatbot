## Alfred

#### A simple chat bot based on API.AI, Web Speech API, Socket.io and Node.js

Web Speech API is experimental with [limited](http://caniuse.com/#search=speech) support.


This is how this web app works:

1. Using the Web Speech API’s `SpeechRecognition` interface to listen your voice from a microphone
2. Send your message to [API.ai](https://api.ai) (the natural language processing platform) as a text string
3. Once the AI from the API.ai returns the reply text back, use the `SpeechSynthesis` interface to give it a synthetic voice.




#### For local development

- API.ai API key (as an env var).
- Install Node.js dependencies , `npm install`
- Run `npm start`


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/girliemac/web-speech-ai)



