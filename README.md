leaderboard
===========
This is a websocket interface to screen scraped leaderboards.

Dependencies
------------

* Front end (cart_console).  This application has no user unterface on its own.
* Mojolicious
* Text to speech application
* Modules/Plugins
 * Mojolicious::Plugin::RenderFile
 * Mojolicious::Plugin::CORS to address same origin policy in browsers
 * Mojolicious::Plugin::ForkCall to do tts non-blocking  
 * File::Temp to create file names for generated tts audio

Note
----
This application has no user iterface on its own.  See cart_console for ui.

