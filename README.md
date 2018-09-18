# Shared resources

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

## HTML

- [https://internetingishard.com/](https://internetingishard.com/)
- [SATAN EXPLAINS HTML using DEATH METAL](https://www.youtube.com/watch?v=27dnddCq5gc)

## CSS

- [http://jxnblk.com/hello-color](http://jxnblk.com/hello-color)
- [CSS Diner](https://flukeout.github.io/)
- [Coolers](https://coolors.co/)
  > Nice colour scheme tool for the aesthetically challenged.

### Flex

- [https://css-tricks.com/snippets/css/a-guide-to-flexbox/](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [http://flexbox.malven.co/](http://flexbox.malven.co/)
- [http://flexboxfroggy.com/](http://flexboxfroggy.com/)

### Grid

- [http://grid.malven.co/](http://grid.malven.co/)
- [https://cssgridgarden.com/](https://cssgridgarden.com/)
- [Layout land, real world examples](https://www.youtube.com/watch?v=FEnRpy9Xfes&list=PLbSquHt1VCf1x_-1ytlVMT0AMwADlWtc1)

## Array methods

- [https://doesitmutate.xyz/](https://doesitmutate.xyz/)

> Does it mutate??

## Scope

- [You Don't Know JavaScript Exercises](https://ydkjs-exercises.com/scope-closures/ch1/q1)

> Some people on Reddit got together and made a quiz based on the contents of `You Don't Know JavaScript`.

## Objects

## DOM and Events

## fetch and AJAX

- [https://github.com/toddmotto/public-apis](https://github.com/toddmotto/public-apis)

## Tools

[http://tachyons.io/xray/](http://tachyons.io/xray/)

> rips out colors and applies a grid and borders.

[https://prettier.io/](https://prettier.io/)

> Awesome, can't live with out it.

[WAVE - Web Accessibility Evaluation Tool](https://wave.webaim.org/)

> Evaluates your page to see how accessible it is to things like screen readers.

[WhatFont?](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?hl=en)

> Find out what font styles are being used on a page and shamelessly steal them for yourself.

## VS Code

- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Open in Browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [Debugger for Chrome ](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)

## Git

**Resetting code to last commit** - this will abandon any changes and load code as it was at last commit

- `git reset head --hard`

**Clone repo into new folder** - if you want to clone some else's repo without affecting your own copy you can clone it into a new folder. From `workspace` run

- git clone <clone url> <folder name>

For example running `git clone git@github.com:constructorlabs/shared-resources.git my-resources` will create a folder called `my-resources` inside current folder and clone `shared-resources` repo into the folder.
