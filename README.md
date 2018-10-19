# restaurantReviewsAppStage1

# Front-End Web Developer Nanodegree

## Project Overview: Stage 1

In this project, we will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. we will also add a service worker to begin the process of creating a seamless offline experience for our users.

### Specification

We have been provided the code for a restaurant reviews website by Udacity. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Our job is to update the code to resolve these issues while still maintaining the included functionality. 

### What do we do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on our local computer. Python has some simple tools to do this, and we don't even need to know Python. For most people, it's already installed on our computer. 

In a terminal, check the version of Python one have: `python -V`. If one have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, one can use `python3 -m http.server 8000`. If one don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With the server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.

4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). One need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript one write. 
