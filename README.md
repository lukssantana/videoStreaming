
<h1 align="center">
    <a href="#"> STREAMING PLAYER </a>
</h1>

<h3 align="center">
   Simple app of audio/video streaming POC that loads only a small portion of the buffered video!
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/lukssantana/videoStreaming?color=%2304D361">
	

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/lukssantana/videoStreaming">

  <!--<a href="https://www.twitter.com/tgmarinho/">
    <img alt="Siga no Twitter" src="https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2Ftgmarinho%2FREADME-ecoleta">
  </a>-->
  
  <a href="https://github.com/lukssantana/videoStreaming/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/lukssantana/videoStreaming">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/lukssantana/videoStreaming/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/lukssantana/videoStreaming?style=social">
  </a>
</p>


<h4 align="center"> 
	 Status: Finished
</h4>

<p align="center">
 <a href="#about">About</a> •
 <a href="#features">Features</a> •
 <a href="#how-it-works">How it works</a> • 
 <a href="#tech-stack">Tech Stack</a> • 
 <a href="#author">Author</a> • 
 <a href="#user-content-license">License</a>

</p>


## About

Straming Player - is a way to understand the application of the concept of streaming in a player, running the buffer received by the backend in small chunks.

---

## Features

- [x] Video player receives and plays bits of the received buffer:
   - [x] both in audio & video

---

## Layout

A simple html with the video tag.

---

## How it works

This app is divided into two parts:
1. Backend (server folder)
2. Frontend (web folder)


### Pre-requisites

Before you begin, you will need to have the following tools installed on your machine:
[Git] (https://git-scm.com), [Node.js] (https://nodejs.org/en/).
In addition, it is good to have an editor to work with the code like [VSCode] (https://code.visualstudio.com/)

#### Running the Backend (server)

```bash

# Clone this repository
$ git clone git@github.com:tgmarinho/README-ecoleta.git

# Access the project folder cmd/terminal
$ cd README-ecoleta

# go to the server folder
$ cd server

# install the dependencies
$ npm install

# Run the application in development mode
$ npm run dev:server

# The server will start at port: 3333 - go to http://localhost:3333

```
<p align="center">
  <a href="https://github.com/tgmarinho/README-ecoleta/blob/master/Insomnia_API_Ecoletajson.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

---

## Tech Stack

The following tools were used in the construction of the project:


#### [](https://github.com/tgmarinho/Ecoleta#server-nodejs--typescript)**Server**  ([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**

> See the file  [package.json](https://github.com/tgmarinho/README-ecoleta/blob/master/server/package.json)


#### [](https://github.com/tgmarinho/Ecoleta#utilit%C3%A1rios)**Utilitários**

-   API Test:  **[Insomnia](https://insomnia.rest/)**

---

## Contributors

POC - no contributors at moment.


## How to contribute

1. Fork the project.
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save your changes and create a commit message telling you what you did: `git commit -m" feature: My new feature "`
4. Submit your changes: `git push origin my-feature`
> If you have any questions check this [guide on how to contribute](./CONTRIBUTING.md)

---

## Author

<a href="https://www.linkedin.com/in/lukssantanna/">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/23119212?v=4" width="100px;" alt="Lucas Santanna"/>
 <br />
 <sub><b>Lucas Santanna</b></sub></a>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Lucas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lukssantanna/)](https://www.linkedin.com/in/lukssantanna/) 
[![Gmail Badge](https://img.shields.io/badge/-luks.santanna@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:luks.santanna@gmail.com)](mailto:luks.santanna@gmail.com)

---

## License

This project is under the license [MIT](./LICENSE).

Made with love to learn and technology by Lucas Santana 👋🏽 [Get in Touch!](https://www.linkedin.com/in/lukssantanna/)

---

##  Versions of README

[English Version](./README.md)
