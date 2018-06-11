# squadmc-maps
repository for [SquadMC](https://github.com/Endebert/squadmc) holding the only the map image files. Also includes maps for PostScriptumMC.

# Usage

SquadMC works with external maps hosted on maps.squadmc.ende.pro. However, if you wish to host and serve them locally, follow these steps:

 1. `npm install`
 2. `npm run mapdata`
 3. `http-server public`
    * There are many different ways to serve the public folder locally, but `http-server` is very easy
    * if you don't have `http-server` installed already, run `npm install -g http-server` to have it globally available
 4. adapt the baseUrl variable in the squadmc repository (`squadmc/src/App.vue`), to whatever `http-server` tells you