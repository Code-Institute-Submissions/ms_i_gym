# Website for a fictitious gym

## Table of Contents

<!--ts-->
- [Table of contents](#Table-of-Contents)
- [About](#About)
  - [Functionality/UX](#Functionality-and-UX)
- [Technologies](#Technologies)
  - [Languages/Frameworks/Libraries/Tools](#Languages-Frameworks-Libraries-Tools)
  - [Other Resources](#Other-Resources)
- [Testing](#Testing)
  - [Tools and Methods Used for Testing](#Tools-and-Methods-Used-for-Testing)
  - [Additional Notes](#Additional-Notes)
  [Futures](#Futures)
  - [Potential Enhancements](#Potential-Enhancements)
- [Deployment](#Deployment)
- [Credits](#Credits)
  - [Content](#Content)
  - [Acknowledgements](#Acknowledgements)
<!--te-->

## About

Milestone Project One / User Centric Development / Code Institute

This is a web site for a fictitious gym fulfilling the requirements for Milestone I project. The premise of the site is to put the gym in the best light
possible and motivate the visitor of the site to fill out to the form which -- in a live envir

#### Functionality and UX

There site is a one page site where the menu takes you to different sections of the page with the navbar navigating to each of the sections. The sections are:

- [Home] which takes you to the top of the page and consists of a navbar and carousel images. There are 3 carousel images and each has a cal
- [Facility] which takes you to the section under the carousel. This describes 

## Technologies

#### Languages Frameworks Libraries Tools

- [HTML5](https://www.w3.org/TR/html5/ "HTML5 Official Site")

- [CSS3](https://www.w3.org/Style/CSS/ "Cascading Style Sheets Official Site")

- [jQuery](http://jquery.com/ "jQuery Official Site")

- [dc](https://dc-js.github.io/dc.js/ "Dimensional Charting JavaScript Library")

- [d3](https://d3js.org/ "Data-Driven Documents")
 
- [crossfilter.js](https://github.com/crossfilter/crossfilter/ "Grouping and Filtering Data")

- [queue](https://github.com/d3/d3-queue/ "Queueing and Deferring Asynchronous Tasks")

- [Chart.js](https://www.chartjs.org/ "JavaScript Charting")

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/ "JavaScript Official Site")

- [Bootstrap - v4.1.1](https://getbootstrap.com/docs/4.1/getting-started/introduction/ "Bootstrap Official Site")

- [Font Awesome - v5.0.13](https://fontawesome.com/ "Fontawesome Official Site")

- [Python](https://www.python.org/ "Python Official Site")
Used for running a script/spider to scrape the PGA Tour website

- [Scrapy](https://scrapy.org/ "Scrapy - Web Scraping")
Used for scraping the pgatour.com site for the data used

#### Other Resources

- https://getbootstrap.com/
- https://www.w3schools.com/
- https://stackoverflow.com/
- https://slack.com/

#### About the Charts

One might ask, "if you are using dc and d3, why are you also using Chart.js?" Great question. As there was very little grouping, summing and aggregating required, I was struggling with
crossfilter and dc to chart the data correctly. In essence, each record within my JSON file is indeed the data that is charted; no aggregating required. Chart.js is perfect for this more
simplistic chart creation. I am using the aforemention libraries for some grouping but that is it. All charting is done by Chart.js.

And a final note about this. I actually find Chart.js easier to work with that dc and d3.

#### Potential Enhancements

There is immense potential improvement to this application. Some that come to mind are:

- Dynamically adding and removing statistics for different years and displaying in the same chart. That woud be very cool.
- Associating the players with the finishing positions (1st, 10th, etc.)
- Adding putting statistical data. There is putting in the data.json file. However, I was already behind schedule, so I didn't put it on the website.

## Testing

#### Tools and Methods Used for Testing

- [HTML Validation](https://validator.w3.org/ "W3C Markup Validation Service")
- [CSS Validation](http://jigsaw.w3.org/css-validator/ "CSS Validation Service")
- [JavaScript Linting](https://eslint.org/ "JavaScript Linting Service")
- [JavaScript Data Structure Testing](https://jsbin.com/ "JSFiddle-Like Service")
- Chrome Developer Tools

#### Additional Notes

I used a lot of visual comparison of the original data set with what was displayed in the charts. In addition, I literally stepped over every line of JavaScript code via Chrome Developer Tools

## Deployment

- Used GitHub Pages to deploy the final version (https://mrbrown2207.github.io/mrbmsII/).

## Credits

#### Content

- All written content is bespoke and created by the code author (Michael Brown).
- Images used are royalty-free, downloaded from the web.

#### Acknowledgements

- Sipo Charles' for his readme.md file. I started with it as I liked the structure.
- Anonija Šimić for her help with some formatting issues I had and CSS guidance.....I love CSS Variables!
- Zach Golwitzer for his PGA Tour website scraping code. I started with it and modified it for my scraping purposes. https://github.com/zachgoll/pga-tour-stats.
