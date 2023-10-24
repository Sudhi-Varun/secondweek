# secondweek
 Please follow the instructions in Readme
 
 1)Clone the repo at the following link, and deploy on the local server.
 https://rxdb.info/replication-graphql.html

 2) 'client' folder in this repo contains modifications to include update function, hard coded database and ip address of test server. Replace client in the local deployment done earlier with this one.
 
 3) 'dist' folder is the build genertated using webpack. This is a standalone self contained web resources folder, which can be ported to any stytem or server.
 
 4) Install capacitor (capacitor.js) at the root folder of the node.js installation.
 
 5) Now perform init operation 'npx cap init'. The web folder is 'dist' folder.
 
 6) Update the capacitor.config.json like the one in this repo. This is needed to hard code server IP and Port numbers, and allow Websocket connections.
 
 7) Now generate android build using 'npx cap add android'.
 
 8) Server can be run by navigating to the folder and using 'npm run server'.
 
 9) 'Android' folder in this repo is generated using the above command. This can now be imported into Android Studio and tested. 
 
 
 Output:
 
 The android app generated is working irrespective of the availability of server. Whenever server is available, data is synced with the server. 