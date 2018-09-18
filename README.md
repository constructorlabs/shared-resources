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

## CSS

## Array methods

## Scope

## Objects

## DOM and Events

## fetch and AJAX

## Tools

## Git

**Resetting code to last commit** - this will abandon any changes and load code as it was at last commit

- `git reset head --hard`

**Clone repo into new folder** - if you want to clone some else's repo without affecting your own copy you can clone it into a new folder. From `workspace` run

- git clone <clone url> <folder name>

For example running `git clone git@github.com:constructorlabs/shared-resources.git my-resources` will create a folder called `my-resources` inside current folder and clone `shared-resources` repo into the folder.
