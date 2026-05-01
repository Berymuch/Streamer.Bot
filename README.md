# Botymuch (Powered by [Streamer.Bot](https://streamer.bot/))

[Chat Commands List](https://github.com/Berymuch/Streamer.Bot/blob/main/Chat%20Commands%20List.md)  
[Actions List](https://github.com/Berymuch/Streamer.Bot/blob/main/Actions%20List.md)  

***

>*THIS BOT FEATURES COMPLETE TWITCH API INTEGRATION. Youtube/Kick integrations are in development.*

> [!NOTE]
> Botymuch v1.4.5 is a major release that reorganizes/consolidates many actions and changes the code hierarchy. This will result in the duplication of some functions if updating from a previous version. Botymuch v1.1.5+ Require Streamer.bot v1.0.0+.

This is a collection of hundreds of actions/commands I've created and collected to support my Twitch channel! It automates various components that I had previously relied on webserver-based bots for, and does so while running entirely locally from your computer. 

**INSTALLATION:**

:red_square: ***ALWAYS*** backup your streamerbot prior to updating :red_square:

*/// REQUIRED ///*

1.  Download the latest version of the .sb file and import it into streamer bot by dragging and dropping the text file into the import window or copying and pasting the hash into the import window.

2.  Update write filepaths to your preferred locations in the "CONFIG ME" action at the top of the Twitch Events action group in order to enable Stream/Moderation/Summary event logging.

*/// OPTIONAL ///*

3.  If you plan to use the built-in SFX features, download and extract the "Streamerbot SFX.zip" archive above and place the resulting folder wherever. Update the SFX write filepath in "CONFIG ME (OPTIONAL)" to point to the extracted folder's location. The file path should resemble "yourfilepath/Streamerbot SFX". Do not rename/reorganize the contents of the "Streamerbot SFX" folder (it will break things), but do feel free to add files to it as desired.

4.  If you plan to use the built-in Squawk TTS features, update the write filepath to your preferred location in "CONFIG ME (OPTIONAL)". Squawk can be downloaded here: https://obsproject.com/forum/resources/squawk-real-time-local-text-to-speech-with-ai.1965/

5.  Certain functions of the bot are set to look towards specifically named OBS sources. In order to use them, you must first connect your OBS websocket to streamerbot then [create sources of the type and name provided in the source setup file above](https://github.com/Berymuch/Streamer.Bot/blob/main/Botymuch%20OBS%20source%20setup.txt). A guide on how to connect via the OBS websocket can be found here: https://www.youtube.com/watch?v=u4GWb6NaNsw

6. If you don't already have a local clip shoutout player, download the "shoutouthd.html" file above and follow the setup instructions in "CONFIG ME (OPTIONAL)". You will need to add a new Scene to OBS, and inside of it create a new Browser source. In the browser source properties, Ensure the browser source URL is set to "about:blank" and that "control audio via OBS" and "refresh browser when scene becomes active" are both checked. Credit for this implementation goes out to my buddy [Liminality](https://www.twitch.tv/liminality)!

7. If you would like to use my Elgato Stream Deck layout, download the "Botymuch Streaming Layout.streamDeckProfile" file above and import it into your Elgato Stream Deck under a new profile. You will need to install the free [Discord](https://marketplace.elgato.com/product/discord-e3559f36-d31d-4529-ab1f-739955e2ac7a), [OBS Studio](https://marketplace.elgato.com/product/obs-studio-35615969-830f-45c9-ba0a-1a295bba7fec), [Stream Avatars](https://marketplace.elgato.com/product/stream-avatars-72fb3e4b-4b1d-4d49-882c-adfdff30fc60), [Streamer.bot](https://marketplace.elgato.com/product/streamerbot-5c942a07-4bf6-4207-a2f2-f8599c398f2a), and [Web Requests](https://marketplace.elgato.com/product/web-requests-d7d46868-f9c8-4fa5-b775-ab3b9a7c8add) plugins off the Elgato Marketplace.

Note that some actions rely on specific scenes/filters/transitions/sources to be present in OBS to function- these aspects of this bot will not work out of the box but can be modified to suit your needs. Eventually a method will be provided to autopopulate OBS sources once the bot progresses further along the developmental roadmap.

All credit for the streamer bot application goes to its developers.

There is a TON here to document and I haven't done any of it hahaha- stay tuned!
