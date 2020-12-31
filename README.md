# Twitter tipbot - A twitter tipbot for Beyondcoin

This repo contains the twitter tipbot used by Beyondcoin. This bot allows users to tip each other BYND on Twitter.

## Installation
### Prerequisites
* beyondcoind
* Node.js v8+
* Yarn
* A twitter application on the tipbot account

>To get started you should clone the git:
```
git clone https://github.com/beyondcoin-project/twitter-tipbot
```
>Install all modules with yarn:
```
yarn install
```
>Rename default.example.json to default.json and enter the twitter tokens and daemon settings.

>Run the bot with:
```
node index.js
```
>If you want to move over accounts from the old tipbot format which used usernames as identifier, run move_helper.js:
```
node move_helper.js
```
>It will automatically move over the old accounts to the new id based system.


## License
This project is MIT Licensed &copy; [BYND](https://github.com/beyondcoin-project)

## Security

We take security seriously. Please contact security@beyondcoin.io regarding any security issues.

