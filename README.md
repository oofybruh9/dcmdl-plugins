# `dcmdl-plugins`
the official dcmdl plugin repo  
this is where` DCMDL` fetches plugin info and downloads the respective python file

## contributing to a plugin
cool, you want to enhance `dcmdl` with new downloaders or helpful features

to do that, just develop a plugin, host it somewhere (e.g. website, github, pastebin, etc.), and write a .json in the `plugins/` folder.

### sample `plugins/plugin.json` file
```json
{
    "title":"<plugin title>",
	"description":"<description>",
	"author":"<your name>",
	"version":"<use any version type, preferrably semver>",
	"download":"<main download>",
	# you do not have to add mirrors, but preferrably do so (2 mirrors max)
	"download-mirror2":"<mirror 1 download>",
	"download-mirror3":"<mirror 2 download>",
}
```
all code (other than plugins not developed by oofybruh9) are licenced under GPLv3 :P
