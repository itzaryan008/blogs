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

<details>
  <summary>What's New?</summary>
  
  __UPDATE!__
  - Fixed Render Issue.
  - Added unfont.js
  - Added sharecontact.js
  - Bug fixed!
  - HandleReply.js issue fixed!
</details>

<details>
  <summary>Languages</summary>
  
> - en = English-US 
> - vi = Vietnamese 
> - tl = Tagalog 
> - cb = Bisaya/Cebuano
> - bd = Bengali 
> - ar = Arabic

Go to your config.json and set it in the language property:
```json
{
  "language": "en",
}
```

Looking for a French language translation done by a local French! Your contribution would be greatly appreciated, and credits will be provided!
</details>

<details>
  <summary>Appstate Encryption</summary>
  
  ### Security 
