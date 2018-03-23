# CheckTone
A Social Listening application that checks tone of tweets based on a certain Twitter hashtag

## Getting Started

1. You need to have Node.js installed. You can download and install Node.js [here](http://nodejs.org/)

2. You need to create a Twitter application to generate credentials to consume Twitter API. You can do so [here](http://dev.twitter.com/apps)

3. You need to create a Tone Analyzer service instance on IBM Cloud to generate credentials to use the Watson Tone Analyzer API. There's a short tutorial [here](https://medium.com/ibm-watson-tutorials/getting-started-with-ibm-watson-95b10ca145f6)

4. Clone this repository.

5. Create a `.env` file in the root directory. The `.env` file will look something like the following:

  ```none
    TWITTER_CONSUMER_KEY = <Twitter Consumer Key>
    TWITTER_CONSUMER_SECRET = <Twitter Consumer Secret>
    TWITTER_ACCESS_TOKEN = <Twitter Access Token>
    TWITTER_ACCESS_TOKEN_SECRET = <Twitter Access Token Secret>
    TONE_ANALYZER_USERNAME = <Service credential>
    TONE_ANALYZER_PASSWORD = <Service credential>
    TONE_ANALYZER_VERSION_DATE = <Check service documentation for most recent date>
  ```

6. Install the dependencies your application needs:

  ```none
  npm install
  ```
7. Start the application locally:

  ```none
  npm start
  ```

8. Point your browser to http://localhost:3000
