# How to upload:


Fork the repo

Create a file called `all/YourAppName/script.osl` and put your osl code there

Create `icon.icn` in the same folder, and add your applications .icn file in there

Create `info.json` and fill out this json

```json
{
  "title": "Your App Name",
  "description": "A description for your application",
  "author": "Your Origin Username",
  "version": "If you update your app later, increment this value",
  "genre": "Pick the genre your app falls into",
  "game_modes": ["Single-player","Multiplayer"],
  "permissions": ["i'll fill these out for you based on your application code"]
}
```

Create a pull request for your app
