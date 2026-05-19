🟥 Note 🟥

Some actions rely on specific scenes/filters/sources to be present in OBS to function- these aspects of this bot will not work after following the above installation procedure but can be modified to suit your needs. Eventually a method will be provided to autopopulate OBS sources once the bot progresses further along the developmental roadmap.

Follow and add the sources according to the layout below in order to activate further core features of the bot in OBS. Ideally you will source mirror this scene wherever you need to use it in your setup.

# OBS Scene name: Twitch Elements

Group Name: **Audio Sources**

	Streamerbot (Application Audio Capture)
	
		This source will capture audio from the built-in SFX the bot includes, if enabled (optional)
	
Group Name: **Web apps & Browser Overlays**

	Shoutout Clips (Scene)
	
		This source will host a mirror of the Shoutout Clips scene below and will display clips when you shout someone out with the !shoutout command (optional)
	
	Prediction & Poll Overlay (Browser Source)
	
		This source will display the Twitch Webpage showing Prediction and Poll results
	
	Goal Overlay (Browser Source)
	
		This source will display the Twitch webpage showing Goal progress
	
Group Name: **General Overlay FX**

	Status Text (GDI+ Text Source)
	
		This source will display text intended to be used as a display for a Starting Soon, Be Right Back, and Ending status message
	
	Now Playing Title (GDI+ Text Source)
	
		This source will display the current stream title
	
	Now Playing Text (GDI+ Text Source)
	
		This source will display the current stream category name
		
	Now Playing Icon (Browser Source)
	
		This source will display the current stream category boxart
	
	User Profile Name (GDI+ Text Source)
	
		This source is intended to be used as a banner text for various types of information and API event confirmations (the source name is misleading and the source will be renamed in the future)
	
	Teammate Name (GDI+ Text Source)
	
		This source will display the name of a randomly chosen stream team member
	
	Fetch Team Member Image (Browser Source)
	
		This source will display the profile picture of the same randomly chosen team member and is also used for a few other functions attached to the User Profile Name source above (the source name is misleading and the source will be renamed in the future)
	
	Noclip shoutout image (Browser Source)
	
		This source is meant to accent clip shoutouts with an additional profile picture (the source name is misleading and the source will be renamed in the future)
	
	Noclip shoutout text (GDI+ Text Source)
	
		This source is used when users include a message along with various API events (the source name is misleading and the source will be renamed in the future)
	
	Death Display (GDI+ Text Source)
	
		This source is used to display death count information
		
	Ad Timer (GDI+ Text Source)
	
		This source is used to display the current time as well as the ad timer countdown
		
Group Name: **Stream Labels**

	Stream Labels User PFP (Browser source)
	
		This source displays the profile picture of the latest username in the current label category
	
	Label Username (GDI+ Text source)
	
		This source displays the latest username currently active in the current label category
	
	Label Title (GDI+ Text source)
	
		This source displays the name of the current label category
	
	Label Icon (Image source)
	
		This source displays the icon associated with the current label category
		
# OBS Scene name: Shoutout Clips

	Shoutout Clip Player (Browser Source)
	
		This source hosts clips played when using the !shoutout command to shout people out
