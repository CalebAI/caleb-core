# Caleb (Core) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
Caleb is an open source and completely customizable Smart Assistant.
The aim of this project is to create a fully functioning and user friendly voice oriented smart assistant that could interact with you in multiple ways through "skills". 

In the market of voice oriented smart assistants, which is getting completely owned by big players like Google, Microsoft and Amazon, I think that a totally open source project which will run on a free OS like **Windows IOT**, powered by a cheap and affordable hardware like **Raspberry Pi 3**, could become something that people and developers will actually use and enjoy updating and changing as they please.

The entire system is being designed adopting C# .NET technology. 
In particular, the Core, Skills and the Enclosure, will be implemented as UWP apps and .NetStandard libraries running on Windows IOT. 

# Introduction

Caleb echosystem will be organised as follows:

The **Core** project will provide the Kernel, the basic architecture components the will be used by the **Features** to expose the actual functionalities and by the **Enclosure**, to send notificafion signals to any additional supported hardware like, lights, led screen, etc.

The Core will implement the basic data exchange between the components, the TTS (text to speech) engine and the NLP (natural language  processing) layer. The main purpose of Core is to simplify the feature implementation and enhance the modularity of the entire architecture.

The **Hardware Enclosure** is a low-level component which will sit right below the Core to handle the communication with any additional hardware like: lights, lcd screen, microphone, speakers. The hardware will be connected to the Giop ports of the Raspberry Pi. An example of usage could be to show updates and notifications on the lcd screen when a new email is received.

A **Feature** could be something relatively simple like checking your Gmail account, tell you the latest weather forecasts, advice you on the latest news. This is the kind of skills that Alexa, Google Home and Cortana already have, by the way, my vision of Caleb is to be much more than that. The idea of making the entire system open source should increment the amount of features that the app will be capable to fulfill, Caleb could be able to interact with as many smart appliances as possible, like Nest, WeMo, Blink. It could interact with your car, with your oven, with your fridge, it could even order for you groceries, checking what is missing from the fridge first. The possibilities are endless.

I strongly believe that sharing Quad source code could ignite the interest of the open source community, bringing the Artificial Intelligence and Voice Controlled software to grow faster making it available to everyone. My hope is to create a community around this project to create the most easy to use, efficient and reliable voice assistant available.

# Contributing

Caleb is completely open source. If you want to help, please follow the steps shown in the [Contribution guidelines](CONTRIBUTING.md).

