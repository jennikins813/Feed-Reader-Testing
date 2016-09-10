# Project Feed Reader Testing

In this project I was given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite.

## Getting Started

You can download this repo and open index.html in your browser.

You can also view the live demo [here](https://jennikins813.github.io/Feed-Reader-Testing/).


## How I completed this project

1. Took the JavaScript Testing [course](https://www.udacity.com/course/ud549)
2. [Required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
3. Explore the application's HTML (**./index.html**), CSS (**./css/style.css**) and JavaScript (**./js/app.js**) to gain an understanding of how it works.
4. Explore the Jasmine spec file in **./jasmine/spec/feedreader.js** and review the [Jasmine documentation](http://jasmine.github.io).
5. Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
6. Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
7. Wrote a test that ensures the menu element is hidden by default.
8. Wrote a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
9. Wrote a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
10. Wrote a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
11. No test is dependent on the results of another.
12. Callbacks used to ensure that feeds are loaded before they are tested.
13. Implement error handling for undefined variables and out-of-bound array access.
14. When complete - all of the tests passed.