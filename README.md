# Project Overview

## Anime+

[Deployed Project](URL)

## Project Description

This project allows for users to search for anime. The project will append an image, title, and description of the anime show the user searches for while also displaying the current anime shows airing at the time.

## API and Data Sample

I am using the Jikan API which pulls data from MyAnimeList and gives data on anime and manga. [Jikan](https://jikan.docs.apiary.io/#)


```
{
    "request_hash": "request:search:b5021fb5569664933c0ddceeeda2cfdfbe5ad745",
    "request_cached": true,
    "request_cache_expiry": 184727,
    "results": [
        {
            "mal_id": 20,
            "url": "https://myanimelist.net/anime/20/Naruto",
            "image_url": "https://cdn.myanimelist.net/images/anime/13/17405.jpg?s=59241469eb470604a792add6fbe7cce6",
            "title": "Naruto",
            "airing": false,
            "synopsis": "Moments prior to Naruto Uzumaki's birth, a huge demon known as the Kyuubi, the Nine-Tailed Fox, attacked Konohagakure, the Hidden Leaf Village, and wreaked havoc. In order to put an end to the Kyuubi'...",
            "type": "TV",
            "episodes": 220,
            "score": 7.93,
            "start_date": "2002-10-03T00:00:00+00:00",
            "end_date": "2007-02-08T00:00:00+00:00",
            "members": 2082967,
            "rated": "PG-13"
        },
```

## Wireframes

![Wireframe](https://i.imgur.com/JouFioF.png)

### MVP/PostMVP

#### MVP 

- Allow user to search with a form input to find information about different anime 
- Render image, title, based on the search results 
- Have dynamic header image that showcases most popular anime at the time
- Styling with flexbox
- Media query for mobile


#### PostMVP  

- Display list of popular anime on the page that are clickable and bring user to information page
- Display upcoming anime that has been announced
- Display different genres
- Create image carousel in header that displays popular anime characters as well as most popular anime show at the moment
- Let user add anime to a "watch later" list
- Add description to anime that the user shows for on a different page
- Show currentlly airing anime

## Project Schedule

|  Day | Deliverable | Status
|---|---| ---|
|June 21| Prompt / Wireframes / Priority Matrix / Timeframes | Complete
|June 22| Project Approval / HTML Boilerplate / JS part of input form completed & appended items showing up | Complete
|June 23| Add current anime airing for the week / Style the page in CSS based on wireframe | Incomplete
|June 24| Initial Clickable Model / Additional CSS: hover effects,  animations / work on mobile UI  | Incomplete
|June 25| MVP | Incomplete
|June 28| Presentations | Incomplete

## Priority Matrix

![Priority Matrix](https://i.imgur.com/CQXfcIZ.png)

## Timeframes

| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Create functional form | H |2hrs| 0.5hrs |  |
| Format form information using CSS | H | 3hrs|  |  |
| Create currently airing anime section | H | 4hrs|  |  |
| Add top anime to header and format header section | H | 3hrs|  |  |
| Add hover effects for the images | L | 3hrs| |  |
| Go through all data I want to display for the anime | H | 2hrs| |  |
| query for mobile | H | 3hrs|  |  |
| Format general website (background, footer) | H | 3hrs|  |  |
| Testing out information taken from API (image sizes, kinds of information, search functionality) | H | 3hrs|  |  |
| Add image carousel | L | 5hrs|  |  |
| Add links at top of page that go to different sections | L | 1hrs|  |  |
| add go go back up top of the page button | L | 2hrs|  |  |
| create watch later list | L | 4hrs|  |  |
| Total |  | 38hrs|  |  |

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of and a brief description.  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  
