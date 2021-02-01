German Reproducibility Network (GRN) Website
============================================

This repository contains the raw files used to build the GRN homepage.

Usage
-----

Any changes to this git repository will be taken into account by our hosting provider, [Netlify](https://netlify.com/). They will also create a preview version for every submitted pull request -- you will find a link to this deploy preview in the testing report that is automatically generated when you submit a PR.

### Local development

To reproduce the website on your local computer, and apply changes without interacting with either GitHub or Netlify, you can download this repository, and setup a local development environment.

You will need a copy of [node.js](https://nodejs.org/) installed on your computer, as well as the [Zola](https://getzola.org/) static site generator. From a console, run `npm install` to download the project dependencies, and `npm run copy_static` to copy third-party static files into the correct locations.

With the project dependencies in place, run `zola serve` to start a (temporary) local development server, and `zola build` to build a copy of the website that you could upload to a web server.
