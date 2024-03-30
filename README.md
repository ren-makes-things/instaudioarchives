# instaudioarchives
the archive of instaud.io

## Status of the project
This is going to be on hold for a WHILE because i have to contact the internet archive and provide them with the IP addresses of the server or servers scraping the entire 20 thousand URLs

### You can check the issues tab for the most up to date status on things

## How am i going to do this
Simple, python, docker, a good internet connection, some wayback machine API, and more python

There are gonna be two parts to this,
* Scraping and sorting the data
* Hosting the data & music (or providing archive.org links to the music) on a static online database

## Why am i doing this
Read [this twitter post](https://twitter.com/PixelatedEngie/status/1768022239159472238) 
I got bored, wanted to program/do something, this is what i ended up working on, apperently instaud.io is ***very*** important to the undertale community for one reason or another, so i figured why not

## When can i expect this to come out?
Not sure yet

### The easy explination of why this is going to take a while
i have to take 20 thousand puzzle peices with no clear accociation with eachother and complete it

### The more techincal end of why this is going to take a while 
I have to parse the html of over 10 THOUSAND urls and accociate those with links to archived S3 bucket mp3s, and present it all in a clean nice website thats fully searchable and filterable

**but there is a catch**

instaud.io decided, it would be REALLY SMART, to use the same ID for multiple different songs! that or archive.org's archiveing tools failed badly for some reason



# Credits
[Ren](https://twitter.com/ren_dreemurr) - The guy who programs stuff

[PixelatedEngie](https://twitter.com/PixelatedEngie) - The dude who came up with the idea
