# Simple WebRTC Video Chat Using Firebase

This is a 1-to-1 video chat using WebRTC and Firebase as the signaling server. You can use socket.io for your signaling server instead of Firebase.

## Getting Started

Create a Firebase account, and replace these credentials with your credentials.

```
var config = {
  apiKey: "AIzaSyCTw5HVSY8nZ7QpRp_gBOUyde_IPU9UfXU",
  authDomain: "websitebeaver-de9a6.firebaseapp.com",
  databaseURL: "https://websitebeaver-de9a6.firebaseio.com",
  storageBucket: "websitebeaver-de9a6.appspot.com",
  messagingSenderId: "411433309494"
};
```

## Built With

* [WebRTC](https://webrtc.org/) - Used for real-time communication
* [Firebase](https://firebase.google.com/) - Used for signaling
* [Bootstrap](http://getbootstrap.com/) - Used for styling

## Authors

* **David Marcus**