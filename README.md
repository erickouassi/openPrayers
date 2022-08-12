# {JSON} 🔥 Catholic Prayers and Devotions


## Create a fork of this repository
 *(A fork is a copy of a repository)*.
1. Fork the repository in your account [Click here](https://github.com/erickouassi/jsoncatholic/fork)
2. Clone your repository to make a local copy, URL will be `https://Your-Username-Here.github.io/jsoncatholic`

### Basic Prayers


### Pray the Rosary
- *Joyful Mysteries* are traditionally prayed on Mondays, Saturdays, and, during the season of Advent, on Sundays.
- *Sorrowful Mysteries* are traditionally prayed on Tuesdays, Fridays, and, during the season of Lent, on Sundays.
- *Glorious Mysteries* are traditionally prayed on Wednesdays and, outside the seasons of Advent and Lent, on Sundays.
- *Luminous Mysteries* are traditionally prayed on Thursdays.

The endpoints return data in json format:

Available year: 2022, 2023, 2024, 2025, and 2026.

` https://github.com/Your-Username-Here/jsoncatholic/blob/main/rosary/dailyrosary_:YYYY.json?raw=true`

Example : (Year format: YYYY)

[.../dailyrosary_2022.json?raw=true](https://raw.githubusercontent.com/erickouassi/jsoncatholic/main/rosary/dailyrosary_2022.json)

Result:
![This is an image](https://github.com/erickouassi/jsoncatholic/blob/main/year_json1.png?raw=true)

### Other Resources
- The saints `Coming soon!`

- The Stations of the Cross `Coming soon!`

- The verse of the day `Coming soon!`


## Endpoints
-`Your-Username-Here` will replace my-username: `erickoussi`-

To get direct link of `.json` file as a Read-Only API, you add `?raw=true`.

The endpoints return data in json format:
[.../rosary-day.json?raw=true](https://raw.githubusercontent.com/erickouassi/jsoncatholic/main/rosary/rosary_day.json)

` https://github.com/Your-Username-Here/jsoncatholic/blob/main/rosary/rosary_day.json?raw=true`

Result

`[
   {
      "nday":"1",
      "day":"Saturday",
      "mystery":"Joyful",
      "url":"saturday.html",
      "season":"Advent",
      "currentdate":"January 1, 2022",
      "mp3Link":"audio-rosary-joyful-mysteries.mp3"
   },
   {
      "nday":"2",
      "day":"Sunday",
      "mystery":"Joyful",
      "url":"advent.html",
      "season":"Advent",
      "currentdate":"January 2, 2022",
      "mp3Link":"audio-rosary-joyful-mysteries.mp3"
   },
   {
      "nday":"3",
      "day":"Monday",
      "mystery":"Joyful ",
      "url":"monday.html",
      "season":"Advent",
      "currentdate":"January 3, 2022",
      "mp3Link":"audio-rosary-joyful-mysteries.mp3"
   },
   {
      "nday":"4",
      "day":"Tuesday",
      "mystery":"Sorrowful ",
      "url":"tuesday.html",
      "season":"Advent",
      "currentdate":"January 4, 2022",
      "mp3Link":"audio-rosary-sorrowful-mysteries.mp3"
   },
   {
      "nday":"5",
      "day":"Wednesday",
      "mystery":"Glorious ",
      "url":"wednesday.html",
      "season":"Advent",
      "currentdate":"January 5, 2022",
      "mp3Link":"audio-rosary-glorious-mysteries.mp3"
   },
   {
      "nday":"6",
      "day":"Thursday",
      "mystery":"Luminous ",
      "url":"thursday.html",
      "season":"Advent",
      "currentdate":"January 6, 2022",
      "mp3Link":"audio-rosary-luminous-mysteries.mp3"
   },
   {
      "nday":"7",
      "day":"Friday",
      "mystery":"Sorrowful",
      "url":"friday.html",
      "season":"Advent",
      "currentdate":"January 7, 2022",
      "mp3Link":"audio-rosary-sorrowful-mysteries.mp3"
   }
   ]`

## Image
To get the direct link of an image, you add `?raw=true` 

`https://github.com/Your-Username-Here/jsoncatholic/blob/main/jesus-cross.jpg?raw=true`

## Audio
To get direct link of an audio, you add `?raw=true` 

`https://github.com/Your-Username-Here/jsoncatholic/blob/main/Apostles-Creed.mp4?raw=true`


**Full Tutorial blog post:** *coming soon!*

**If you have questions:**  [erickouassi.com/contact](https://erickouassi.com/contact.html)

I am primarily maintaining this repository for my own use cases. If you want any help setting your rosary web app for yourself, group or church, I’d love to help! [contact me here](https://erickouassi.com/contact.html).

