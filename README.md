# Learn How to Make a Website with Steph

## Capstone Project Lessons

> **Are you brand new to web development?** [Start with the "Foundations" part of this course](https://github.com/5t3ph/howtowebdev) to learn the basics of HTML and CSS.

## Starting the Capstone Course

Begin by cloning this repo, and then visit [LearnWithSteph.dev](https://learnwithsteph.dev) to view all available videos and supplemental transcripts.

## General use of this repo

This repo uses what's called "yarn workspaces" meaning it's managed with `yarn` instead of `npm`.

However, individual lessons can be run with either `yarn` or `npm`. They can also be pulled out individually into a new project.

All of the following scripts intended to be run in the root package.

1. `yarn` installs all dependencies.
1. `yarn start 01` (replace with lesson number or keyword) runs the project in the browser.
1. `yarn latest` updates all dependencies.
1. `yarn clean:node_modules` deletes `node_modules` recursively.
