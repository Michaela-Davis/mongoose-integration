Step 1 – Install Node.js

Step 2 – Install Express Generator
* npm install -g express-generator

Step 3 – Install Dependencies
* npm install

Start Mongo server
➜  bin ./mongod --dbpath ~/development-michaela/node/nodetest1/data/ 
* change path according to local location

* You'll see the Mongo server start up. This is going to take a while if it's the first time, because it has to do some preallocating of space and a few other housekeeping tasks. Once it says "[initandlisten] waiting for connections on port 27017", you're good. There's nothing more to do here; the server is running. Now you need to open a second command prompt. Navigate again to your Mongo installation directory, and type:

    Command C:\mongo\bin\
    ```
    mongo
    ```

    Mongo Console
    ```
    use nodetest1
    ```

Start server
* npm start
* cntrl + c to quit