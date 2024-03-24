# Omnifood-Project

#### [Click here for live site](https://wills-omnifood-project.netlify.app/)

## Summary

The purpose of this project was to familiarise myself with HTML5, CSS3,, and some JavaScript. Part of this practice included building the architecture of the site using CSS Grid and Flexbox, depending on which section fitted the criteria.

## About Omnifood

The purpose of the website itself is to prioritise well-being by promoting healthy eating habits. Therefore, by preparing and delivering freshly prepared meals to selected cities via an affordable monthly subscription service, users will recieve one or two meals per days on affordable subscription plans, making healthy eating convenient and accessible.

## Code

1. HTML5
2. CSS3
3. JavaScript

## Visuals

![](Omnifood-Project/img/omnifood-versions.png)


<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="img/favicon.png" alt="Project logo"></a>
</p>

<h3 align="center">Natours Project</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Exciting tours for adventurous people
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

The purpose of this project was to become familiar and comfortable using SASS to compile and organise CSS.

It also helped me understand more advanced CSS techniques such as animation, how to scale or rotate images using the transform property, as well as the pre-requisites needed to ensure websites are responsive, browser compatible, and accessible.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

You will need to have [Nodejs](https://nodejs.org/en/) in your system.

Check the documentation to install it on your system.

### Installing

<img width=1080 height=300 src="screenshots/screenshot-1.PNG" alt="Project logo"></a>

Once Node Js is installed, you can see all necessary scripts in the package.json file.

```

"scripts": {
    "watch:sass": "node-sass sass/main.scss css/style.css -w",
    "devserver": "live-server",
    "start": "npm-run-all --parallel devserver watch:sass",
    "compile:sass": "node-sass sass/main.scss css/style.comp.css",
    "concat:css": "concat -o css/style.concat.css css/icon-font.css css/style.comp.css",
    "prefix:css": "postcss --use autoprefixer -b 'last 10 versions' css/style.concat.css -o css/style.prefix.css",
    "compress:css": "node-sass css/style.prefix.css css/style.css --output-style compressed",
    "build:css": "npm-run-all compile:sass concat:css prefix:css compress:css"
  },

package.json

```

## 🎈 Usage <a name="usage"></a>

You can make changes in the components inside the sass folder.
Run **npm watch:sass** to see in the browser all the changes that you do in the page.

## ⛏️ Built Using <a name = "built_using"></a>

- [HTML] - Markup Language
- [CSS] - Stylesheets
- [SASS](https://sass-lang.com/) - CSS Preprocessor
- [Node.js](https://sass-lang.com/) - CSS Preprocessor

## ✍️ Authors <a name = "authors"></a>

- [@fernandocutire](https://github.com/willh89) - Build by
- [@jonasschmedtmann](https://github.com/jonasschmedtmann) - Idea & Initial Work

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- CSS Udemy Jonas Course
- [Advanced CSS Course](https://github.com/jonasschmedtmann)
