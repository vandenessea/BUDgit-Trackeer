# BUDgit-Trackeer
# Unit 19 PWA Homework: Online/Offline Budget Trackers

Functionality has been added to the existing Budget Tracker application to allow for offline access and functionality.

The user is able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they will be able to populate the total when brought back online.

* We added in a service worker file, and manifest.json file. The service worker file is essentially a JavaScript file that runs separately from the main browser thread, intercepting network requests, caching or retrieving resources from the cache, and delivering push messages.
* The manifest.json file provides information about an application (such as name, author, icon, and description) in a JSON text file. The purpose of the manifest is to install web applications to the homescreen of a device, providing users with quicker access and a richer experience.

## Business Context

This application is giving users a fast and easy way to track their money, and allowing them to access that information anytime. Having offline functionality is paramount to the applications success.






* This application is deployed with [Heroku and MongoDB Atlas.](../04-Important/MongoAtlas-Deploy.md)

