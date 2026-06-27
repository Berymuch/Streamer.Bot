🟥 Note 🟥

Some actions rely on specific scenes/filters/sources to be present in OBS to function- these aspects of this bot will not work after following the above installation procedure but can be modified to suit your needs. Eventually a method will be provided to autopopulate OBS sources once the bot progresses further along the developmental roadmap.

Follow and add the sources according to the layout below in order to activate further core features of the bot in OBS. Ideally you will source mirror this scene wherever you need to use it in your setup.

# OBS Scene name: Twitch Elements

Group Name: **Audio Sources**
Source Name | Source Type | Function
------ | ------ | ------
Streamerbot | Application Audio Capture | This source will capture audio from the built-in SFX the bot includes as part of certain actions, if enabled (optional)
Squawk Text-to-Speech | [Squawk Text-to-Speech](https://obsproject.com/forum/resources/squawk-real-time-local-text-to-speech-with-ai.1965/) | This source is used to locally generate TTS audio if the plug-in is installed (see link)

Group Name: **Redeem SFX & FX**
Source Name | Source Type | Function
------ | ------ | ------
Za Warudo Countdown | Application Audio Capture | This source will host the countdown timer for the Za Warudo redeem logic provided in the streamerbot import. [Requires the Advanced OBS Timer plug-in](https://obsproject.com/forum/resources/advanced-timer.637/) to be installed and pointed at this source to function as intended (optional)
Za Warudo Screenshot | Media | This source is used display the screenshot taken during the Za Warudo redeem (optional)
Za Warudo Clip | Media | This source is used to play the media file associated with the Za Warudo redeem (optional)

Group Name: **Web apps & Browser Overlays**
Source Name | Source Type | Function
------ | ------ | ------
Fanart Gallery | Scene | This source will host a mirror of the Fanart Gallery scene (you need to make this manually) (optional)
[NS] Spinning Prize Wheel | Scene | This source will host a mirror of the spinning prize wheel scene created once setup in the streamerbot logic (optional)
Shoutout Clips | Scene | This source will host a mirror of the Shoutout Clips scene below and will display clips when you shout someone out with the !shoutout command (optional)
Weather | Browser Source | This source will display the current weather as configured by you using the [weather plugin](https://obsproject.com/forum/resources/current-live-weather-and-time-overlay.1605/) (optional)
Prediction & Poll Overlay | Browser Source | This source will display the Twitch Webpage showing Prediction and Poll results
Goal Overlay | Browser Source | This source will display the Twitch webpage showing Goal progress
Hype Train Progress Bar | Browser Source | This source will display the Twitch webpage showing Goal progress
Emote Display | Browser Source | This source will display the Twitch webpage showing Goal progress
Vore Redeem | Browser Source | This source will display the Twitch PFP targetted by the vore command in streamerbot/vnyan. Requires the [Spout2 plugin](https://github.com/Off-World-Live/obs-spout2-plugin/releases) to function as intended (optional)
Orb Present User Image | Browser Source | This source will display the Twitch PFP for the account currently spotlit by the Orb logic (optional)

Group Name: **Orb Base**
Source Name | Source Type | Function
------ | ------ | ------
Color Orb | Color | This source will host the preferred twitch color, if any, of the user currently chosen by the orb and as determined by my SB logic (optional)
Color Orb BG | Color | This source will host a base colour for the colour chosen by the source above it (optional)

Group Name: **General Overlay FX**
Source Name | Source Type | Function
------ | ------ | ------
Status Text | GDI+ Text Source | This source will display text intended to be used as a display for a Starting Soon, Be Right Back, and Ending status message
Now Playing Title | GDI+ Text Source | This source will display the current stream title
Now Playing Text | GDI+ Text Source | This source will display the current stream category name
Now Playing Icon | Browser Source | This source will display the current stream category boxart
User Profile Name | GDI+ Text Source | This source is intended to be used as a banner text for various types of information and API event confirmations (the source name is misleading and the source will be renamed in the future)
Fetch Team Member Image | Browser Source | This source will display the profile picture of the same randomly chosen team member and is also used for a few other functions attached to the User Profile Name source above (the source name is misleading and the source will be renamed in the future)
Noclip shoutout image | Browser Source | This source is meant to accent clip shoutouts with an additional profile picture (the source name is misleading and the source will be renamed in the future)
Noclip shoutout text | GDI+ Text Source | This source is used when users include a message along with various API events (the source name is misleading and the source will be renamed in the future)

Group Name: **HUD Elements**
Source Name | Source Type | Function
------ | ------ | ------
Teammate Name | GDI+ Text Source | This source will display the name of a randomly chosen stream team member
Ad Timer | GDI+ Text Source | This source is used to display the current time as well as the ad timer countdown
Death Display | GDI+ Text Source | This source is used to display death count information	

Group Name: **Stream Labels**
Source Name | Source Type | Function
------ | ------ | ------
Stream Labels User PFP | Browser source | This source displays the profile picture of the latest username in the current label category and is cycled
Label Username | GDI+ Text source | This source displays the latest username currently active in the current label category and is cycled
Label Title | GDI+ Text source | This source displays the name of the current label category and is cycled
Label Icon | Image source | This source displays the icon associated with the current label category and is cycled
		
# OBS Scene name: Shoutout Clips
Source Name | Source Type | Function
------ | ------ | ------
Shoutout Clip Player | Browser Source | This source hosts clips played when using the !shoutout command to shout people out. Additional setup is also required in the bot setup instructions (optional)

# OBS Scene name: [NS] Spinning Prize Wheel
Source Name | Source Type | Function
------ | ------ | ------
Wheel Winner | Browser Source | This source will display the spinning prize wheel winner (create and add it to OBS via the setup logic in my streamerbot import) (optional)
Wheel Spinner | Browser Source | This source will display the spinning prize wheel (create and add it to OBS via the setup logic in my streamerbot import) (optional)

# OBS Scene name: Fanart Gallery
Source Name | Source Type | Function
------ | ------ | ------
Image Slide Show | Image Slide Show | This source hosts an image gallery fo all the art you'd like to display on your stream (optional)

# OBS Scene name: Watch Streak Leaderboard
Source Name | Source Type | Function
------ | ------ | ------
Image Slide Show | Image Slide Show | This source hosts an image gallery fo all the watchstreak art you'd like to display on your stream (optional)
