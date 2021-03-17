# AZ 3D-PHYSICS GAME SERVER & CLIENT

## game server and client demo with server-side physics developed in TypeScript.

### two game modes:
* eat -> 3D agario/slitherio type game mode
* paint -> you will change the color of any npcs/objects you come in contact with

![GAME DEMO](https://i.imgur.com/o8QkHAt.png)
![GAME DEMO w/ REAL-TIME STATS](https://i.imgur.com/WFcnytL.png)
![CREATION TOOL](https://i.imgur.com/5nqCf2K.png)

[ALBUM](https://imgur.com/a/xWM1H9N)

### [AZ GAME ROOM CREATION TOOL (Heroku hosted)](https://azim-gs.herokuapp.com/)
### [QUICK START GAME DEMO (Heroku hosted)](https://azim-gs.herokuapp.com/game/)

### To join a room to play with friends head to https://azim-gs.herokuapp.com/game/?room_id=<ROOM_ID>

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
