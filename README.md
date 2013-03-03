nhldotcom-crawler-app
=====================

Web-crawling hello world. What it does:

1. Goes to http://www.nhl.com/ice/playersearch.htm and gets the ABC links to lists of players
2. Takes every ABC link, it retrieves the list of player pages URLs
3. Takes every player URL and retrieves player's name
4. Retrieved names are printed

Technically, it uses
* [jsoup][] to retrieve web pages and extract required data
* Java's standard `ThreadPoolExecutor` to process multiple tasks simultaneously

[jsoup]: http://jsoup.org/

