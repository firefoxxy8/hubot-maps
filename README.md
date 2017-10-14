Hubot Maps
==========
A Hubot script for searching maps and directions via Google

Usage
-----
```
hubot map me <query> - Returns a map view of the area returned by `query`.
hubot directions from <origin> to <destination> - Returns a map and list of directions from origin to destination.
```

Environment Variables
---------------------
Follow the instructions for obtaining an API key here:
https://developers.google.com/maps/documentation/javascript/tutorial#api\_key

Once you have an API key, set it as the value for the HUBOT\_GOOGLE\_API\_KEY environment variable.

Markdown
--------
You can enable Markdown output by setting the environment variable HUBOT\_MAPS\_MARKDOWN to `true`
