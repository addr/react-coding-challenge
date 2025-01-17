# React Coding Challenge

> Welcome to the React Coding Challenge!

## Overview

To complete this challenge, you will need to write a simple [React](https://facebook.github.io/react/) based web app.

The purpose of this challenge is to assess your **skills and approach to composing a simple web app** given a mockup and an API feed.

This challenge is expected to take about 20-30 minutes.

## The Challenge

It's pretty simple. Using the screen below as a reference, build a basic React app that fetches the first page of results from the open TVMaze API and displays the show thumbnail and title. No styling is required, but if you are comfortable using a component library like Material UI, feel free to use it.

API: http://api.tvmaze.com/shows

![TV Series Mockup](./screens/2-series.jpg)

Sample response:

```
[
  {
    "id": 1,
    "url": "http://www.tvmaze.com/shows/1/under-the-dome",
    "name": "Under the Dome",
    "type": "Scripted",
    "language": "English",
    "genres": ["Drama", "Science-Fiction", "Thriller"],
    "status": "Ended",
    "runtime": 60,
    "premiered": "2013-06-24",
    "officialSite": "http://www.cbs.com/shows/under-the-dome/",
    "schedule": { "time": "22:00", "days": ["Thursday"] },
    "rating": { "average": 6.5 },
    "weight": 92,
    "network": {
      "id": 2,
      "name": "CBS",
      "country": {
        "name": "United States",
        "code": "US",
        "timezone": "America/New_York"
      }
    },
    "webChannel": null,
    "externals": { "tvrage": 25988, "thetvdb": 264492, "imdb": "tt1553656" },
    "image": {
      "medium": "http://static.tvmaze.com/uploads/images/medium_portrait/81/202627.jpg",
      "original": "http://static.tvmaze.com/uploads/images/original_untouched/81/202627.jpg"
    },
    "summary": "<p><b>Under the Dome</b> is the story of a small town that is suddenly and inexplicably sealed off from the rest of the world by an enormous transparent dome. The town's inhabitants must deal with surviving the post-apocalyptic conditions while searching for answers about the dome, where it came from and if and when it will go away.</p>",
    "updated": 1562326291,
    "_links": {
      "self": { "href": "http://api.tvmaze.com/shows/1" },
      "previousepisode": { "href": "http://api.tvmaze.com/episodes/185054" }
    }
  },
  ...
]
```
