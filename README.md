# A-Frame Boilerplate

Boilerplate for creating WebVR scenes using A-Frame.


## Getting Started

There are two easy options for obtaining this A-Frame scene. It's then up to you to make it your own!

### <sup>Option 1:</sup> Download the ZIP kit 📦

[<img src="http://i.imgur.com/UVPZoM0.png" width="200">](https://github.com/aframevr/aframe-jade-boilerplate/archive/master.zip)

After you have __[downloaded and extracted this `.zip` file](https://github.com/aframevr/aframe-jade-boilerplate/archive/master.zip)__ containing the contents of this repo, open the resulting directory, and you'll be have your scene ready in these few steps:

    npm install && npm start

<hr>

### <small><sup>Option 2:</sup> Fork this Git repo 🍴

Alternatively, you can __[fork this repo](https://github.com/aframevr/aframe-jade-boilerplate/fork)__ to get started, if you'd like to maintain a Git workflow.

After you have __[forked this repo](https://github.com/aframevr/aframe-jade-boilerplate/fork)__, clone a copy of your fork locally and you'll be have your scene ready in these few steps:

    git clone git@github.com:your_username/aframe-jade-boilerplate.git
    cd aframe-jade-boilerplate && npm install && npm start

### <small><sup>Option 3:</sup> Fork this CodePen example

Or, you can simply __[fork this CodePen example](http://codepen.io/kevining/pen/PZqaYw?editors=100)__ to dive right in. Enjoy!


## Publishing your scene

If you don't already know, GitHub offers free and awesome publishing of static sites through __[https://pages.github.com/](GitHub Pages)__.

To publish your scene to your personal GitHub Pages:

    npm run deploy

And, it'll now be live at __http://`your_username`.github.io/__ :)

<hr>

To know which GitHub repo to deploy to, the `deploy` script first looks at the optional [`repository` key](https://docs.npmjs.com/files/package.json#repository) in the [`package.json` file](package.json) (see [npm docs](https://docs.npmjs.com/files/package.json#repository) for sample usage). If the `repository` key is missing, the script falls back to using the local git repo's remote origin URL (you can run the local command `git remote -v` to see all your remotes; also, you may refer to the [GitHub docs](https://help.github.com/articles/about-remote-repositories/) for more information).

<hr>

## Still need Help?

### Installation

First make sure you have Node installed.

On Mac OS X, it's recommended to use [Homebrew](http://brew.sh/) to install Node + [npm](https://www.npmjs.com):

    brew install node

To install the Node dependencies:

    npm install


### Local Development

To serve the site from a simple Node development server:

    npm start

Then launch the site from your favourite browser:

[__http://localhost:3000/__](http://localhost:3000/)

If you wish to serve the site from a different port:

    PORT=8000 npm start


## License

This program is free software and is distributed under an [MIT License](LICENSE).
