# Submission name: Communicate-Comprehend-Collaborate (CCC)


## Contents

1. [Short description](#short-description)
1. [Demo video](#demo-video)
1. [The architecture](#the-architecture)
1. [Long description](#long-description)
1. [Project roadmap](#project-roadmap)
1. [Getting started](#getting-started)
1. [Running the tests](#running-the-tests)
1. [Live demo](#live-demo)
1. [Built with](#built-with)
1. [Contributing](#contributing)
1. [Versioning](#versioning)
1. [Authors](#authors)
1. [License](#license)
1. [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?

During emergency connecting helplines is extremely troublesome due to stuffed lines/occupied lines. A human helpline can't answer the primary call and last call without breaking a sweat as a result of same inquiry being posed over and over and furthermore tedious.

How to make information sharing easier during crisis?

How to prevent panic situations as numerous individuals are getting un authentic/un reliable  information during crisis?

How about providing insights on the crisis to the government agents who has to respond quickly on the need basis?


### How can technology help?

The proposed solution helps public and government. This helps to reduce the communication gaps provides answers to the public queries which is always going to be authentic information. In addition to that system analyze this data to let government know about public needs.

### The idea

Combat using Commbot helps government agents and users. 

1)	This will help users being panic with un authenticated information
2)	This will also help users to find out everything at one place.
3)	This helps government agents (police/volunteer) reduce the risk of getting impacted with the disease. As it will reduce the public contact with government         agents for enquiries.
4)	Access information faster, avoiding communication and information gaps
5)	Help governments gather analytics of how many people are being helped and their safety status, as chatbots voluntarily get in touch with users who interacted
6)	Resolve critical requests quickly without waiting for a human agent
7)	Offer agility to responsiveness 

## Demo video

[![Watch the video](https://github.com/Code-and-Response/Liquid-Prep/blob/master/images/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

## The architecture

![Video transcription/translation app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Long description

[More detail is available here](DESCRIPTION.md)

## Project roadmap

![Roadmap](roadmap.jpg)

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```bash
dnf install wget
wget http://www.example.com/install.sh
bash install.sh
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be, for example

```bash
export TOKEN="fffd0923aa667c617a62f5A_fake_token754a2ad06cc9903543f1e85"
export EMAIL="jane@example.com"
dnf install npm
node samplefile.js
Server running at http://127.0.0.1:3000/
```

And repeat

```bash
curl localhost:3000
Thanks for looking at Code-and-Response!
```

End with an example of getting some data out of the system or using it for a little demo




## Built with

* Text to Speech- This can be used to convert Watson Assistant output text into voice for end user
* Speech to Text - This can be used to convert user voice to text which is feed to Watson Assistant
* Machine Learning: This is used for detecting user voice and deep learning
* Watson Assistant- This is used for the chatbot integration
* Watson discovery– Watson Discovery scans preloaded documents/news articles and responds with relevant information.
* Watson Translation – This can translate the text to the desired language.
* Watson NLP and NLU- This can be used to understand & analyze end user questions and derive insights


## Versioning

 https://github.com/ratnamalubelli/CCC

## Authors

* ** Ratnam Alubelli (Valubell@in.ibm.com)


## License

This project is licensed under the IBM Cloud


