# starter-repo
This is a starter repo for learning anything realted to JavaScript/CSS offline.

This is a package for my personal use.
But feel free to use it for your own purposes (if at all necessary).

This is the offline version of now-a-days online editors like jsfiddle, jsbin, etc.

Now, I have nothing against these awesome online editors, but personally, its not always convenient to fire an online IDE and work.  
So I wanted to have a way in which I get the basic setup ready for using ES6 and Less without much effort to get up and running.

### Directory structure
1. All script files go in app/scripts with app.js as the entry file. Any subdirectory structure inside is supported out of the box.
2. All style files go in app/styles with app.less as the entry file. Any subdirectory structure inside is supported out of the box.
3. ES6 is supported for all js files while less is supported for all style files.

### Getting started
1. Make sure you have node.js installed. If not please do it from their [official website](https://nodejs.org/en/)  
2. I personally prefer [yarn](https://yarnpkg.com/lang/en/) but even if you use [npm](https://www.npmjs.com/), it should be fine. I am neutral about npm. So no hard feelings intended!
3. Clone the repo or download using zip.
4. cd into starter-repo
5. If you are using npm run  
    `npm install`  
    If you are using yarn then  
    `yarn install`
6. To start the server and watch files continuously inside the app directory to restart the server, run the command  
    `npm run serve`  
    OR  
    `yarn serve`

I hope it proves useful to someone. It did for me atleast!