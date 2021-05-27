# Blabbr API
## The official API to communitate with the [Blabbr website](blabbr.xyz)

### Get Started!
#### First, you have to import the api, you can either download it from our [github repository](https://github.com/TeamBlabbr/Blabbr-API/blob/main/index.js)

##### or

#### Run this command in your terminal
``` shell
npm install blabbr-api

```

### Setting it up
#### to start, you have to import the API:
``` nodejs
const api = require('blabbr-api')
```

### Features
#### To send a message in a specific room, run:
``` nodejs
api.sendmessage('username', 'room', 'message')
```

#### To Get a list of all users in a room, run:
``` nodejs
api.getusers('room')
```

### Questions? Contact us on our website.
