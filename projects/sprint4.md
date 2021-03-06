---
title: Sprint 4 Project
layout: page
---

## 🚀 gitg0

[![NPM](https://nodei.co/npm/gitg0.png)](https://npmjs.org/package/gitg0)

gitg0 is a command line tool which makes lives of both project maintainers and contributors easy 😌. How does gitg0 do that❓

### For contributors and developers 👨‍💻

- Ever spent 2-3 minutes before working on thinking what to name your branch? ⸙
- After making the changes, spent time on wondering about an appropriate commit message? 🖋️
- After a long hectic day of working, skipped over the commit guidelines followed by your project? 😴
- Felt like your commit message could be a bit better if it had an emoji? ✨

Well, gitg0 takes care of all this and much more!
You just need to enter the number of the issue you're working on, and select what kind of issue it is, whether a new feature, ui refactors, documentation, security fixes, etc. gitg0 will do the rest for you. The tool will automatically suggest a branch name, and a commit message as well along with an appropriate emoji if you want one!

Head over [here](https://github.com/dotrachit/gitg0/tree/readme#-usage) for instructions on how to use gitg0 🎁

### For maintainers 👩‍🔧

Tired of telling contributors to follow proper commit guidelines? 😫

Fear no more, gitg0 is here! With gitg0, you can setup a `.gitgo` file and choose exactly what commit guidelines your project follows. You want an emoji? We got you covered. You want to enter a custom set of guidelines? We provide an option for that as well. Just eenter the format in which you want your commits to be, and that is the format in which the commit message that will be shown to contributors when they want to make a commit.

Head over [here](https://github.com/dotrachit/gitg0/tree/readme#-usage) for instructions on how to do the one time gitgo setup 🎁

## 💻 What did we use?

gitg0 has been developed completely in javascript.

## 🔨 Installation

The tool is available as an npm package over [here](https://www.npmjs.com/package/gitg0).

Before installing the package, [download and install Node.js](https://nodejs.org/en/download/).
Then you can install it by simple running the following command:

```bash
npm i gitg0
```

## 🎮 Usage

Currently, we have the following 6 commands which will make you **Good To Go**, `gtg`:

### `gtg whoami`

As the name suggests this command will help you know what the tool does and how to use the commands right from your terminal.

### `gtg config`

This commands should be used on for the first time, while setting up the gitgo configuration. You will be asked a small set of questions regarding your commit and emoji preferences. If you would like to change these preferences sometime in future, you can run this command again to make the changes.

### `gtg start`

Everytime you start working on a new issue, just run this command in order for the tool to know which issue you're working on. After this, the tool will suggest the branch names and commit messages automatically.

### `gtg display`

This command can be used to display the branch name and commit that the tool will be suggesting for a particular issue once `gtg start` has been run.

### `gtg checkout`

This is a replacement for `git checkout` and will simply checkout with the suggested branch name.

### `gtg commit`

This is a replacement for `git commit` and will commit your files once added with the suggested commit message.

## 👨‍💻 For contributors

- Before contributing do go through the [Code of Conduct](https://github.com/dotrachit/gitg0/blob/main/CODE_OF_CONDUCT.md) and the [Contributor Guidelines](https://github.com/dotrachit/gitg0/blob/main/CONTRIBUTING.md). 🔧
- If you find any bugs in the application, or a feature you think would be nice to have, please open an [issue](https://github.com/dotrachit/gitg0/issues/new/choose). 🐞
- Continue reading the rest of the README to get the build instructions. ⛏️
- For detailed information and screenshots of the project, please head over to the project [wiki](https://github.com/dotrachit/gitg0/wiki). 📚

## 🛠️ Setting up the project

Before setting up the project, [download and install Node.js](https://nodejs.org/en/download/).

After cloning the project, you need to execute the following commands to install and work on the project locally:

```bash
# This will install alll the needed dependencies
npm install

# This will install the project from source locally in your system
npm install -g ./
```

## Link to the project

[https://github.com/yashk2000/gitg0](https://github.com/yashk2000/gitg0)