# MyReads Project

To run MyReads:
    npm install
    npm start

This is MyReads App developed by Juan Murga. It does the basic functionality required for the Udacity project.
    *Retrieve my books from BooksAPI and then arrange them on three shelves (Reading, To Read, Finished Books). These books are displayed following the fundamental concepts of React, reusing code making functional components and class components
    * Every time the user refreshes the App, it can maintain her state updating the database on BooksAPI using the method update()
    * Added basic routing for the search page and another route for view dynamically the description of books on a new page.
    * The search page can show the books in the database by looking for the SEARCH_TERMS. These books can be moved to my shelves and automatically save their positions for future uses. You can click on these books to view their data on a new page too
    *In AddBook.js we used debounce method to get the desirable behavior: When there is no input or we look for a invalid Term, the app should clean the view.

## What You're Getting
```bash
├── README.md - This file.
├── SEARCH_TERMS.md # The whitelisted short collection of available search terms for you to use with your app.
├── package.json # npm package manager file. It's unlikely that you'll need to modify this.
├── public
│   ├── favicon.ico # React Icon, You may change if you wish.
│   └── index.html # DO NOT MODIFY
└── src
    ├── App.css # Styles for your app. Feel free to customize this as you desire.
    ├── App.css # Styles for your app. Feel free to customize this as you desire.
    ├── Book.js # This is the
    ├── App.test.js # Used for testing. Provided with Create React App. Testing is encouraged, but not required.
    ├── BooksAPI.js # A JavaScript API for the provided Udacity backend. Instructions for the methods are below.
    ├── icons # Helpful images for your app. Use at your discretion.
    │   ├── add.svg
    │   ├── arrow-back.svg
    │   └── arrow-drop-down.svg
    ├── index.css # Global styles. You probably won't need to change anything here.
    └── index.js # You should not need to modify this file. It is used for DOM rendering only.
```



