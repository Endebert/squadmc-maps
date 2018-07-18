# squadmc-maps
repository for [SquadMC](https://github.com/Endebert/squadmc) holding the only the map image files. Also includes maps for PostScriptumMC.

# Usage

SquadMC works with external maps hosted on maps.squadmc.ende.pro. However, if you wish to host and serve them locally, follow these steps:

 0. `npm install -g yarn`
 1. `yarn install`
 2. `yarn run mapdata`
 3. `yarn run serve`
 4. adapt the baseUrl variable in the squadmc repository (`squadmc/src/App.vue`), to whatever `http-server` tells you