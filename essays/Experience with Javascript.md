---
layout: essay
type: essay
title: Experience with Javascript
date: 2019-12-13
labels:
  - Software Engineering
  - Learning
  - JavaScript
  - WOD
 
---
## What is Javascript?

Javascript is a scripting or programming language that allows you implement complex features on web pages. Implementing Javascript makes a web page more dynamic instead of just displaying static information. Examples include displaying timely content updates, interactive maps, animated 2D/3D graphics, photo slideshows,  scrolling video jukeboxes, etc.

## The Power of 3

There are three main elements that form the backbone of web development. That is HTML, CSS, and Javascript.

- **HTML** is the structure of your page - the headers, body text, any images you want to include.
- **CSS** controls how that page looks such as customizing fonts, background colors, etc.
- **Javascript** is the magic third element. Once you've created your structure (HTML) and your aesthetic vibe (CSS), Javascript makes your web page dynamic.

## What can Javascript do?
We all know that Javascript turns your static web page of text into a functional dynamic web page. But it not just limited to front-end development. Javascript is also used for:

- **Developing mobile applications** - it is used to create those apps you have on your phone or tablet as well.

- **Creating web browser based games** - it is used to create web browser games.

- **Back-end web development** - Javascript is mostly used for fron-end developing but it's a versatile enough scripting language to be used on back end infrastructure too


Example for simple text label:

After adding CSS:
```
p {
     font-family: 'helvetica neue', helvetica, sans-serif;
     letter-spacing: 1px;
     text-transform: uppercase;
     text-align: center;
     border: 2px solid rgba(0,0,200,0.6);
     background: rgba(0,0,200,0.3);
     color: rgba(0,0,200,0.6);
     box-shadow: 1px 1px 2px rgba(0,0,200,0.4);
     border-radius: 10px;
     padding: 3px 10px;
     display: inline-block;
     cursor: pointer;
   }
```
we get this:

<img class="ui medium image" src="../images/player 1.png">

After adding some Javascript:
```
const para = document.querySelector('p');

para.addEventListener('click', updateName);

function updateName() {
  let name = prompt('Enter a new name');
  para.textContent = 'Player 1: ' + name;
}


```
we can now add your name by clicking on the button.

## My Experience with Javascript

My experience with learning Javascript has been enjoyable thus far although it was my first time learning in ICS 314. For my ICS 314 class, we had weekly WODs which are timed coding assignments done in class. I found the weekly WODs to be stressful because those assignments were a big part of my grade. So naturally it puts a lot of pressure on you especially when you are being timed. In the long run, I believe it will help me be a better coder as it helps with learning how to code efficiently and quickly.
