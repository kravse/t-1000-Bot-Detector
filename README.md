# T-1000 Bot Detection Chrome Extension
T-1000 is a chrome extension that helps users detect bot generated text. Users can paste in text from any website and check to see if it is generated by language models. On twitter, the extension can auto-fetch text from tweets. 

Built with the [cohere.ai](https://cohere.ai) NLP API. This is a work in progress.

### Paste some text and the t-1000 will analyze it for you.
![extension example](./src/images/extension-example.png)

### Or auto-populate by clicking the t-1000 button on tweets.
![twitter](./src/images/twitter-example.png)


# Dev Instructions:

#### Install Dependencies
```bash
npm install
```
#### Build for production
```bash
npm run build
```

Load dist as an upacked extension in chrome.
