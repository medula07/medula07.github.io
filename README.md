### Project Aims:

The aim of this project was to Design a front-end for Google Search, Google Image Search, and Google Advanced Search., using the following technologies:

* **HTML**
* **CSS**
* **SASS / SCSS**


### Project Requirements:

* Your website should have at least three pages: one for regular Google Search (which must be called index.html), one for Google Image Search, and one for Google Advanced Search.
* On the Google Search page, there should be links in the upper-right of the page to go to Image Search or Advanced Search. On each of the other two pages, there should be a link in the upper-right to go back to Google Search.
* On the Google Search page, the user should be able to type in a query, click “Google Search”, and be taken to the Google search results for that page.
* Like Google’s own, your search bar should be centered with rounded corners. The search button should also be centered, and should be beneath the search bar.
* On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page.
* On the Google Advanced Search page, the user should be able to provide input for the following four fields (taken from Google’s own advanced search options)
   * Find pages with… “all these words:”
   * Find pages with… “this exact word or phrase:”
   * Find pages with… “any of these words:”
* Find pages with… “none of these words:”
* Like Google’s own Advanced Search page, the four options should be stacked vertically, and all of the text fields should be left aligned.
   * Consistent with Google’s own CSS, the “Advanced Search” button should be blue with white text.
   * When the “Advanced Search” button is clicked, the user should be taken to the search results page for their given query.
* Add an “I’m Feeling Lucky” button to the main Google Search page. Consistent with Google’s own behavior, clicking this link should take users directly to the first Google search result for the query, bypassing the normal results page.
   * You may encounter a redirect notice when using the “I’m Feeling Lucky” button. Not to worry! This is an expected consequence of a security feature implemented by Google.
* The CSS you write should resemble Google’s own aesthetics.


### Project Writeup:

This project is a starting point for my cs50w projects which I hope to continually add with additional content/projects etc. It has been created and styled using several Bootstrap components, as well as a Sass .scss stylesheet with some custom styles. Most pages use bootstrap navbar, jumbotron and footer components, as well as the bootstrap responsive grid system and cards to layout links to other sections of the website etc.

* index.html - homepage for the website, containing links to the rest of the site as well as links tom my GitHub and LinkedIn pages.
* about.html - a brief bio page with links to info about my cats.
* louis.html and boo.html - fun profiles for my two cats, including photos, lists of their favourite things and a nickname generator written in jQuery.
* projects.html - a mock-up for a page that will in the future have links to various projects I have built, displayed using bootstrap cards.
* blog.html - similar to projects.html, this is a mockup for a page that will have links to blog posts, and currently has a single blog post accessible.
* blog-n-queens.html - the start of a blog post about the N-Queens puzzle, which contains a table as well as images. An @media query in the main.scss stylesheet helps to resize the images here on smaller screens.

* main.scss - SCSS style sheet using Sass variable to handle the main color scheme as well as nesting and inheritance where appropriate. This is converted to the main.css stylesheet by Sass, which is referenced by the website.

* templates folder - contains a blog template for writing future blog posts.
* assets folder - contains image assets for various pages on the site.




