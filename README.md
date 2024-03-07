# Media Library
A web app that keeps track of the shows you watch and downloads the recent episode or the one you will be watching. The web app will also function as a streaming service to access the media library. The motivation for this app is that I am too lazy to search and download the shows I want to watch. consider this aas an app to keep track of the shows I watch

## Goals
1. micro service to download meida through torrent. This service will bw made using pyhton for its scrappy library. This step will need bot detection counter measures. An example is that if I want to watch the show The Rookie, the service should keep track of when a new episode will be available and download the latest/next episode. At frist the release time and date will be entered manually, once this will be upo and runnig the service should simply do a web search and figure out whent the next episode will be available.
2. App to access the downloaded media. This will include auth and give the option to maintain the library locally or on the cloud. The app will have the option to stream media from devices that have downloaded media like plex.
