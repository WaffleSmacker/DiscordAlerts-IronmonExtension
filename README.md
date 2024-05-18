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
U0JBRR+LCAAAAAAABADtWFtv2zYUfh+w/6AG6Fvp8CZRzMvQtV03oGiBpV2xDUXBy5GtVRI9inISFPnvoyQ7iS0nSNJ1WLe+JBa/40OeC7/vyB+//SZJDlbg29I1B0cJezQslPXS+fDL7nJdNmXd1ZfrB3hGZ+xgjUJQce1j/xAfG1VDb/K0bI3zNnlcgQ/taBth1YWF873BW1UUFRzXynwAf4FfnumAzPAMXwAWWuPLZViDVx26n7vmsVkjTVdVPXQ+ns6qrdOpwayNK7+PK8kGGuDS9r4pM5pmKkUMg0CcE4ZyqyjiAlOTaUwsFpv9h6/92UEH672vrkOjdAW9z0JVLWxBp6bqLPzgXf1j2Qbnz/ZZbZL5jI953Np17l237NHXfshh8tja5FXTbhmp6kSdtTFB+9x71VhXX6RughvXmM57aMI+NPhyPo/luprMnYSOJVW+7PPw8iKYSSyD3bIvfRuGfOFdcKwM4CzDhgiUEoMRVyZDutAFwkxrHPuJZJBN/IazZb+vwHIXuaxP8B1M0L5E7aZd3l1Fzy8f3m1le9pe+zIyBmOYFFJbgyTGEnGZK6QzzBHhlAkJhFJDJsGcQDlf9OWId+OaQCnZBS46ZeLu5gyUjYXTfq+t2B/dFNpNHTsYdC34jdFP3jW1awbD793U9gT0wrkPb3y19/CxPcPYmwcPtXfKGtWGN9H/w6RskwUoWzbzJLgkLCB5xh8kTxYQr0nhfL9SJyocJYsQlu3R4WE4KYNZzMLqcMfVZNeyVnPYex61imTj90IBTsNrd7wEMIs9d2l0PHSF5AZryS1SmGeI4zRFeUoKRDDXgrGCCqHv0xUC42v7Yoe3Bux2nUFv3xkrVXVjazxP1uKwp6KV25/AMTkFA5sRLBDLGUPcqhwpmkMkalkIJimGTN0nOQRPyeFTLw25PWE877caWWabfqtKLVuwV/ANfJnrqX7llEgKoJAkMuoX0wblNLKkMlqkmnBVcPhn9etYFVEEkt9cA/8hIRujureYxXZVklAdb3oay6RkgXJMJIpCkKc8YzxP8RcjZoQbySjlKAUaJyXNYjCFVUhZAlmapwaze93Mr2L2MKmVhaQMGyW7cpkeJG8Xrhc7H8XubFC21tWQLMuVC1H8vks+k8BtvLZBhdIgY5vZH2HVnMwaCIfx0/s+M++XpQmdh/ZQKG5ynmco15GH4twWuwNkigorrLU0K3ictpfeFWUF74f9kcCnAs+WzfwTtDQVGnAuMSqosYhTiHJR5BgRltqU0tSwPP/faqnSqpAFJgg0iYOGBIw0FRLlJs7YIqdx6BBftdTEQVzEkQsRYiOvKWyR5NwgDEyRQqdxQGN31NKdQO8opQO/JMcQumWCklcvX/yaPH0V/z959kVram/48Xx/pzIlRWFE36nxD8/ii5I0cbIhBcWUZCnLlLxeKOm/RSgttJGT1Tqfk+tzn9fkfQG0rvNmuIjTHdas8TRKxzWsoLkuCE01KlgKPWUSpCVhiDFlKUsVVun0Dfs2rEAndfh0xryDlN8x+bcd7f7+AmCcC5JhhaI89T9xMIivOFEqM0bSFGMNmt/vFedzFOAz8/L4YWM/UuuWi/j1uo48tb0YJ63WRdILx+BXaw6agk+qMnLXNhjKemPfr8QDnP8FfawOwSsVAAA=
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


