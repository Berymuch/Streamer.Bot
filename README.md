# Botymuch (Powered by [Streamer.Bot](https://streamer.bot/))

[Chat Commands List](https://github.com/Berymuch/Streamer.Bot/blob/main/Chat%20Commands%20List.md)  
[Actions List](https://github.com/Berymuch/Streamer.Bot/blob/main/Actions%20List.md)  

***

>*THIS BOT FEATURES COMPLETE TWITCH API INTEGRATION. Youtube/Kick/Trovo integrations are in development.*

> [!NOTE]
> Botymuch v1.4.5 is a major release that reorganizes/consolidates many actions and changes the code hierarchy. This will result in the duplication of some functions if updating from a previous version. Botymuch v1.1.5+ Require Streamer.bot v1.0.0+.

This is a collection of hundreds of actions/commands I've created and collected to support my Twitch channel! It automates various components that I had previously relied on webserver-based bots for, and does so while running entirely locally from your computer. 

**INSTALLATION:**

:red_square: ***ALWAYS*** backup your streamerbot prior to updating :red_square:

1.  Download the latest version and import it into streamer bot by dragging and dropping the text file into the import window or copying and pasting the hash into the import window.

2.  Update write filepaths to your preferred locations in the "CONFIG ME" action at the top of the Twitch Events action group in order to enable Stream/Moderation/Summary event logging.

3.  **OPTIONAL** If you plan to use the built-in SFX features, download and extract the "Streamerbot SFX.zip" archive above and place the resulting folder wherever and update the SFX write filepath in "CONFIG ME (OPTIONAL)" to point to the folders location. The file path should resemble "yourfilepath/Streamerbot SFX". Do not rename/reorganize the contents of the "Streamerbot SFX" folder (it will break things), but do feel free to add files to it as desired.

4.  **OPTIONAL** If you plan to use the built-in Squawk TTS features, update the write filepath to your preferred location in "CONFIG ME (OPTIONAL)". Squawk can be downloaded here: https://obsproject.com/forum/resources/squawk-real-time-local-text-to-speech-with-ai.1965/

Note that some actions rely on specific scenes/filters/sources to be present in OBS to function- these aspects of this bot will not work out of the box but can be modified to suit your needs. Eventually a method will be provided to autopopulate OBS sources once the bot progresses further along the developmental roadmap.

All credit for the streamer bot application goes to its developers.

There is a TON here to document and I haven't done any of it hahaha- stay tuned!
