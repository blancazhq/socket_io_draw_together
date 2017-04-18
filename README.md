# Draw Together

## Introduction

Draw Together is an app that built with Node.js, Express and Socket.io. Multiple User can use this app to draw and chat at the same time. The painting and the message are sent to all the users real-time. Moreover, new users logged-in can see what has been drawn previously.

## Collaborator
* Debra Mae Lee

## Technologies We Used
* HTML
* CSS
* Node.js

## Node Modules We Used
* express
* handlebars
* socket.io

## Functionalities
![start_screen](./public/assets/start_screen.png?raw=true "start_screen")
![drawing and chatting](./public/assets/drawing.png?raw=true "drawing and chatting")

## Challenges
When we set the form for user to chose color and brush thickness, there was a submit button. At the first, we set the event listener to the submit event of that form, but the problems were 1) users always forgot to press the submit button after they made the change; 2) after drawing each stoke, the user had to press submit so that the changes will get recorded in the history. We made improvement by getting rid of the submit button, and also not by not sending the drawing event information until the actual drawing start instead of when the changing of the setting happens.
