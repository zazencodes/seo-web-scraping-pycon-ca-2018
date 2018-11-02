# Python for SEO: Web Scraping

In this workshop, I want to show off the open-source tools we (at ![Ayima](https://www.ayima.com/)) leverage from Python’s ecosystem, and present them in a guided format.

 - We’ll first look at the basics of web requests with the requests library and show simple HTML parsing with BeautifulSoup4.
 - Then we’ll get into some more advanced details of each, including request sessions, passing cookies, custom user agents and more detailed HTML parsing techniques.
 - Finally we’ll conclude by showing how selenium can be used to render JavaScript when making requests.

### Dependencies

 - python (ideally 3.6+)
 - requests
 - beautifulsoup4
 - pandas
 - selenium

### No Internet Connection?

Most of the tutorial can still be completed without an internet connection.

1. Start a local server from `backup-html` folder:   

```
cd backup-html
python -m http.server
```

2. Replace all URLs with the equivalent local files:   

e.g.
```
https://2018.pycon.ca -> http://localhost:8000/2018.pycon.ca.html
```

