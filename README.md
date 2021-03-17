# AZ 3D-PHYSICS GAME SERVER & CLIENT

## game server and client demo with server-side physics developed in TypeScript.

### [AZ GAME ROOM CREATION TOOL (Heroku hosted app)](https://azim-gs.herokuapp.com/)
### [QUICK START GAME DEMO (Heroku hosted app)](https://azim-gs.herokuapp.com/game/)

#### QUERY PARAMS
* join a specific game room: `https://azim-gs.herokuapp.com/game/?room_id=<ROOM_ID>`
* quick create a game mode room: `https://azim-gs.herokuapp.com/game/?id=<GAME_MODE_ID>`
  * GAME_MODE_ID => paint || eat

![GAME DEMO](https://i.imgur.com/o8QkHAt.png)
![GAME DEMO w/ REAL-TIME STATS](https://i.imgur.com/WFcnytL.png)
![CREATION TOOL](https://i.imgur.com/5nqCf2K.png)

### GAME MODES:
* eat -> 3D agario/slitherio type game mode
* paint -> you will change the color of any npcs/objects you come in contact with

### HOW TO PLAY
* use your fingers/mouse to tap/click/drag the camera to move your player in whichever direction the player is facing.
* use the speed slider to adjust your speed.
* tap the menu button to view real-time stats about the game room/world.
* tap the play button to toggle auto play. Auto play will automatically attempt to complete the task(s) of the game mode.
* Every AI that joins will have auto play toggled on automatically.

[ALBUM](https://imgur.com/a/xWM1H9N)

##### *HEROKU DEMO APP DISCLAIMER*
`initializing a room with > 100 AI per room will directly impact server/client lag due to hardware limitations. try to keep it below 100.`

#### author: revzim

#### server: TypeScript
- Physics Engine Tick Rate 60Hz
- Game Server Tick Rate 20Hz
- [Express](https://github.com/expressjs/express)
- [Colyseus](https://github.com/colyseus/colyseus)
- [BabylonJS w/ OIMO](https://github.com/BabylonJS/Babylon.js)
- [OIMO Physics Engine](https://github.com/lo-th/Oimo.js/)

#### client: HTML/CSS/TypeScript/JS
- [Vue](https://github.com/vuejs/vue)
- [Vuetify](https://github.com/vuetifyjs/vuetify)
- [BabylonJS (for rendering only)](https://github.com/BabylonJS/Babylon.js)
