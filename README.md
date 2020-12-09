# CompRobo Final Project

Check out our [website here!](https://amfry.github.io/sign_recognition/index.html)

## Modifying the Website

The website's source code exists in the [docs/](https://github.com/amfry/sign_recognition/tree/main/docs) directory. To modify any of the existing pages, edit the markdown file associated with the page, and the new content will load on the webiste. Put any images you would like to add to the [images](https://github.com/amfry/sign_recognition/tree/main/docs/images) directory to link them relative to the page and to maintain high-quality copies of the images. 

To add a new page, add a new markdown file to the [docs/](https://github.com/amfry/sign_recognition/tree/main/docs) directory. with the following header (populate TITLE_OF_PAGE with the actual title of the page). 
```
---
layout: "default"
title: TITLE_OF_PAGE
---
```
Then, add a link to your page in the navigation bar located in the [default layout page](https://github.com/amfry/sign_recognition/tree/main/docs/_layouts) after the comment flagged for adding navbar items. Add the item with the following syntax, with MARKDOWN_FILENAME replaced with the filename of the markdown file (without the .MD extension) and TITLE_OF_PAGE replaced with the navigation bar item title.

```[html]
<! –– FLAG: Add navbar items here -->                                                   
<a href="{{site.baseurl}}/MARKDOWN_FILENAME.html"> TITLE_OF_PAGE</a> <br>

```

