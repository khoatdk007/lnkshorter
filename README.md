﻿# LnkShorter
 
## About
This is kind of a clone of Bitly.com, which shortens your link.

## Installation

### Required
You can download this app and run it yourself by the following commands.
But you have to install Git and Nodejs before doing this.

```
git clone https://github.com/khoatdk007/lnkshorter.git
cd lnkshorter
npm install
```
Then rename `.env_sample` to `.env` and put your database link to that file.
For example :
#### .env
```
DB_URL=mongodb://localhost/lnk-shorter
```
After install, you can run it by :
```
npm start
```
You will see these messages in your Terminal
```

> linkshortener@1.0.0 start D:\Programming\LinkShortener
> node app.js

Connected to MongoDB
Server started on port 5000
```
After that, you go to [http://localhost:5000/](http://localhost:5000/) and YAY, it's running !

![The app is running !](https://i.imgur.com/zeIDvrA.png)

## Usage
This LnkShorter is very easy to use. You put your link into the input and you get your short link !
