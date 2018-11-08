### signalr-jquery-shim 

(jquery free signalr, signalr without jquery)

A for of signalr-shimmy which is based on signalr-no-jquery which is based on react-native-signalr :D :D
but whithout signalr itself made to work woth other soultions for example ng2-signalr to make it work without jquery saving more than 80kb of you bundle

### how it work
just polly fill JQuery object on window

### Usage

```
npm i signalr-jquery-shim --save
```

then just replace jquiry with it and signalr will still work as expected in case of angular
add this to angular.json
```
"scripts": [
              "node_modules/signalr-jquery-shim/build/signalr-jquery-shim.js",
              "node_modules/signalr/jquery.signalR.js"
            ]
```

