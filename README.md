# DiscordAlerts-IronmonExtension
DiscordAlerts - IronMon Extension for sending notifications to discord when you get to E4 or Safari Zone!
Created by [WaffleSmacker](https://www.twitch.tv/wafflesmacker)

![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/520444bf-02b4-4ba5-9fe9-c8e107ea0350)


## Requirements
- [Ironmon-Tracker v8.4.1](https://github.com/besteon/Ironmon-Tracker) or higher
- [Streamerbot v0.2.3](https://streamer.bot/api/releases/streamer.bot/latest/download) or higher

## Setup
This extension requires that you have streamerbot up and running.<br>
1. Copy the following text and import it into Streamerbot:<br>
```
U0JBRR+LCAAAAAAABADtWF1v2zYUfR+w/6AG6Fvp8EuimJeha7tuwNACS7tiG4qCH5e2Vn14FOUkKPLfR0l2EltOkKTrsK59SSyea5L33sNzKH/49pskOViBb4umPjhK2KNhoKiWjQ+/7g5XRV1UXXU5foBndMYO1igEFcc+9A/xsVYV9CFPi9Y03iaPS/ChHWMjrLqwaHwf8EY5V8Jxpcx78Bf45Z4OyAzP8AVgoTW+WIY1eHXC5peufmzWSN2VZQ+dj7uzamt3aghr48gf40iygQa4sP3clBlNM5UihkEgzglDuVUUcYGpyTQmFovN+sPX/uqgg/XaV8ehVrqEfk6nyha2oFNTdhZ+8E31Y9GGxp/ti9oU8xkf67i16tw33bJHX/mhhslja5OXdbsVpMoTddbGAu2b3qvaNtVF6Sa4aWrTeQ912IcGX8znsV1Xi7lT0LGlyhd9HV5cJDPJZYhb9q1vw1AvvAuOnQGcZdgQgVJiMOLKZEg77RBmWuPIJ5JBNpk3nC37dQWWu8hlf4LvYIL2LWo3dHl7FT2/fHi7Ve0pvfZVZEzGMCmktgZJjCXiMldIZ5gjwikTEgilhkySOYFivujbEc/GNYlSsgtcMGUy3c0VKGoLp/1aW7k/uim1mxg7BHQt+E3QT76pq6YeAr9vprEnoBdN8/61L/duPtIzjNw8eKh9o6xRbXgd53+YFG2yAGWLep6EJgkLSJ7xB8mTBcRj4hrfj1SJCkfJIoRle3R4GE6KYBazsDrcmWqyalGpOezdj1pFsRm0bTNrG1QoDDK2nv0ZVvXJrIZwGD+966vwblmY0HloD4XiJud5hnIdyRxp7VAOMkXOCmstzRyPYrT0jStKeDesjwQ+FXi2rOdTusNpeNUcLwHMYs+xHXMYCCi5wVpyixTmGeI4TVGeEocI5low5qgQ+j4EFBhfS8EdiRyw25GQ3p6EK1V2IwufJ2sf2kOecvShaYOH4jgGNiNYIJYzhrhVOVI0h+gJ0gkmKYZM3ac4BE916GPPJ7m9Nj3vlxoFbVvpy1ItW7BX8A18WeupVeaUSAqgkCQyWiXTBuU0clgZLVJNuHIc/l2rPFYu+k3ye1PD/8gzx6zu7ZuRrkoSquNJT2OblIwCg4lE0XPylGeM5yn+bHyTcCMZpRylQOOlTLOYjLMKKUsgS/PUYHavk/nVNx8mlbKQFGFjmlcO04PkzaLpfdVHXz0bTLRtKkiWxaoJ0We/S75oL02FBpxLjBw1FnEK0S5cjhFhqU0pTQ3L8y/WS5VWTjpMEGgSLxoSMNJUSJSbeJ0XOY2XDvHVS02884t45UKE2KhrClskOTcIA1PE6TRe0NgdvXQn0Tta6aAvyTGEbpmg5OWLn39Lnr6M/588+6w9tQ/8cL6fqUxJ4YzomRr/8Cy+k0kTbzbEUUxJlrJMyeuNkv5XjNJCGzVZres5OT73eSPfl0DbdN4MB3G6wlo1nkbruEYVNNeO0FQjx1LoJZMgLQlDjClLWaqwSqcv87dRBTrpw8cr5h2s/I7Fv+3V7p9vAMa5IBlWKNpT/2sKg/iKE60yYyRNMdag+f1ecT5FAz6xLo8fNvGjtG5NEb9eVVGntgfjTattouiFY/CrtQZNwSdlEbVrGwxFtYnvR+IGzv8GK1+XQpYVAAA=
```
![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/98f44034-d9b3-4f68-9836-13ba72b8636c)<br>

2. Click import and the new actions will be added to your streamerbot instance.<br>

3. We need the global variables for E4 and Safari to exist in order for the extension to work correctly. Click "Alert Setup - ONLY DO THIS ONCE" & then right click "Test" and then "Test Trigger" <br>

![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/8ba4aed6-99de-4aa9-9b02-5a7c882bf765) <br>

3a.If you want to verify that it worked correctly, click "Variables" then click "Last Write" 2 times to see the most recent variables:<br>
![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/5d7dc928-36cc-46cc-965c-899f02536de1)<br>


![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/744eea32-1ccb-4ec7-b90d-58006abb0b40)<br>

4. Disable "Alert Setup - ONLY DO THIS ONCE" then Enable "E4 Alert" & "Safari Zone Alert"  (should look like below)<br>

![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/9d3b7fa8-8ea4-47e1-849e-a52aca713f5e) <br>

5. Set up which discords you want to send notifications to:<br>
(IF YOU ARE IN EPILOGUE GAMING REACH OUT TO BEN OR WAFFLE FOR THE URL)<br>
By default you will probably want to add your own discord.<br>
Access your discord channel where you want the notifications to go and get a websocket url. (edit channel -> Integrations -> Webhooks -> New Webhook -> Copy Webhook URL) <br>
Using that url paste it into both the E4 and Safari Alert sub-actions in streamerbot.<br>
![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/b3e07a0b-c5be-4744-bd50-1c8b19d1eaad)<br>

5a. You can set up notifications to multiple discords IF you have permissions!<br>

6. You are done setting it up!  Now play the game and get a good run!<br>


## How to Use

Simply turn the extension on when you are playing IronMon. <br>

Once you enter the Safari Zone OR When you successfully escape from Victory Road you will get a popup. <br>

![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/8b995a3a-6040-4811-ad82-a6c9950ab917)<br>


Click Yes to send an automated Discord message with a link to your stream and a notification!  Click No to do nothing! <br>

Example of what it looks like on Discord:<br>

![image](https://github.com/WaffleSmacker/DiscordAlerts-IronmonExtension/assets/131427794/ec67dce1-9744-429d-97fb-928349dfc8ee)


