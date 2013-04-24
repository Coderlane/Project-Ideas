# Updater

## Outline
I want a program to update programs.

## Requirements
* Must check server for updates
* Must validate authenticity of server 
* Must validate authenticity of the update
* Must validate integrity of the update

## Suggestions
* You don't need to write a server program.
	* The server could have a key or something similar
	* Updates could be validated by hash
		* That said, use something better than MD5
* Make it cross platform
* Allow for configuration and customization
* Show download progress
