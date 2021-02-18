# Sezzle Coding Challenge - Nirbhay Vig

## How to access:

### Method 1: Web

To access the project on the world wide web, navigate to https://salty-fjord-30434.herokuapp.com/

### Method 2: Docker

I have added a Dockerfile to the project. To run please follow these steps:

1. Make sure docker is installed on your machine
2. Open a command terminal and pull the latest image with the following command

        docker pull piro844/node-web-app
3. Run the docker image

        docker run -p 3000:3000 -d piro844/node-web-app:latest
4. Now navigate to **http://localhost:3000/**

## How to use:

1. Follow the access methods listed above to get to the site
2. To use the calculator you can either **click the buttons** or **type in the top text box**
3. Once you are ready to evalulate **click the '=' button** or **press the enter key**
4. Enjoy! The results will show up on the right side of the screen, and you can only see up to the 10 most recent results.
