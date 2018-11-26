# Developer resources

## Contributing guide

- To get started fork and clone this repo
- To add more information first create new branch using `git checkout -b <branch name>`
- Add information to this README file. It uses markdown formatting [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)
- Once information has been saved in README. Use `git commit -am "<commit message>"` to commit changes to your branch
- Push your branch up to your forked repo using `git push origin head`
- Once branch is pushed up create a pull request
- **Important** make all your changes on your feature branch not master.

## Getting updates from upstream

- The first time you want to get latest changes from upstream repo you will need to add it as a remote.
- To do that run `git remote add upstream git@github.com:constructorlabs/shared-resources.git`. You only need to do that once
- All changes will be coming in on master branch. Make sure you are on master branch before pulling down changes - `git checkout master`
- To pull latest changes to master from upstream run `git pull upstream master`
- At this stage you can checkout a feature branch as above and continue as before.

## JS

- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
  > JS bible book
- [Step through code visualiser](https://tylermcginnis.com/javascript-visualizer/)
  > ES5 only at the moment

### Methods

- [Does it mutate?](https://doesitmutate.xyz/)
- [Hungarian Dancers demonstrate sort method!](https://www.youtube.com/watch?v=lyZQPjUT5B4&feature=youtu.be)

### Arrays

- [W3 concise list of array methods](https://www.w3schools.com/jsref/jsref_obj_array.asp)

### Objects

### Scope

- [You Don't Know JavaScript Exercises](https://ydkjs-exercises.com/scope-closures/ch1/q1)

> Some people on Reddit got together and made a quiz based on the contents of `You Don't Know JavaScript`.

- [JS Essentials: Objects](https://codeburst.io/javascript-essentials-objects-56373a1a6bfb)

### DOM and Events

### Fetch and AJAX

- [https://github.com/toddmotto/public-apis](https://github.com/toddmotto/public-apis)

### Debugging

- [Debug like a pro](https://itnext.io/10-console-tricks-to-debug-like-a-pro-66ee2225ec57)
  > 10 x console tricks `Medium`

### Regex

- [Regex Cheatsheet](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

## React

- [React Cheat Sheet 1](http://www.developer-cheatsheets.com/react)
- [React Cheat Sheet 2](https://devhints.io/react)

- [Beginners guide to React](https://www.youtube.com/playlist?list=PL55RiY5tL51oyA8euSROLjMFZbXaV7skS) - 2nd video helps explain what the webpack.config file is doing, afterwards going on to clearly explain building individual components.
- [React Fundamentals](https://medium.freecodecamp.org/these-react-fundamentals-you-skip-may-be-killing-you-7629fb87dd4an) Article on component render, props and state
- NPM packages:

  - [shuffle array](https://www.npmjs.com/package/shuffle-array)
  - [decode html entities](https://www.npmjs.com/package/he)
    `decode(&quot;string&quot;)`
    returns "string"

- [Formik](https://jaredpalmer.com/formik/docs/overview)

## Redux

- [Learn Redux video](https://www.youtube.com/watch?v=Jy-xXB8O12I)
- [Another helpful Redux vid](https://www.youtube.com/watch?v=OSSpVLpuVWA)

- [That gif diagram](https://raw.githubusercontent.com/urunium/Urunium.Redux/master/resources/redux.gif)

- AND… State > mapStateToProps > Component > mapDispatchToProps > Action > Reducer > State

## Testing with Jest

[Jest: Expect matchers](https://jestjs.io/docs/en/expect)

- jest.config.js

```
module.exports = {
    testURL: 'http://localhost:8080'
}
```

- Tests with verbose explanations - launch with:

```
npm test -- --verbose
```

## Node

- [Jim's node slides](https://constructorlabs-node-slides.firebaseapp.com/)
- [Nodemon - auto restart node](https://github.com/remy/nodemon)

  - Install using `npm install --save-dev nodemon`
  - Add entry to the `scripts` object in your `package.json` file:

  ```
  "scripts": {
  "start": "nodemon index.js"
  }
  ```

  - Start using `npm start`

- [Build Restful APIs using Node and Express](https://www.youtube.com/watch?v=pKd0Rpw7O48)

- [Node Handbook - FreeCodeCamp](https://medium.freecodecamp.org/the-definitive-node-js-handbook-6912378afc6e)

### HTTP status ranges in a nutshell:

- 1xx: hold on
- 2xx: here you go
- 3xx: go away
- 4xx: you fucked up
- 5xx: I fucked up

## Databases

- NB using **Postgres 10**.

  > Beware that google will take you to documentation for completely arbitrary versions of postgres -- always click the version number link at the top of the page!

- [Postgres keywords](https://www.postgresql.org/docs/10/sql-keywords-appendix.html)

- [Test DB queries direct in VS Code](https://marketplace.visualstudio.com/items?itemName=ckolkman.vscode-postgres)
  > NB not for creating tables

## HTML

- [https://internetingishard.com/](https://internetingishard.com/)
- [SATAN EXPLAINS HTML using DEATH METAL](https://www.youtube.com/watch?v=27dnddCq5gc)
- [Wes Bos: Easy Creation of HTML with JavaScript’s Template Strings](https://wesbos.com/template-strings-html/)
  > 👏 THIS. 👏 IS. 👏 AMAZING. 👏 How to create HTML elements from arrays using template strings. 🔥💯💪

## CSS

- https://mobbin.design/?ref=producthunt
- [Hello Color](http://jxnblk.com/hello-color)
- [CSS Diner](https://flukeout.github.io/)
- [Coolers](https://coolors.co/)
  > Nice colour scheme tool for the aesthetically challenged.
- [Type-Scale](https://type-scale.com/)
- [Dribbble](https://dribbble.com/)
- [css cheatsheet](https://devhints.io/css)
- [selectors](https://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)

### Flexbox

- [https://css-tricks.com/snippets/css/a-guide-to-flexbox/](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [http://flexbox.malven.co/](http://flexbox.malven.co/)
- [http://flexboxfroggy.com/](http://flexboxfroggy.com/)
- [freeCodeCamp CSS Flexbox course](https://www.youtube.com/watch?v=-Wlt8NRtOpo&t=2078s)

### Grid

- [http://grid.malven.co/](http://grid.malven.co/)
- [https://cssgridgarden.com/](https://cssgridgarden.com/)
- [Layout land, real world examples](https://www.youtube.com/watch?v=FEnRpy9Xfes&list=PLbSquHt1VCf1x_-1ytlVMT0AMwADlWtc1)

## Tools

- [NPM - list installed](https://docs.npmjs.com/cli/ls)

- **Webpack**
  A word to the wise -- if you are following the 'Starting a new project' guide from the syllabus, your webpack bundle will be created in `/static/bundle.js` rather than `/dist/bundle.js`. You can fix this by replacing the word 'static' with 'dist' within webpack.config.js (edited)

- **Babel**

  > Stay away from version 7 as it's not compatible with 6, which your currently using.

- [Prettier and ES Lint - tools for clean coding](https://medium.freecodecamp.org/these-tools-will-help-you-write-clean-code-da4b5401f68e)

- [Marrying Prettier and ES Lint](https://blog.echobind.com/integrating-prettier-eslint-airbnb-style-guide-in-vscode-47f07b5d7d6a)

- [https://docs.emmet.io/cheat-sheet/](https://docs.emmet.io/cheat-sheet/)

- [http://tachyons.io/xray/](http://tachyons.io/xray/)

  > rips out colors and applies a grid and borders.

- [https://prettier.io/](https://prettier.io/)

  > Awesome, can't live with out it.

- [WAVE - Web Accessibility Evaluation Tool](https://wave.webaim.org/)

  > Evaluates your page to see how accessible it is to things like screen readers.

- [WhatFont?](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?hl=en)

  > Find out what font styles are being used on a page and shamelessly steal them for yourself.

- [sizzy.co](https://sizzy.co)

  > For testing responsiveness

- [frontendchecklist.io](https://frontendchecklist.io/)
  > The Front-End Checklist Application

## Security

- [Cross-origin resource sharing](http://performantcode.com/web/do-you-really-know-cors)

## Performance

- [JS performance issues](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4)

## VS Code

- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Open in Browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [Debugger for Chrome ](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
- [VS Code extensions](https://codeburst.io/top-javascript-vscode-extensions-for-faster-development-c687c39596f5)

## Design, UI and UX

- [Figma wireframs](https://www.figma.com)
- [Form design tips](https://uxdesign.cc/design-better-forms-96fadca0f49c)

- [Noun project](https://thenounproject.com/)
  > Icons for everything

**Free photo galleries**

- [Unsplash](https://unsplash.com)
- [Pixabay](https://pixabay.com)

**Photo editing software**

- [Affinity Photo](https://affinity.serif.com/en-gb/photo/desktop/)
  > A much cheaper alternative to Adobe Photoshop, recommened by Jonny

**Logo generator**

- [Logo Joy](https://logojoy.com/explore)

## Git

[Oh shit, git!](https://ohshitgit.com/)

**Resetting code to last commit** - this will abandon any changes and load code as it was at last commit

- `git reset head --hard`

**Clone repo into new folder** - if you want to clone some else's repo without affecting your own copy you can clone it into a new folder. From `workspace` run

- git clone <clone url> <folder name>

For example running `git clone git@github.com:constructorlabs/shared-resources.git my-resources` will create a folder called `my-resources` inside current folder and clone `shared-resources` repo into the folder.

**[Learn Git Branching](https://learngitbranching.js.org/)**

## Markdown

- [Markdown formatting](https://guides.github.com/features/mastering-markdown/)

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Interesting…

[Commented dead code and what to do with it](https://dev.to/damnjan/dead-code---alive-problem-2job)

[State of JS 2018](https://2018.stateofjs.com/introduction)

[Guide to becoming a dev 2018](https://codeburst.io/the-2018-web-developer-roadmap-826b1b806e8d)
