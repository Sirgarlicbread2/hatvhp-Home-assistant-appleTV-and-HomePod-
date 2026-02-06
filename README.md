# hatvhp-Home-assistant-appleTV-and-HomePod-
This is documentation on how I got my HomePod minis to pass request back onto home assistant

 The issue, Homekit does not have a good voice remote system intergrated already, so my project fixes this by using the Apple Tv homeassistant intergration as seen here:https://www.home-assistant.io/integrations/apple_tv
 The way I did this was simple, when you look at my scripts there are only 3 currently.
 1: Turn on Bob's Burgers, This uses deeplinks and the remote controll function of the intergration to sucsessfully navigate to the show page on hulu and start playing the show.
 2:Tv off, very simple. turns the apple tv off and the connected tv off via HDMI cec
 3:tv on , same as nuber 2 but turns it on instead of off.
 These are all scripts in homeassistant which are then triggred by the siri shortcut as seen in the shortcut file.
