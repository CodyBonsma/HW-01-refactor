# HW-01-refactor

For this project, I have cleaned our marketing client's codebase so that it follows web accessibility standards.

## Front page screenshot 

![front page screenshot](./assets/images/screenshot.png)

## Motivation

A refactored codebase will help our client (and others) navigate the website's build and structure. This will also help the site to be optimized for search engines. 

## Refactor work

- CSS [consolidation of CSS](./assets/css/style.css)

In our client's CSS file (linked above), I have consolidated six different classes. This helps clean up the code and makes the reusable classes easier to identify.

Changes have also been made to some of the .header classes to reflect html <div> changes in html

example:
```
.benefit-brand,
.benefit-cost,
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
```

- HTML [html semantics](./index.html)

To help make the html more accessible, I have replaced generic <div> tags with semantic tags. This allows the viewer to easily identify the code and its structure on the webpage itself.

## Link to Horiseon 








