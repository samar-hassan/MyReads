# MyReads Project

In this application, the main page displays a list of "shelves" (i.e. categories), each of which contains a number of books. The three shelves are:

Currently Reading
Want to Read
Read

Each book has a control that lets you select the shelf for that book. When you select a different shelf, the book moves there.

![image](https://user-images.githubusercontent.com/17203612/173902839-639f0ae9-9ff4-41dd-baea-48728dfe7f9c.png)

The main page also has a link to /search, a search page that allows you to find books to add to your library.

The search page has a text input that may be used to find books. As the value of the text input changes, the books that match that query are displayed on the page, along with a control that lets you add the book to your library. 

![image](https://user-images.githubusercontent.com/17203612/173903177-a8fe47b9-3fb7-4482-b204-94a298c299c1.png)

The search page also has a link to / (the root URL), which leads back to the main page.

When you navigate back to the main page from the search page, you can instantly see all of the selections you made on the search page in your library.

* install all project dependencies with `npm install`
* start the development server with `npm start`


## Important
The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](SEARCH_TERMS.md). That list of terms are the _only_ terms that will work with the backend, so don't be surprised if your searches for Basket Weaving or Bubble Wrap don't come back with any results.
