# Code Refactor: Horiseon Social Solution Services

The objective of this exercise was to take existing code and to refactor it to meet the below client objectives:
* codebase follows accessibility standards
* site is optimized for search engines

The client also provided a list of criteria for acceptance of the refactored codebase:

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## Site Picture
![Image](site_image.png)

## Approach

For the express purposes of this exercise, adjustments were made to remain within the scope of the aforementioned objectives and acceptance criteria. The code will likely require additional refactoring to ensure consistency across different platforms / browser sizes and thus, detailed comments have been added throughout.

The code was first checked for functionality, then clarity, and finally accessibility.

From a functionality perspective, the main item to note was a "broken" navigation button which was pointing to a missing id and repaired as follows:

```
<!-- entered missing id tag to fix nav link -->
<section id="search-engine-optimization" class="search-engine-optimization">
```
From a clarity perspective, where possible, non-semantic html (e.g."div") was replaced with semantic html.  This was done to help provide clarity for both future coders and for SEO purposes.  Below are a few samples:

```
<!-- changed from "div" to "section"-->
<section id="online-reputation-management" class="online-reputation-management">

<!-- changed from "div" to "aside" -->
<aside class="benefits">
```
Additional clarity was addressed through and adjustment made to the title.

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link

* [See Live Site](https://cofchips.github.io/code_refractor/)


## Authors

* **CHRISTOPHER LEE** 

- [Link to Github](https://github.com/CofChips)
- [Link to LinkedIn](https://www.linkedin.com/in/christophernlee/)

## Acknowledgments

* [Link to w3 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

