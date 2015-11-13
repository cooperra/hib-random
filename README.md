# hib-random
A bookmarklet to help you choose a random game from your Humble Bundle library

Just save the following link into your bookmarks bar.

    javascript:(function () {var e = _.sample(document.getElementsByClassName("subproduct-selector"));e.scrollIntoView();e.click();})()

Then, go to https://www.humblebundle.com/home/library and log-in. 

Click the bookmarklet to select a random game from your library.
