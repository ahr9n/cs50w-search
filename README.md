# Search
Project 0 for CS50’s Web Programming with Python and JavaScript.

## Overview
A front-end design for Google Search, Google Image Search, and Google Advanced Search.

## Specifications
The website meets the following requirements:
* Has at least three pages: one for regular Google Search (which is called index.html), one for Google Image Search, and one for Google Advanced Search.
  * On the Google Search page, there are links in the upper-right of the page to go to Image Search or Advanced Search. On each of the other two pages, there is a link in the upper-right to go back to Google Search.
* On the Google Search page, the user is able to type in a query, click “Google Search”, and is taken to the Google search results for that page.
  * Like Google’s own, the search bar is centered with rounded corners. The search button also is centered, and is beneath the search bar.
* On the Google Image Search page, the user is able to type in a query, click a search button, and is taken to the Google Image search results for that page.
* On the Google Advanced Search page, the user is able to provide input for the following four fields (taken from Google’s own advanced search options)
  * Find pages with… “all these words:”
  * Find pages with… “this exact word or phrase:”
  * Find pages with… “any of these words:”
  * Find pages with… “none of these words:”
* Like Google’s own Advanced Search page, the four options are stacked vertically, and all of the text fields are left aligned.
  * Consistent with Google’s own CSS, the “Advanced Search” button is blue with white text.
  * When the “Advanced Search” button is clicked, the user is taken to the search results page for their given query.
* Add an “I’m Feeling Lucky” button to the main Google Search page. Consistent with Google’s own behavior, clicking this link takes users directly to the first Google search result for the query, bypassing the normal results page.
  * I encountered a redirect notice when using the “I’m Feeling Lucky” button. But, no worries! This is an expected consequence of a security feature implemented by Google.
* The CSS I wrote resembles Google’s own aesthetics.

## Topics
Built with HTML, SaSS, BootStrap v5.1.3, and [JsAction Library](https://github.com/google/jsaction).
