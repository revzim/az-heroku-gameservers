# AZ 3D-PHYSICS GAME SERVER & CLIENT

## game server and client demo with server-side physics developed in TypeScript.

### [Game Server Room Creation Tool & Demo](https://azim-gs.herokuapp.com/)
### [Quick Start/Join Game Demo](https://azim-gs.herokuapp.com/game/)

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
* every AI that joins will have auto play toggled on automatically.
* [Album](https://imgur.com/a/xWM1H9N)

#### QUERY PARAMS
* join a specific game room: `https://azim-gs.herokuapp.com/game/?room_id=<ROOM_ID>`
  * ROOM_ID => room id
* quick create a game mode room: `https://azim-gs.herokuapp.com/game/?id=<GAME_MODE_ID>`
  * GAME_MODE_ID => paint || eat

#### OTHER HEROKU DEMO APPS (Older iterations of game servers with different uses):
* [Golang Game Server (Box2D server side physics) Demo](https://az-b2d-physgs.herokuapp.com)
  * game server developed in Golang
  * ported box2d golang library for server side physics
  * simulate multiple users movement; dynamic & static objects; freeze/pause & restart game server world; render library CubicVR.js; 
* [Online Jeopardy Game Clone Demo](https://azjeopardy.herokuapp.com)
  * game server developed in TypeScript
  * jeopardy clone; tap the question button in the bottom right for easy questions; hold the question button to change question difficulty 100-1000; type your answer; 4 people per room
  * my family enjoys playing jeopardy, so I created a clone to enjoy with others or by yourself

##### *HEROKU DEMO APP DISCLAIMER*
`initializing a room with > 100 AI per room will directly impact server/client lag due to hardware limitations. try to keep it below 100.`
`ai(s) & player(s) have direct impact on network latency & client fps/latency`

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
