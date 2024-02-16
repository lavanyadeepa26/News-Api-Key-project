# News-Api-Key-project
The project provides a user-friendly interface for accessing news articles based on user preferences, enhancing the browsing experience with dynamic content fetched from the News API.

# User Interface (HTML /CSS)
* The project includes an HTML file **(index.html)** that provides the structure of the webpage.
* It features a navigation bar **(nav)** with a logo and a search container.
* Within the search container, there's an input field **(search-input)** for users to enter their search queries and a search button **(search-button)** to trigger the search.

# Styling (CSS)
* The styling is defined in a separate CSS file **(style.css)**, which enhances the visual appeal and layout of the webpage.
* It includes styling for **the navigation bar, search container, input field, button, and blog cards** (where the news articles are displayed).

# JavaScript Functionality (script.js)
* The JavaScript code handles the dynamic functionality of the webpage.
* It defines constants to store the API key, references to HTML elements, and functions for fetching and displaying news articles.
* There are two main functions for fetching news:
     * **fetchRandomNews()**: Fetches random news articles from the News API when the page loads.
     * **fetchNewsQuery(query)**: Fetches news articles based on the user-entered search query.
* The **displayBlogs(articles)** function dynamically creates HTML elements to display each news article as a blog card on the webpage.
*** Event listeners** are added to the search button to trigger the news search when clicked, and to the blog cards to open the full article in a new tab when clicked.
  
# Integration with News API:
* The project integrates with the News API to fetch news articles based on specific criteria.
* It constructs API requests with the appropriate endpoints, including the API key and any query parameters such as country or search query.
* The fetched data (news articles) are processed and displayed dynamically on the webpage.
