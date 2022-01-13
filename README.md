# Astro Offline Demo

This repository is an example of how to use Astro web components locally, entirely offline. All dependencies have been downloaded manually. Google's Roboto and Roboto Mono fonts have been downloaded and installed locally. 

## Installation

You can download this repo as a zip and upload it to a production server.

### Running locally 

Because of CORS, you won't be able to just simply open the index.html file in your browser. You'll need to setup any kind of server locally. 
The easiest method would be to use [http-server](https://github.com/http-party/http-server) to spin up a quick node server. You don't have to use node, you can use whatever you are comfortable with. 

In the root of this project run:

`npm i http-server`
`http-server` 

and the project should be available at `http://127.0.0.1:8080/`


