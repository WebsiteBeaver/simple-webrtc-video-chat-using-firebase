# Simple WebRTC Video Chat Using Firebase

![Simple WebRTC Video Chat Using Firebase](https://user-images.githubusercontent.com/26162804/31845534-ac2cca0c-b5cf-11e7-8874-94c4d978fcb8.jpg)

This is a 1-to-1 video chat using WebRTC and Firebase as the signaling server. You can use socket.io for your signaling server instead of Firebase, but this uses Firebase to keep things simple. If you've never used WebRTC, this is the perfect repo for you to learn the basics.

## Demo

Try out the demo at https://codepen.io/dmarcus/pen/PWmRmj. Open the CodePen on two different computers or mobile phones, press change the Firebase credentials and Viagenie credentials as described below, and press call to see the 1-to-1 video chat in action. Here's a video showing us using the demo:

[![Demo of WebRTC Video Chat](https://user-images.githubusercontent.com/26162804/31845610-968e0372-b5d0-11e7-8533-63a383c27f98.jpg)](https://www.youtube.com/watch?v=VsPco9VYSfs)

## Tutorial

You don't need to follow this tutorial. You change simply download this repo, and run the code on your https server. But if you'd like to understand how the code works, take a look at [the tutorial ](https://websitebeaver.com/insanely-simple-webrtc-video-chat-using-firebase-with-codepen-demo) that goes with this repo.

## Getting Started

Create a Firebase account, and replace these credentials with your credentials. Be sure to make it readable and writable to the world as explained in the [tutorial](https://websitebeaver.com/insanely-simple-webrtc-video-chat-using-firebase-with-codepen-demo). These credentials are found in [js/script.js](https://github.com/WebsiteBeaver/simple-webrtc-video-chat-using-firebase/blob/master/js/script.js)

```
var config = {
  apiKey: "AIzaSyCTw5HVSY8nZ7QpRp_gBOUyde_IPU9UfXU",
  authDomain: "websitebeaver-de9a6.firebaseapp.com",
  databaseURL: "https://websitebeaver-de9a6.firebaseio.com",
  storageBucket: "websitebeaver-de9a6.appspot.com",
  messagingSenderId: "411433309494"
};
```

You should also create an account on [Viagenie](http://numb.viagenie.ca/), and replace the following code from [js/script.js](https://github.com/WebsiteBeaver/simple-webrtc-video-chat-using-firebase/blob/master/js/script.js) with the information from your account.

```
{'urls': 'turn:numb.viagenie.ca','credential': 'websitebeaver','username': 'websitebeaver@email.com'}
```

## Built With

* [WebRTC](https://webrtc.org/) - Used for real-time communication
* [Firebase](https://firebase.google.com/) - Used for signaling
* [Bootstrap](http://getbootstrap.com/) - Used for styling

## License

MIT License

Copyright (c) 2017 David Marcus

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
