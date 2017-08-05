# kanjiquizbot
Kanji Quiz Bot for Discord written in Go

Quiz data is stored in .json files inside the quizzes folder. The format used is:
```
[
	{"Word":"瑰麗", "Reading":"かいれい"},
	{"Word":"烏鵲", "Reading":"うじゃく"}
]
```

Use this URL to invite your bot to a server:  
https://discordapp.com/oauth2/authorize?scope=bot&client_id=BOT_CLIENT_ID_GOES_HERE  
after creating an app with the [Discord API](https://discordapp.com/developers/docs/intro).

Uses the [DiscordGo](https://github.com/bwmarrin/discordgo) project for API bindings and whatnot, and [Golang Freetype](https://github.com/golang/freetype) to draw fonts on an image.
