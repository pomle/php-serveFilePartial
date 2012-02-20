PHP function for sending partial content
==============================
Useful for secure streaming of audio or video when you don't have access to webserver file sending


Usage Example
---------------
	<?
	serveFilePartial('/home/pomle/Track.oga', 'Pomle - Sing the Blues.oga', 'audio/ogg');