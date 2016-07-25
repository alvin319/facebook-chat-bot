# Usage
* [`color`](#color)
* [`help`](#help)
* [`meme`](#meme)
* ['stock'](#stock)
* [`weather`](#weather)

--------------------------------------------------
<a name="color"/>

## @color

This trigger can set the color of a chat thread.

__Usage__

`@color <RGB Hex>`

__Arguments__

* `RGB Hex`: A six digit hexadecimal number representing the target color. Both upper and lower cases are supported.

__Example__

>`@color #0084FF`

*This will set the chat thread color to Facebook messenger blue.*

--------------------------------------------------
<a name="help"/>
## @help

This lists available commands and lists information about each one.

__Usage__

`@help`

`@help [command]`

__Arguements__

* `command` (optional): Name of one of available commands

__Examples__

>`@help`

>`@help weather`

--------------------------------------------------
<a name="meme"/>

## @meme

This sends the thread a [rickroll YouTube link](https://www.youtube.com/watch?v=dQw4w9WgXcQ).

[![Never Gonna Give You Up](http://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](http://www.youtube.com/watch?v=dQw4w9WgXcQ)

__Usage__

`@meme`

__Arguments__

None

__Example__

>`@meme`

>https://www.youtube.com/watch?v=dQw4w9WgXcQ


*Never gonna give you up, never gonna let you down. Never gonna run around and desert you. Never gonna make you cry, never gonna say goodbye. Never gonna tell a lie and hurt you…*

--------------------------------------------------
<a name="stock"/>

## @stock

This retrieves stock data for a given stock.

__Usage__

`@stock <symbol>`

__Arguments__

* 'symbol': Stock symbol. (Currently only supporting US stocks)

__Example__

>`@stock GOOGL`

>Alphabet Inc. (GOOGL) last traded at $757.52 on Mon Jul 25 2016 00:00:00 GMT-0700 (Pacific Daylight Time).
Volume: 1073278 | P/E Ratio: 30.82
Change: $-1.76 | % Change: -0.23%

--------------------------------------------------
<a name="weather"/>

## @weather

This posts weather information of a given location.

__Usage__

`@weather <zipcode | location name>`

__Arguments__

* `zipcode`: A five digit US zipcode.
* `location name`: A letter and space only location name, or city name and state separated by a comma and a space.

__Example__

>`@weather 94158`

>It is currently 63°F and Mostly Sunny in San Francisco, CA.\
It feels like 63°F outside. Relative humidity is 75%.\
Here's your 5-day forecast:\
2016-07-21 | Low: 53, High: 69. Precipitation: %\
2016-07-22 | Low: 56, High: 70. Precipitation: 0%\
2016-07-23 | Low: 55, High: 72. Precipitation: 0%\
2016-07-24 | Low: 57, High: 73. Precipitation: 0%\
2016-07-25 | Low: 56, High: 71. Precipitation: 40%

>`@weather New York, NY`

>It is currently 89°F and Mostly Sunny in New York, NY.\
It feels like 94°F outside. Relative humidity is 55%.\
Here's your 5-day forecast:\
2016-07-21 | Low: 74, High: 89. Precipitation: %\
2016-07-22 | Low: 82, High: 90. Precipitation: 10%\
2016-07-23 | Low: 79, High: 98. Precipitation: 10%\
2016-07-24 | Low: 82, High: 91. Precipitation: 0%\
2016-07-25 | Low: 82, High: 94. Precipitation: 60%

