Firebase Node Realtime Database Quickstart
==========================================

The Node Firebase Database quickstart demonstrates how to connect to and use the Firebase Realtime Database using Node through a simple social blogging app. It will interoperate with the Web, iOS and Android database quickstarts.

This server will:
 - Update the star counts for all posts.
 - Send email notifications when a post has been stared.
 - Send weekly emails listing top post.

Introduction
------------

- [Read more about Firebase Database](https://firebase.google.com/docs/database/)

Getting Started
---------------

- Create your project on the [Firebase Console](https://console.firebase.google.com).
- Create a Service account as described in [Adding Firebase to your Server](https://firebase.google.com/docs/server/setup) and drop the file in this directory.
- Change the `<PROJECT_ID>` and `<PATH_TO_SERVICE_ACCOUNT_CREDENTIAL_FILE>` placeholders in `index.js`.
- Configure your email transport in `index.js`.
- Run `npm install`.
- Run `node index.js` to run the node app locally.
- Configure and run one of the Database quickstarts for [Web](https://github.com/firebase/quickstart-js/tree/master/database), [iOS](https://github.com/firebase/quickstart-js/tree/master/database) or [Android](https://github.com/firebase/quickstart-android/tree/master/database). Then use one of these apps to publish new posts: you should receive email notifications when one of your posts have received a new star and the starred counter should be ept up to date by the app.

Support
-------

https://firebase.google.com/support/

License
-------

© Google, 2016. Licensed under an [Apache-2](../LICENSE) license.
