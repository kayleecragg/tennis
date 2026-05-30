# [Tennis Checkerboard](https://kayleecragg.github.io/tennis/)

<img src="assets/checkerboard2.webp" width="70%">

## Access the checkerboard at [kayleecragg.github.io/tennis](https://kayleecragg.github.io/tennis/)
## Read blog post about this project at [kayleecragg.github.io/projects/checkerboard](https://kayleecragg.github.io/projects/checkerboard/)

description of files:

- index.html: main page
- offline.html: static page to demonstrate what shows when connection to vercel api goes down
- test.html: test page to demonstrate moving courts feature
- schedule.json: static json to use for in between seasons so that vercel isn't getting called

assets folder:
- aaa.gif: for offline page
- checkerboard2.webp: for readme
- rg.png: for future use
- wimbledon.png: for future use

## how it works? 

- msi checkerboard down since 2024
- roland garros has an api but webpage browser cannot access because of CORS
- vercel server made so that bypass CORS
- vercel server queries https://www.rolandgarros.com/api/en-us/polling every time it is called by this web page (about every 1.5 seconds)
- improvements made recently to increase interval check from like 20 seconds to 1.5 seconds (speed :sunglasses:)

## result

- new checkerboard :)
- near instant updates to scoring
- player change and court change notifications
- court selections (so you only view courts that you want instead of all at once)
- pretty colours