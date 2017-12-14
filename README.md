## example-polymer-tab-sync

A quick example project using local storage with `app-storage` elements to synchronize info between browser tabs.

Well, it's a Twitter-like between tabs of a same browser, i.e. a tab can post messages and all the other tabs receive the
messages and display them in real-time.

Open this page in several browser tabs (on the same browser, of course). Each tab will get an unique instance id.
Write and send some messages...

## How to test

1. Clone or download this repository

1. Install `bower` and `polymer-cli` if needed

  ```
  $ npm install -g bower polymer-cli
  ```
  
1. Recover dependencies via bower

  ```
  $ bower install
  ```
  
1. Run polymer serve

  ```
  $ polymer serve 
  Starting Polymer serve on port 8080
  Files in this directory are available under http://localhost:8080/components/example-polymer-tab-sync/   
  ```
  
  