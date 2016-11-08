# README

## Introduction

As part of the Makers Academy course we were tasked with creating development tool. My team settled on building a tool to help developers refactor their code.

[You can read more here](https://tomstuart92.github.io/portfolio/Recode/)

* If you’re testing the Heroku Project I suggest using my github username ‘TomStuart92’ and using the ‘RecodeTest’ repository which has a nice example file complete with a whole load of code smells.

## Install Instructions

- Fork and clone this repo to your local machine.   
- Run `bundle`.   
- Run `rackup`.   
- App is available on Localhost:9292 by default.   

## Analysis

Recode is integrated through the Github API, and allows you to run analysis for code smells and design anti-patterns on your project files. The current state of the project is very much at an MVP level, and is something I’d love to have a chance to look at further.

We wrote this project in Sinatra, which allowed us to take advantage of the dynamic paradigm of ruby. I’m particularly proud of the way the individual code analysers are built up, which makes the project very extendable.
