# Personal Bio Page

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |
| Flexbox | [https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) |

## Description 

[Visit the Deployed Site](https://bhaskell7901.github.io/perosnal-bio/)

This is an example personal bio webpage to display top proejcts I'm working on.  In this project I created links in the header that moves the UI the section being clicked.  The site has a responsive page design that adjusts to differing viewport sizes using a media query and Flexbox.


## Table of Contents

[Usage](#usage)
[Learning Points](#learning-points)
[Author Info](#author-info)


## Usage 

Feel free to resize the webage and test the responsive design.

*Large screen*

![responsive design small screen view](https://github.com/bhaskell7901/perosnal-bio/blob/main/assets/images/responsive-page-large.jpg)

*Small screen*

![responsive design small screen view](https://github.com/bhaskell7901/perosnal-bio/blob/main/assets/images/responsive-page-small.jpg)



## Learning Points 

Throughout this project I learned a lot about CSS functionality and a lot about Flexbox and how usedful it is in responsive web design. I also leaned a lot about and what selectors are available in CSS.  Some the new examples for me were psedo classes which I used in this project to select the `first-child` in the Projects section to be able to set a differing image size for that child only.

Here is a snippet of the code used:
```CSS
.pj-card:first-child > a > img {
    object-fit: cover;
    border: 3px;
    padding: 20px;
    margin: 12px;
    height: 350px;
    max-width: 100%;
}

```


## Author Info


* [LinkedIn](https://www.linkedin.com/in/BrandonDHaskell)
* [Github](https://github.com/bhaskell7901)
