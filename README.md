<h1 align="center">Welcome to zoom 👋</h1>
<img src="/asset/image.png">

> A webrtc based video chat application that uses node.js as backend and react as frontend

### 🏠 [Homepage](https://github.com/devil-cyber/zoom#readme)

### ✨ [Demo](https://zoom-chat.netlify.app)

## Install

```sh
# To install required library for the Node.js backend
npm install

# Now go to the client directory
cd client
npm install 
```

## Usage

```sh
# To run the backend server
npm start

# Now go to client directory
cd client 
npm start
```

## Note

```sh
# Inside client there is a folder name src and inside that there is a file SocketContext.js

# Now go inside that file and  add http://localhost:5000 for localhost:
const socket = io('http://localhost:5000');
# And for production replace it with the deployed server link
const socket = io('https://"your".herokuapp.com');
```

## Author

👤 **Manikant Kumar**

* Website: https://devil-cyber.github.io/CodingSpace/
* Github: [@devil-cyber](https://github.com/devil-cyber)
* LinkedIn: [@mani360](https://linkedin.com/in/mani360)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
