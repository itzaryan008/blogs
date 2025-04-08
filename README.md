### BOT DETECTION
__=>__ Have you ever experienced this type of issue in facebook?
  
<img align="center" src="https://i.ibb.co/4SChsvH/facebook.jpg">

Maybe, I can help you with that. So these are the things to do. Go to your **config.json** and look for **autoCreateDB**. If you found it, then simply replace true to false.
<br><br>
__BEFORE:__
```json
{
  "autoCreateDB": true,
}
```
__AFTER:__
```json
{
 "autoCreateDB": false,
}
```
<br>
By setting this to false, some commands like checktt, rankup and other commands that needs database may not work but it has a good benefit making your bot last longer and might avoid being suspended for a long period of time.

---
### Run bot on your own ID
__=>__ 
  
<img align="center" src="https://i.imgur.com/gJGPC5w.jpeg">

Maybe, I can help you with that. So these are the things to do. Go to your **config.json** and look for **selflisten**. If you found it, then simply replace false to true.
<br><br>
__BEFORE:__
```json
{
  "selflisten": false,
}
```
__AFTER:__
```json
{
 "selflisten": true,
}
```
<br>
If you set this to true, you will have to run the bot very carefully when adding it Do not log out while your vote ID is logged in to Facebook, otherwise there may be a problem with the ID

---
<br><br> __credit boy ArYAN__
  - [ itz Aryan 🎀](https://www.facebook.com/profile.php?id=61574850908374)

---
Copyright © 2024 ArYAN AHMED RUDRO Philippines.<br>
