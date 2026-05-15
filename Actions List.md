# ACTIONS LIST

Welcome to the web page made for listing all of the actions provided with the Botymuch streamer bot built and maintained by [Berymuch](https://www.twitch.tv/berymuch). While the majority of these commands were created by me, I have included those made by others that I have found to be useful.

> [!NOTE]
> Many of the actions in this bot are in active development and also update irregularly. Check back infrequently for more details as I record them.

*Current Action count: 129*
PiShock | Commands | Prizewheel & Chat GPT | Twitch API
:---: | :---: | :---: | :---:
[PiShock - Twitch Interactions](#PiShock---Twitch-Interactions) | [Broadcaster Commands](#Broadcaster-Commands) | [Spinning Prize Wheel](#Spinning-Prize-Wheel) | [Passive OBS Interactions](#Passive-OBS-Interactions)
[PiShock V2 - Core](#PiShock-V2---Core) | [Chat Command Unit Conversion](#Chat-Command-Unit-Conversion) | [Spinning Prize Wheel - Custom](#Spinning-Prize-Wheel---Custom) | [Redeems](#Redeems)
[PiShock V2 - Examples](#PiShock-V2---Examples) | [Chat Commands](#Chat-Commands) | [Spinning Prize Wheel - User Group](#Spinning-Prize-Wheel---User-Group) | [Twitch interactions](#Twitch-interactions)
[PiShock V2 - Operations](#PiShock-V2---Operations) | [Moderator Commands](#Moderator-Commands) | [Mustached_Maniac ChatGPT](#Mustached_Maniac-ChatGPT) | [𝘼𝙋𝙄𝙓 Logging](#𝘼𝙋𝙄𝙓-Logging)

***

<a name="Broadcaster-Commands"></a>
## Broadcaster Commands

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Disabler/Enabler (Nuts) | 🟩 | 🟥 | This action works as both a chat command (using !non and !noff) and as an action switch button via the Elgato Streamdeck/vnyan logic to toggle chat redeems on and off (streamdeck functions target the default case on the switchcase tree). In order to sync logic states across all three applications, a temp global variable is set when streamerbot is loaded and referenced to determine which state is currently true. The intended default is to have nut interactions "on" when the stream is first launched. The action also integrates a live on-stream display to show more easily to viewers whether the current state is active/inactive. | [Berymuch](https://www.twitch.tv/Berymuch)
Disabler/Enabler (PiShock) | 🟩 | 🟥 | This action works as an action switch button via the Elgato Streamdeck to toggle PiShock functions on and off. In order to sync logic states across the streamdeck and streamerbot, a temp global variable is set when streamerbot is loaded and referenced to determine which state is currently true. The intended default is to have PiShock interactions "on" when the stream is first launched. The action also integrates a live on-stream display to show more easily to viewers whether the current state is active/inactive. | [Berymuch](https://www.twitch.tv/Berymuch)
Disabler/Enabler (Redeems) | 🟩 | 🟥 | This action works as both a chat command (using !ron and !roff) and as an action switch button via the Elgato Streamdeck/vnyan logic to toggle chat redeems on and off (streamdeck functions target the default case on the switchcase tree). In order to sync logic states across all three applications, a temp global variable is set when streamerbot is loaded and referenced to determine which state is currently true. The intended default is to have redeem interactions "on" when the stream is first launched. The action also integrates a live on-stream display to show more easily to viewers whether the current state is active/inactive. | [Berymuch](https://www.twitch.tv/Berymuch)
Disabler/Enabler (Share Browser) | 🟩 | 🟥 | This action works as an action switch button via the Elgato Streamdeck to toggle on-stream browser sharing functions on and off. In order to sync logic states across the streamdeck and streamerbot, a temp global variable is set when streamerbot is loaded and referenced to determine which state is currently true. The intended default is to have browsershare interactions "off" when the stream is first launched. The action also integrates a live on-stream display to show more easily to viewers whether the current state is active/inactive. | [Berymuch](https://www.twitch.tv/Berymuch) | [Berymuch](https://www.twitch.tv/Berymuch)
Disabler/Enabler (Share Screen) | 🟩 | 🟥 | This action works as an action switch button via the Elgato Streamdeck to toggle on-stream screen sharing functions on and off. In order to sync logic states across the streamdeck and streamerbot, a temp global variable is set when streamerbot is loaded and referenced to determine which state is currently true. The intended default is to have screenshare interactions "off" when the stream is first launched. The action also integrates a live on-stream display to show more easily to viewers whether the current state is active/inactive. | [Berymuch](https://www.twitch.tv/Berymuch)
Emergency Mode | 🟩 | 🟥 | A general kill switch to be used in the event of something like a hate raid or other negative channel event. It toggles shield mode/subscriber only mode/stream labels/onstream chat/vtuber/and browser overlays off and on. A confirmation message is also sent to chat. | [Berymuch](https://www.twitch.tv/Berymuch)
Gacha Mode | 🟥 | 🟥 | Placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)
Nom mode | 🟥 | 🟥 | Placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)

***

<a name="Chat-Command-Unit-Conversion"></a>
## Chat Command Unit Conversion

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Conversion C to F | 🟥 | 🟥 | Controls behavior that uses user input to convert from celsius to farenheit. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion CM to In | 🟥 | 🟥 | Controls behavior that uses user input to convert from centimeters to inches. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion Command Check | 🟥 | 🟥 | Controls behavior that uses user input to return a list of associated command functions. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion F to C | 🟥 | 🟥 | Controls behavior that uses user input to convert from farenheit to celsius. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion fluid ounces to milliliters | 🟥 | 🟥 | Controls behavior that uses user input to convert from ounces to milliliters. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion Ft to CM | 🟥 | 🟥 | Controls behavior that uses user input to convert from feet to centimeters. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion Ft to M | 🟥 | 🟥 | Controls behavior that uses user input to convert from feet to meters. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion In to CM | 🟥 | 🟥 | Controls behavior that uses user input to convert from inches to centimeters. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion Kg to lbs | 🟥 | 🟥 | Controls behavior that uses user input to convert from kilograms to pounds. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion KM to MI | 🟥 | 🟥 | Controls behavior that uses user input to convert from kilometers to miles. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion lbs to Kg | 🟥 | 🟥 | Controls behavior that uses user input to convert from pounds to kilograms. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion M to Ft | 🟥 | 🟥 | Controls behavior that uses user input to convert from meters to feet. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion Mi to KM | 🟥 | 🟥 | Controls behavior that uses user input to convert from miles to kilometers. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)
Conversion milliliters to fluid ounces | 🟥 | 🟥 | Controls behavior that uses user input to convert from milliliters to fluid ounces. | [Rondhi](https://extensions.streamer.bot/t/chat-command-unit-conversion/69)

***

<a name="Chat-Commands"></a>
## Chat Commands

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Burp Counter Increase | 🟩 | 🟩 | Increments a global variable that stores the amount of times the streamer has burped while live. It includes features the activate GFX/SFX effects and posts a confirmation message to chat. | [Berymuch](https://www.twitch.tv/Berymuch)
Chat Gacha | 🟥 | 🟩 | Placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_) & [Berymuch](https://www.twitch.tv/Berymuch)
Interactive Commands | 🟩 | 🟩 | This is a massive command switch tree that consolidates 39+ different chat commands. Features range from random facts to user interaction actions- a big thank you to ItzApix_ for the fold/push/sniff/nom commands and to Luposity for the flip/unflip/angryflip commands! | [Berymuch](https://www.twitch.tv/Berymuch), [ItzApix_](https://www.twitch.tv/ItzApix_), & [Luposity](https://www.twitch.tv/luposity)
Links | 🟥 | 🟥 | This action consolidates around 20 different common website link requests, and ranges from things like discord to tiktok. By default, links are set up to use the Broadcaster's name in the URL and will adapt based off the current twitch account that is set to use streamerbot.| [Berymuch](https://www.twitch.tv/Berymuch)
Quick Maths | 🟥 | 🟥 | This action powers the interactive "quick maths" chat game. Users are able to use the command to return a random or tiered math problem, and then have a set amount of time to answer it in chat. Antes can even be offered up as an incentive/bet if the user of the command is confident that tthey will be able to answer it first. | [Berymuch](https://www.twitch.tv/Berymuch)
Quotes | 🟥 | 🟥 | This action consolidates all three major quote interactions into one switch tree. Using this logic, users are able to leverage the built in quotes system provided by streamerbot to add, delete, and display random or specific quotes that have been stored. Editing quotes is more easily done through the built in quote manager and thus a command to do so has not been implemented. | [Berymuch](https://www.twitch.tv/Berymuch) & [ItzApix_](https://www.twitch.tv/ItzApix_)
Sub-Enhanced Commands | 🟩 | 🟩 | This action contains 5 seperate sub-enhanced commands organized under a single switch tree, and also includes functionality when non-subbed accounts try to use the commands. They also provide informative feedback in the case of improper entry and poroduce various onscreen GFX and SFX. | [Berymuch](https://www.twitch.tv/Berymuch)
User Auto-translate | 🟥 | 🟥 | If enabled, will autopmatically detect and translate non-english chat messages. This tends to be very reactive and thus is disabled by default as common slang and internet shorthand will cause it to go off when not required. | [rez1dev](https://ko-fi.com/s/60e0aab91d)
User Auto-translate File & Command | 🟥 | 🟥 | Placeholder | [rez1dev](https://ko-fi.com/s/60e0aab91d)
User Translate v2.1 | 🟥 | 🟥 | placeholder | [rez1dev](https://ko-fi.com/s/60e0aab91d)
Weather | 🟩 | 🟥 | Controls toggling visibility fo the weather overlay I've set up in my OBS. If you would like to use a similar weather function, please refer to [this website](https://obsproject.com/forum/resources/current-live-weather-and-time-overlay.1605/) in order to get it running. | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="Chat-Commands"></a>
## Deathcounter

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Deathcounter | 🟩 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-(re)Set without changing total | 🟥 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-Add | 🟩 | 🟩 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-Rem | 🟥 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-Reset-Total-Deaths | 🟥 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-Set | 🟥 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="Moderator-Commands"></a>
## Moderator Commands

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Alert | 🟩 | 🟩 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Ban User | 🟥 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Gold Stars | 🟩 | 🟩 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Redeem Cost Modifier | 🟥 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Swear Jar | 🟩 | 🟩 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="Mustached_Maniac-ChatGPT"></a>
## Mustached_Maniac ChatGPT

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
_ChatGPT Set-Up UI_ | 🟥 | 🟥 | Placeholder | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Answers v2 | 🟥 | 🟩 | Placeholder | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Random Messaging v2 | 🟥 | 🟩 | Placeholder | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Recall Behavior | 🟥 | 🟥 | Placeholder | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Set Bot Behavior | 🟥 | 🟥 | Placeholder | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Shoutouts v2 | 🟥 | 🟥 | Placeholder | [mustached_maniac](https://www.twitch.tv/mustached_maniac)

***

<a name="Passive-OBS-Interactions"></a>
## Passive OBS Interactions

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :---: | :---:
Now Playing Enabler/Disabler | 🟩 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Onscreen Clock | 🟩 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Orb Present User Image Cycler | 🟩 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Random Bot Chat Messages | 🟩 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Scene Switch (Streamdeck) | 🟥 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Stream Duration Timer | 🟩 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Stream Labels Cycler | 🟩 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Team Member Advertisement | 🟩 | 🟥 | Placeholder | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="PiShock---Twitch-Interactions"></a>
## PiShock - Twitch Interactions

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
PiShock Information | 🟥 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Random Events | 🟥 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Shock Events | 🟥 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Vibrate Events | 🟥 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="PiShock-V2---Core"></a>
## PiShock V2 - Core

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
!!PiShock Code | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
!PiShock Setup | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock ConfigForm | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock LoginForm | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock ShareCodeForm | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)

***

<a name="PiShock-V2---Examples"></a>
## PiShock V2 - Examples

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
PiShock - Climbing Shock | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock - Generic Shock | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock - Operation Roulette | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock - Pre-vibrate Shock | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)

***

<a name="PiShock-V2---Operations"></a>
## PiShock V2 - Operations

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
PiShock Operate | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock OperateBeep | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock OperateShock | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock OperateVibrate | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)

***

<a name="Redeems"></a>
## Redeems

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Nut Commands | 🟥 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Redeem TTS Bot Source Visibility | 🟥 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Run an Ad | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Tummy Timeout & Vore | 🟥 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
VIP Nut Redemption | 🟥 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Za Warudo Screenshot VTuber | 🟩 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Za Warudo! | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="Spinning-Prize-Wheel"></a>
## Spinning Prize Wheel

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Spinning Prize Wheel 0. Code | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel 1. Settings | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel 2. Import | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Send Group Data | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Winner | 🟩 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)

***

<a name="Spinning-Prize-Wheel---Custom"></a>
## Spinning Prize Wheel - Custom

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Spinning Prize Wheel 0. Spin (Custom) | 🟩 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Add Custom Entry | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Clear Custom Entries | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Remove Custom Entry | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)

***

<a name="Spinning-Prize-Wheel---User-Group"></a>
## Spinning Prize Wheel - User Group

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Spinning Prize Wheel 0. Spin (User Group) | 🟩 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Clear Entries | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Clear Winners | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Command Add User to Group | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Command Remove User from Group | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Entries Close | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Entries Open | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Winner Announce | 🟩 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)
Spinning Prize Wheel Winner Claim | 🟥 | 🟥 | placeholder | [Rondhi](https://extensions.streamer.bot/t/spinning-prize-wheel-update/1957)

***

<a name="Twitch-interactions"></a>
## Twitch Interactions

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Ads | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Ads Timer | 🟩 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Channel | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch) & [Luposity](https://www.twitch.tv/luposity)
Channel Goal | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Charity | placeholder | placeholder | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Chat | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Connections | 🟩 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Donations | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
General | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch), [Liminality](https://www.twitch.tv/liminality), & [ItzApix_](https://www.twitch.tv/ItzApix_)
Guest Star | 🟥 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Hype Train | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch) & [Luposity](https://www.twitch.tv/luposity)
Moderation | 🟥 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Poll | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Power-up | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Prediction | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch) & [ItzApix_](https://www.twitch.tv/ItzApix_)
Raid | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Shared Chat | 🟥 | 🟥 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch)
Subscriptions | 🟩 | 🟩 | placeholder | [Berymuch](https://www.twitch.tv/Berymuch) & [ItzApix_](https://www.twitch.tv/ItzApix_)
Pyramid Core | 🟩 | 🟩 | placeholder |  [ItzApix_](https://www.twitch.tv/ItzApix_) & [Berymuch](https://www.twitch.tv/Berymuch)
Pyramid Writeline | 🟥 | 🟥 | placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)
Watch Streak Core | 🟩 | 🟩 | placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_) & [Berymuch](https://www.twitch.tv/Berymuch)
Watch Streak Writeline | 🟥 | 🟥 | placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)

***

<a name="𝘼𝙋𝙄𝙓-Logging"></a>
## 𝘼𝙋𝙄𝙓 Logging

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
𝘼𝙋𝙄𝙓 Logging Core | 🟥 | 🟥 | placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)
𝘼𝙋𝙄𝙓 Logging Debug | 🟥 | 🟥 | placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)
𝘼𝙋𝙄𝙓 Logging Intake | 🟥 | 🟥 | placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)
𝘼𝙋𝙄𝙓 Logging Setup | 🟥 | 🟥 | placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)
𝘼𝙋𝙄𝙓 Logging Writeline | 🟥 | 🟥 | placeholder | [ItzApix_](https://www.twitch.tv/ItzApix_)
