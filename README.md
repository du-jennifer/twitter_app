# Project 3 - *Twitter*

**Twitter** is a basic twitter app to read your tweets.

Time spent: **8** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User sees app icon in home screen and styled launch screen. (1pt)
- [x] User can log in. (1pt)
- [x] User can log out. (1pt)
- [x] User stays logged in across restarts. (1pt)
- [x] User can view tweets with the user profile picture, username, and tweet text. (6pts)

The following **bonus** features are implemented:

- [x] User can pull to refresh. (1pt)
- [x] User can load past tweets infinitely. (2pts)

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://i.imgur.com/yY8ZW2E.gif)

## Notes

Describe any challenges encountered while building the app.

During this app, I had trouble completing Twitter's login page, as the login button wouldn't navigate to the authorization page/login page of twitter. A 401 error kept appearing. Realizing that Twitter increased its security on its API usage, I had to sign my submit a form on regarding my usage of their API and generate a new consumer key and consumer secret key. I then replaced these in the  TwitterAPICaller.swift file. Lastly, I enabled 3-legged oauth in the app settings. Finally, the login button was able to redirect me to Twitter's login authorization page. 


