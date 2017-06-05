Polymer Offline Weather Codelab
===
See http://www.code-labs.io/codelabs/polymer-offline-weather for codelab instructions.
See https://googlecodelabs.github.io/polymer-offline-weather/final/index.html for the final working version of the codelab.

To configure service worker put the sw-import.js in the root directory. You need also to manually configure the polymer.json file to manually copy the js file of the 'bootstrap' folder and the sw-toolbar folder to the build directory.  
For the bundled version, the bootstrap folder from the platinum-sw and the sw-toolbox to the build directory, the easiest way is to copy them to top level directory and also config polymer.json to copy them in the build directory.