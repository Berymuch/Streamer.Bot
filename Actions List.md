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
User Auto-translate File & Command | 🟥 | 🟥 | Core translation action. This action is required in order to allow other associated translation actions to function as intended. Supports word/term filtering via the !add, !remove, !list, & !clear commands. | [rez1dev](https://ko-fi.com/s/60e0aab91d)
User Translate v2.1 | 🟥 | 🟥 | Calls the User Auto-translate File & Command action to query Google's API and translate a specified string of text via the '!en' command. | [rez1dev](https://ko-fi.com/s/60e0aab91d)
Weather | 🟩 | 🟥 | Controls toggling visibility of the weather overlay I've set up in my OBS. If you would like to use a similar weather function, please refer to [this website](https://obsproject.com/forum/resources/current-live-weather-and-time-overlay.1605/) in order to get it running. | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="Chat-Commands"></a>
## Deathcounter

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Deathcounter | 🟩 | 🟥 | Lists deaths for current streaming category as well as returning total global death count using the !deaths command. | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-(re)Set without changing total | 🟥 | 🟥 | Resets deaths for the current streaming category without resetting total global death count using the !deathsreset command. | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-Add | 🟩 | 🟩 | Increments deaths by 1 for the current streaming category using the !death, !deaths+, or !d command. | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-Rem | 🟥 | 🟥 | Decrements deaths by 1 for the current streaming category using the !deaths-. | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-Reset-Total-Deaths | 🟥 | 🟥 | Resets total gloabl deaths across every single streaming category using the !deathsresettotal command. | [Berymuch](https://www.twitch.tv/Berymuch)
Deathcounter-Set | 🟥 | 🟥 | Sets the death count for the current stream category to the specified amount using the !deathsset [amount] command. | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="Moderator-Commands"></a>
## Moderator Commands

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Alert | 🟩 | 🟩 | Plays a SFX and sends a message via websocket to VNyan to toggle a prop and get the streamer's attention using the !alert or !a command. The !alertoff & !ao commands can be used to disable the effect. | [Berymuch](https://www.twitch.tv/Berymuch)
Ban User | 🟥 | 🟥 | Sends a message to chat confirming that a user was banned successfully and activates further logic to support that in VNyan. | [Berymuch](https://www.twitch.tv/Berymuch)
Gold Stars | 🟩 | 🟩 | Increments variable storing amount of user specified gold stars by 1 using the !givegoldstar or !ggs command. You can also decrement gold stars by 1 using the !removegoldstar or !rgs command, and check total gold stars you currently own using the !checkgoldstars or !cgs command.| [Berymuch](https://www.twitch.tv/Berymuch)
Redeem Cost Modifier | 🟥 | 🟥 | Dynamically increases the costs of specified channel redeems using the !chillstream and !chill commands. Using the command again returns costs to their default value. | [Berymuch](https://www.twitch.tv/Berymuch)
Swear Jar | 🟩 | 🟩 | Increments a global "swearjar" variable by 10 or as a 10 times multiple of a specified value using the !swearjar [multiple] or !sj [multiple] commands (the multiple can also be blank or zero). The current searjar variable value can be rests using the !resetswearjar or !rsj commands, and the current as well as total lifetime amount of value put into the jar can be seen using the !checkswearjar or !csj command. | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="Mustached_Maniac-ChatGPT"></a>
## Mustached_Maniac ChatGPT

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
_ChatGPT Set-Up UI_ | 🟥 | 🟥 | Initializes setup for ChatGPT functions and integration. | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Answers v2 | 🟥 | 🟩 | Controls the ability of the chatbot to reply to user input as directed via the ChatGPT servers and your personal API key. | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Random Messaging v2 | 🟥 | 🟩 | Controls the random message response function of the ChatGPT bot. By default during setup, a probability of a 1-100% chance for the bot to reply to any message can be set. Unfortunately, this was still far too common- additional logic has been added to cut that chance down further by a factor of 10. | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Recall Behavior | 🟥 | 🟥 | Controls how the bot accesses and stores the personality blueprint applied to it during setup. | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Set Bot Behavior | 🟥 | 🟥 | Controls how the bot's personality blueprint is stored and set. | [mustached_maniac](https://www.twitch.tv/mustached_maniac)
ChatGPT Shoutouts v2 | 🟥 | 🟥 | Allows the usage of ChatGPT to deliver user targetted twitch shoutouts via the !gptso command. | [mustached_maniac](https://www.twitch.tv/mustached_maniac)

***

<a name="Passive-OBS-Interactions"></a>
## Passive OBS Interactions

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Now Playing Enabler/Disabler | 🟩 | 🟥 | Controls the visibility of sources displaying info about the currently streamed category, and determines when and when not to make them visible based off of currently active OBS scenes, timed actions, streamer bot status, Twitch stream status, and clip shoutout commands. | [Berymuch](https://www.twitch.tv/Berymuch)
Onscreen Clock | 🟩 | 🟥 | Parses system time into the format specified and saves it to the chosen OBS GDI+ text source. | [Berymuch](https://www.twitch.tv/Berymuch)
Orb Present User Image Cycler | 🟩 | 🟥 | Controls the appearance of a "chat orb". Every 30 seconds, a random present user is chosen and has their profile pic and preferred twitch colour queried. If no preferred colour is specified, a random one is chosen. The resulting colour value is then applied to an OBS Colour Source intended to be referenced as an accent value for other sources on the stream. | [Berymuch](https://www.twitch.tv/Berymuch)
Random Bot Chat Messages | 🟩 | 🟥 | Randomly selects and sends a "tip" chat message that showcases an aspect of the stream. Frequency by default is once every 20 minutes and if 75 messages have been sent (both have to be true) in chat since the last randomized message was run. | [Berymuch](https://www.twitch.tv/Berymuch)
Scene Switch (Streamdeck) | 🟥 | 🟥 | Controls behavior of Elgato StreamDeck button presses based off of stored arguments in streamerbot. Using the streamerbot plugin for the streamdeck, this action determines which value the %sceneStatus% and %sceneStatusEnding% arguments are set to by the button press on the stream deck side. This action is then activated and, using a combination of those arguments and the state of the streamdeck button switch, responds accordingly. Values by default are associated with 1 being tied to a "starting" button, 2 with a "brb" button, and 3 with a "ending" button. | [Berymuch](https://www.twitch.tv/Berymuch)
Stream Duration Timer | 🟩 | 🟥 | Every minute, this action increments a global temp variable by one. This value is then used to calculate total time streamed. | [Berymuch](https://www.twitch.tv/Berymuch)
Stream Labels Cycler | 🟩 | 🟥 | Controls the current state of the stream labels sources/group. By default, it will rotate every 12 seconds between showing the latest Follower, Subscriber, Bits giver, Donation, Raid, & Watchstreak along with the associated username and profile picture. | [Berymuch](https://www.twitch.tv/Berymuch)
Team Member Advertisement | 🟩 | 🟥 | Controls the dispay of a randomly selected stream team meber as specified by the execude code command. By default, it is configured to use my stream team  "Go Beyond" and its members and activate every 25 minutes. | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="PiShock---Twitch-Interactions"></a>
## PiShock - Twitch Interactions

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
PiShock Information | 🟥 | 🟥 | Controls sending a message to chat about configured PiShock parameters. | [Berymuch](https://www.twitch.tv/Berymuch)
Random Events | 🟥 | 🟥 | Controls how the PiShock is randomized when triggered by the specified channel point redeem. | [Berymuch](https://www.twitch.tv/Berymuch)
Shock Events | 🟥 | 🟥 | Controls how the PiShock functions for shock events. | [Berymuch](https://www.twitch.tv/Berymuch)
Vibrate Events | 🟥 | 🟥 | Controls how the PiShock functions for vibrate events. | [Berymuch](https://www.twitch.tv/Berymuch)

***

<a name="PiShock-V2---Core"></a>
## PiShock V2 - Core

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
!!PiShock Code | 🟥 | 🟥 | Contains the core C# logic that runs the streamerbot PiShock integrations. The other actions in this group call back to this one. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
!PiShock Setup | 🟥 | 🟥 | Controls setup parameters for the streamerbot PiShock integrations. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock ConfigForm | 🟥 | 🟥 | Controls saved configuration for the streamerbot PiShock integrations. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock LoginForm | 🟥 | 🟥 | Controls saved login information for the PiShock service and API. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock ShareCodeForm | 🟥 | 🟥 | placeholder | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)

***

<a name="PiShock-V2---Examples"></a>
## PiShock V2 - Examples

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
PiShock - Climbing Shock | 🟥 | 🟥 | Contains an example setup for a climbing shock PiShock event. This will gradually increase the intensity of the shock. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock - Generic Shock | 🟥 | 🟥 | Contains an example setup for a generic shock PiShock event.  | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock - Operation Roulette | 🟥 | 🟥 | Contains an example setup for a operation roulette PiShock event.  | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock - Pre-vibrate Shock | 🟥 | 🟥 | Contains an example setup for a pre-vibrate PiShock event.  | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)

***

<a name="PiShock-V2---Operations"></a>
## PiShock V2 - Operations

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
PiShock Operate | 🟥 | 🟥 | Controls which type of operation is triggered when a PiShock event is activated. This will activate other actions according to the input it recieves. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock OperateBeep | 🟥 | 🟥 | Triggers to activate a Beep event on the PiShock. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock OperateShock | 🟥 | 🟥 | Triggers to activate a Shock event on the PiShock. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)
PiShock OperateVibrate | 🟥 | 🟥 | Triggers to activate a Vibrate event on the PiShock. | [mxpuffin](https://mxpuffin.itch.io/streamerbot-pishock-plugin-v2)

***

<a name="Redeems"></a>
## Redeems

Action | GFX | SFX | Description | Credit
:--- | :---: | :---: | :--- | :---:
Nut Commands | 🟥 | 🟩 | Contains logic that helps to run certain Nut commands. Currently this only contains the logic that lets !nut 2002 function due to limitations in VNyan. All other nuts function solely via nodegraphs in VNyan, and in the event that future nuts require additional logic in streamerbot this action will serve as the container for those cases. | [Berymuch](https://www.twitch.tv/Berymuch)
Redeem TTS Bot Source Visibility | 🟥 | 🟥 | Controls interactions that modify the visual state of a TTS bot using the specified OBS sources. | [Berymuch](https://www.twitch.tv/Berymuch)
Run an Ad | 🟩 | 🟩 | Controls how an ad is run when the specified channel point redeem is used. | [Berymuch](https://www.twitch.tv/Berymuch)
Tummy Timeout & Vore | 🟥 | 🟩 | Controls how data is queried from twitch targetting the specified user and in response to external input for the Tummy Timeout and Vore redeem/commands. Requires my VNyan logic in order to function, and also requires certain sources to be present and configured in OBS along with the OBS Spout2 plugin. | [Berymuch](https://www.twitch.tv/Berymuch)
VIP Nut Redemption | 🟥 | 🟩 | Controls how VIP status is granted if the user is not a moderator in tandem with the redemption of the VIP Nut redeem. Requires and works in conjunction with my VNyan logic. | [Berymuch](https://www.twitch.tv/Berymuch)
Za Warudo Screenshot VTuber | 🟩 | 🟥 | Controls when a screenshot is taken of the specified OBS source. Works in tandem with and is called by the Za Warudo! action in streamerbot. | [Berymuch](https://www.twitch.tv/Berymuch)
Za Warudo! | 🟩 | 🟩 | Controls how redemption of the Za Warudo redeem disables all channel point redeems, most commands, and other visual effects in OBS. Has a hardcoded 6 minute timer that then reverts those modifications once it resolves. Works in tandem with and requires my VNyan logic to run as intended. | [Berymuch](https://www.twitch.tv/Berymuch)

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
