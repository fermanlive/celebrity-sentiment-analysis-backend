# Celebrity Sentiment Analysis Backend
This is the backend for a celebrity sentiment analysis application that uses the Go programming language. The backend is responsible for processing and analyzing tweets related to a specific celebrity and determining the overall sentiment towards that celebrity.

## Requirements
* Go (version 1.15 or higher)
* Go libraries:
* twitter (for accessing the Twitter API)
* go-sentiment (for sentiment analysis)
* gorilla/mux (for routing)

## Installation
1. Clone this repository to your local machine
2. Run go mod download to download the necessary libraries
3. Run go build to build the executable file
4. Run the executable file to start the backend server

## API Endpoints
The backend has the following API endpoints:

* GET /celebrity/{celebrity_name}: returns the overall sentiment towards the specified celebrity
* GET /celebrity/{celebrity_name}/recent: returns the most recent tweets and sentiment towards the specified celebrity

## Twitter API
To access the twitter API, you need to create a developer account on twitter developer and use the API keys to configure the application.

## Sentiment Analysis
The go-sentiment library is used for sentiment analysis. It uses a pre-trained model to classify the sentiment of tweets as positive, neutral or negative.

## Conclusion
This backend is a simple yet powerful tool for analyzing the sentiment towards a specific celebrity on Twitter. With this backend, you can easily retrieve real-time sentiment data and analyze how people feel about a celebrity at any given time.
