---
layout: page
title: Programming Tutorials/Challenges
permalink: /
---

# Programming Tutorials/Challenges
```java
// Java
static String[] repository = new String[3];
repository[0] = "Java and Javascript tutorials";
repository[1] = "a collection of programming challenges";
repository[2] = "sample solution code and writeups";

System.out.println("This repository contains");
for (int i = 0, length = repository.length; i < length; i++) {
	System.out.println(" - " + repository[i]);
}
```
```js
// Javascript
var repository = []
repository.push('Java and Javascript tutorials')
repository.push('a collection of programming challenges')
repository.push('sample solution code and writeups')

console.log('This repository contains')
for (var i = 0, length = repository.length; i < length; i++) {
  console.log(' - ' + repository[i])
}
```
```
This repository contains
 - Java and Javascript tutorials
 - a collection of programming challenges
 - sample solution code and writeups
```
## Introduction
The aim of this repository is to teach programming concepts from the very basic to the very advanced.
> Most good programmers do programming not because they expect to get paid or get adulation by the public, but because it is fun to program.

Both Java and Javascript solutions and writeups are provided for each challenge, as well as additional language-specific tutorials and tutorials on additional development tools. Challenges are divided into several difficulty levels: `Basic`, `Intermediate`, and `Advanced`. Challenges of each difficulty are found within their respective directory. Within each difficulty directory are located numbered challenge directories. The challenges are ordered such that higher numbered challenges build upon concepts covered in lower numbered challenges.

Located inside each challenge directory is a `README` file which describes the challenge. This file also includes a small extra challenge which expands upon the initial challenge. Template files to start the challenge with are located within each of the language directories. Also provided are solution files containing example solution code. Below is an example of the directory structure.
```
Basic
└───Challenge 1
    ├───Java
    │   │   README.md
    │   │   solution.java
    │   │   app.java
    ├───Javascript
    │   │   index.html
    │   │   README.md
    │   │   solution.js
    │   │   template.js
```
Solution writeups for each challenge are located in the [Wiki](https://github.com/andrewmthomas87/Tutorials/wiki). Other tutorials on additional development tools such as `git` are located there as well.
## Java
Java introduction here.
## Javascript
To start off, let's throw out a common misconception. ~~Javascript is Java~~ (not true). Javascript is actually an entirely different programming language than Java. Javascript and Java are similar in some ways but fundamentally different in others.
> Javascript is to Java as carpet is to car

So what is Javascript? Javascript is a small and lightweight, cross-platform, object-oriented scripting language. Javascript is generally found in two flavors, `client-side` Javascript and `server-side` Javascript. In these tutorials and challenges, the focus is on `client-side` code, but mainly just the core Javascript language. Although basic HTML is included to allow for running challenge code in a browser, the focus is on Javascript.
