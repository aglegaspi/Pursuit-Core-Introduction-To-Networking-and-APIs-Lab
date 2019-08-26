# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
``` 
the status code means the server understood the request and is able to fulfull it". Everything is good so there's no need to troubleshoot this.
source: https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/200

```
1. 301
```
the status code means the resource has moved elsewhere. I will provide a redirect link to the new link.
source: https://airbrake.io/blog/http-errors/301-moved-permanently
```
1. 400
```
the 400 code means that the DNS records are outdated. to resolve this issue I would provide a updated link, a closest match to the query, or a link to the landing page.
source: https://www.lifewire.com/how-to-fix-a-400-bad-request-error-2617988
```
1. 401
```
the 401 error means you can't access the page w/o logging with your username & password. to solve this i'd provide a sign in link, or redirect the user to a sign page also displaying the error from the link aiming to be accessed on first request.
source: https://www.lifewire.com/401-unauthorized-error-what-it-is-and-how-to-fix-it-2622934
```
1. 403
```
the 403 error message is a forbidden access message. To solve this problem I'd check if the root directory/current directory has it's 'index' file, if not I'll create it. I'll also check if the permissions are correct.
source: https://mediatemple.net/community/products/dv/204644980/why-am-i-seeing-a-403-forbidden-error-message
```
1. 404
```
uri: https://api.thecatapi.com/v1/images/search/dog
the status code means that the client entered information that is not recognizable to the server.
source: https://whatis.techtarget.com/definition/404-status-code
```
1. 418
```
the 418 error joke was a April Fools joke from 1998. It refers to an error a coffe displays. To fix this I would buy a new coffee pot.
source: https://httpstatuses.com/418
```
1. 500
```
The 500 status code means that server cannot process the request for an unknown reason. To solve this I would check for server misconfiguration, ie. corupt .htaccess file, or missing packages, i.e trying process PHP file without PHP installed properly.
source: https://www.digitalocean.com/community/tutorials/how-to-troubleshoot-common-http-error-codes
```


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
```
uri: https://catfact.ninja/fact
json: {
"fact": "The cat appears to be the only domestic companion animal not mentioned in the Bible.",
"length": 84
}
```
1. A list of 150 random users in English.
```
uri: https://randomuser.me/api/?results=150&nat=us
json: (just visit link cause issa lot of data)
```
1. The current stock price of Microsoft. (IEX API)
```
uri: https://api.worldtradingdata.com/api/v1/stock?symbol=AAPL,MSFT,HSBA.L&api_token=demo
json: {
"message": "This request is for demonstration purposes only. If you wish to use our API, please sign up and get your personal API token for free.",
"symbols_requested": 3,
"symbols_returned": 3,
"data": [
{
"symbol": "MSFT",
"name": "Microsoft Corporation",
"currency": "USD",
"price": "134.97",
"price_open": "134.99",
"day_high": "135.45",
"day_low": "133.91",
"52_week_high": "141.68",
"52_week_low": "93.96",
"day_change": "1.58",
"change_pct": "1.18",
"close_yesterday": "133.39",
"market_cap": "1030551306240",
"volume": "12739034",
"volume_avg": "23691916",
"shares": "7662819840",
"stock_exchange_long": "NASDAQ Stock Exchange",
"stock_exchange_short": "NASDAQ",
"timezone": "EDT",
"timezone_name": "America/New_York",
"gmt_offset": "-14400",
"last_trade_time": "2019-08-26 14:58:51"
}
]
}
```
1. The 5 year history of Apple stock prices (IEX API)
```

```
1. All the Swift language repos on Github with Pursuit in their name
```
uri: https://api.github.com/search/repositories?q=pursuit-core-ios&language=Swift

```
1. A list of all Pokemon
```
uri: https://pokeapi.co/api/v2/pokemon/?limit=964
```
1. A list of all items in Fortnite
```
uri: https://fortnite-public-api.theapinetwork.com/prod09/store/get
```
1. A list of all Game of Thrones Episodes.
```
uri: https://api.got.show/api/map/episodes
```
1. A list of all songs with "Love" in the title.
```
uri: 
```
1. All information about Petyr Baelish from the Game of Thrones books
```
uri: https://api.got.show/api/book/characters/Petyr%20Baelish
```
1. All the movies Leonardo Dicaprio has acted in
```

```
