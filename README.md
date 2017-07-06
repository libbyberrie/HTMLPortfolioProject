# HTML Portfolio
This project jumps off from where the HTTP portforlia Project is left off. instead of following along with Bootstrap i created my own stylesheet and just fiddled around with it. 


TO DO: 
- [ ] change background image to something more subtle
- [ ] change colour scheme? 
- [ ] probably migrate all of this to a separate document instead of using the codeschool fork
- [ ] remove 'landing' link in favour for making a svg animation of the name that animates on hover (similarly to superhi?) 
- [ ] put proper content in there
- [ ] figure out where social links fit into all of this

This will not be a finial version of a website by any means, i feel like i would want the framework to be less static to accomodate for that, but it is a nice exercise. 

## Setup

Once you have cloned the forked repository, go into the directory containing the project and look for the `/src` directory. This is the directory where you will be making changes when you start following the step-by-step instructions. You can simply open those files in a text editor and get started.

You can always open the index.html file directly in your browser and work through the tasks below. You can also head over to the [Node.js](https://nodejs.org) website and follow the instructions to install Node on your machine. Once you have Node installed, open your command line and follow these instructions:

```
cd HTMLPortfolioProject
npm install
npm start
```

Running `npm start` should open a browser window pointing to `http://localhost:3000`. Now once you make changes to the files under the `/src` directory, your browser will refresh automatically, displaying the newest changes made to the files. This will save you the round trip of saving files and clicking refresh on your browser.


## Deploying

Putting this site up on GitHub pages is a bit different than some other projects because the code is all in the `/src` directory. There’s a nifty way to push this directory to a GitHub branch, which allows you to use GitHub pages with it! Try running this Git command for this project:

```
git subtree push --prefix src origin gh-pages
```

This will push the `src` folder up to GitHub on the `gh-pages` branch. After that, you should be able to open up `http://username.github.io/HTMLPortfolioProject`, where `username` is your GitHub username.
