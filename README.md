# Udacity Project 6: Feed Reader Testing

## About
========

Tests were added in 'jasmine/spec/feedreader.js'(comments will be included in the file) to test for functionality of the website:

- RSS feeds are defined in 'allFeeds' and are not empty.
- Each feed in 'allFeeds' has a defined and valid URL.
- Each feed has a defined and name.
- The menu is hidden by default (on page load).
- The nav. menu toggles visibility after clicking the menu icon.
- The first feed has at least one entry.
- The feed changes content after selecting a new feed.

## How to Run
=============

Download the file and open index.html it in your browser locally, and you will see a section below the page showing the test results.

To add or edit the feed sources, open 'js/app.js' and change the 'allFeeds' object.  Ensure that you have at least 2 feeds, or else the 'New Feed Selection' test will fail.