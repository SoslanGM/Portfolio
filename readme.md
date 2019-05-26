# Soslan Guchmazov

## Education:
- 2005-2009, **Moscow IT Lyceum 1533**, programming.
- 2009-2011, **Bauman's Moscow State Technical University**, programming.

## Last places of employment:
- Sep 2015 - Jan 2016, **Gameboloid**, "Woodland Quest", match-3 game.
- Mar 2016 - Dec 2018, **Russian Post**, operator

## Short description of last few years:
   After leaving university early due to complications in family, I leveraged my general knowledge and skills
at using computers to get various data entry and simple helpdesk jobs, lacking confidence to pursue
programming career at that point in time.

   Aug '15, while I was looking for job opportunities closer to my vocation, a university friend told me
he had a junior spot in a team he led at the time, and offered it to me, on a condition of completing a project
in the Unity game engine.
   After a couple weeks of training I have written a 3D variant of the classic "Snake" game, and it was enough.
   During my time there I've integrated an ad-serving library Appodeal, processing some events it couldn't
at the time; added some of UI features like text lines popping upon combos and timers; some of the
character animations.
   Shortly before the NY of '16 we started hearing rumours of financial trouble brewing in the company that
owned the team, and we were soon disbanded.
 
   Near the end of '18, having built a little warchest to sustain myself while I concentrated on self-education,
I left Post Office to try and make a sharp career turn into programming, again. I've spent a few months learning
Python and SQL on [DataCamp](https://www.datacamp.com/profile/soslangm) and have completed a few personal
projects, listed below.
   Next, aiming to build a more diverse and interesting portfolio, I spent another couple months honing my
skills in C and Vulkan Graphics API, having been programming in both on and off for a few years, vying to,
this time, get further into the woods than lands of humble triangles, and to a level beyond mere tutorials.


## Portfolio entries

### C & Vulkan projects
   These entries find Vulkan SDK folders and dynamically extract every function needed to work from its library and
the viewer requires a couple of API extensions that should be present on most GPUs currently in use(mine certainly isn't new!).

   Footage of my every Vk-C project was produced by **ffmpeg** stitching together screenshots captured from
within the applications; presented on this page are 24fps gifs, clickable and leading to short Youtube 60fps videos.
   This feature, while being developed in the "Triangle" entry, is on full display 
and accessible only in the "Viewer" project.

   The entries make use of the excellent single-header [STB libraries](https://github.com/nothings/stb) written by [Sean Barrett](https://github.com/nothings/) for rendering of text, reading and writing of images.


#### [Asynchronious Vulkan-based thumbnail-generating image viewer.](https://github.com/SoslanGM/Vulkan_AsyncFolderImageViewer)
   This application obtains a list of images of most commonly used formats(.jpg, .bmp and .png) in a folder specified
in source.cpp, using Win32 functions. It then, using multiple threads, loads and renders the images as smaller-sized
thumbnails, allowing you to scroll through your folder.
   It can handle folders worth of several hundred images(potentially up to 4096 images, utilizing special extensions),
with maximum size of up to 25 megabytes.
<p align="center"><a href="http://www.youtube.com/watch?v=EagvXuvbbQw"><img width="720" height="405" src="viewer.gif"></a></p>

#### ["A Flappy Fish".](https://github.com/SoslanGM/Vulkan_FlappyFish)
   This is a simple recreation of the popular "Flappy Bird" game, with the assets from **"Super Mario Bros."**(© Nintendo)
<p align="center"><a href="http://www.youtube.com/watch?v=fW6_d3bbo3c"><img width="720" height="405" src="flappy.gif"></a></p>

#### ["The Spinning Triangle."](https://github.com/SoslanGM/Vulkan_ASpinningTriangle)
   This is the ["Black Triangle"](http://rampantgames.com/blog/?p=7745) of my recent Vulkan trip, and it took me a bit
to remember how to even output a triangle. I decided to make this the last one, and cooked it to perfection, making it
the basis of the framework in which I wrote the following two entries; trying out for the first time a memory management
scheme of a humble, yet effective, memory pool into which all further geometry writes are written; and convenient text
overlay system allowing for convenient layout, for debugging purposes and others.
<p align="center"><a href="http://www.youtube.com/watch?v=o-HaOMZ5nZ8"><img width="720" height="405" src="triangle.gif"></a></p>



### Python projects
   These entries are written in Jupyter Notebook.
   
#### [Business analytics: Lending Club open dataset, 2007-2011](analytics.html)
   Armed with **Pandas**, **Numpy**, **Pyplot** and **Seaborn**, I look into the activity of a lending company, to see if I could reason a little bit about how the business is across America and in individual states, and whether an imaginary reallocation of offices is would make business sense, constructing a **PostgreSQL** database in the process with the help of **SQLAlchemy** library.
<p align="center"><img width="720" src="analytics_final.jpg"></p>


#### [Youtube playlist generation for a desktop media player](playlist.html)
   Using **Youtube Data v3** and Google's own authentication libraries, I search through a "Geek and Sundry" channel, find "Spellslingers with Day\[9\]" playlist and format it to fit my media player of choice.
<p align="center"><img width="720" src="yt playlist mockup 0.png"></p>


#### [A price of MtG tribe's card collection](web_scraping.html)
   Gently scraping two databases of Magic the Gathering cards with **Requests** and **Scrapy**, I first find out all the names of cards from a certain collection, and then how much a full set of them, four copies each, can cost.
<p align="center"><img width="720" src="web scraping mockup 0.png"></p>


#### [Downloading a podcast from Apple Music RSS feed](podcasts.html)
   In goes an .rss URL, out goes a folder full of .mp3 files. Simple as that. Starring: **BeautifulSoup**.
<p align="center"><img width="720" src="podcast-dl mockup 0.png"></p>
