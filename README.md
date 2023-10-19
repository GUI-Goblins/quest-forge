# Quest-forge

[Logo](./QuestForge.png)

## Application Description (About)

* QuestForge is  A text-based, Dungeons and Dragons themed choose your own adventure game. Users will be able to interact with responsive story prompts, and have a host of story options in order to decide their fate! NPC's and story dialogue will be generated via OpenAI integration.

## Authors

* [Chester Lee Coloma] (<https://github.com/cleecoloma>)
* [Joshua Shea] (<https://github.com/jshea44>)
* [Anthony Cunningham] (<https://github.com/Spacecowboi>)

## Features

* Choose your own adventure!
* Interactive story prompts
* AI-Generated Dialogue and walkthrough
* D&D themed storytelling and immersion

## Installation

* Clone down the respective repos located on our organization page (<https://github.com/GUI-Goblins>)
* Create API Gateway on AWS
* Create 3 separate lambda functions named after the repos
* Export the code located in the respective repos to AWS
* Check your cloudwatch logs! (for now)

## Dependencies 

* aws-sdk
* dynamoose
* dynamoDB
* environment variables
    * Please create an OpenAI account if you do not already have one, and generate a secret key as you will need it in order to access the API!
    * Place the Secret Key into your environment variable as a value with a key of "OPENAI_API_KEY"

