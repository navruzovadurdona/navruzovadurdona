- 👋 Hi, I’m @navruzovadurdona
- 👀 I’m interested in various codes
- 🌱 I’m currently learning in ICT4GIRLS in Batken
- 💞️ I’m looking to collaborate on Epam
- 📫 How to reach me +996 (221)-02-80-64
  

<!---
navruzovadurdona/navruzovadurdona is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


# 👋 Привет! Я Дурдона

Junior Backend Developer | Python & Django 💻

## 🛠 Навыки
- Django, REST API, PostgreSQL
- HTML, CSS, JavaScript
- Git, GitHub

## 🌟 Проекты
- SmartRazzakov — информационный сайт
- Блог на Django/React

## 👩‍💻 My Coding Vibes


## 📫 Контакты
📍 Кыргызстан, Лейлек  
📧 navruzovadurdona@gmail.com
📱 +996 (221) 02-80-64

badge-maker

npm version npm license npm type definitions
Installation

npm install badge-maker

Usage
On the console

npm install -g badge-maker
badge build passed :brightgreen > mybadge.svg

As a library

With CommonJS in JavaScript,

const { makeBadge, ValidationError } = require('badge-maker')

With ESM or TypeScript,

import { makeBadge, ValidationError } from 'badge-maker'

const format = {
  label: 'build',
  message: 'passed',
  color: 'brightgreen',
}

const svg = makeBadge(format)
console.log(svg) // <svg...

try {
  makeBadge({})
} catch (e) {
  console.log(e) // ValidationError: Field `message` is required
}

Node version support

The latest version of badge-maker supports all currently maintained Node versions. See the Node Release Schedule.
Format

The format is the following:

{
  label: 'build',  // (Optional) Badge label
  message: 'passed',  // (Required) Badge message
  labelColor: '#555',  // (Optional) Label color
  color: '#4c1',  // (Optional) Message color
  logoBase64: 'data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI2NCIgaGVpZ2h0PSI2NCI+PHJlY3Qgd2lkdGg9IjY0IiBoZWlnaHQ9IjY0IiByeD0iOCIgZmlsbD0iI2IxY2U1NiIvPjxwYXRoIGQ9Ik04IDBoMjR2NjRIOGMtNC40MzIgMC04LTMuNTY4LTgtOFY4YzAtNC40MzIgMy41NjgtOCA4LTh6IiBmaWxsPSIjNWQ1ZDVkIi8+PC9zdmc+' // (Optional) Any custom logo can be passed in a URL parameter by base64 encoding
  links: ['https://example.com', 'https://example.com'], // (Optional) Links array of maximum two links

  // (Optional) One of: 'plastic', 'flat', 'flat-square', 'for-the-badge' or 'social'
  // Each offers a different visual design.
  style: 'flat',

  // (Optional) A string with only letters, numbers, -, and _. This can be used
  // to ensure every element id within the SVG is unique and prevent CSS
  // cross-contamination when the SVG badge is rendered inline in HTML pages.
  idSuffix: 'dd'
}

Colors

There are three ways to specify color and labelColor:

    One of the Shields named colors:

    – the default labelColor

    – the default color

    – the default color

    A three- or six-character hex color, optionally prefixed with #:

    etc.

    Any valid CSS color, e.g.

    rgb(...), rgba(...)
    hsl(...), hsla(...)
    etc.

Raster Formats
Conversion to raster formats is no longer directly supported. In javascript code, SVG badges can be converted to raster formats using a library like gm. On the console, the output of badge can be piped to a utility like imagemagick e.g: badge build passed :green | magick svg:- gif:-.



