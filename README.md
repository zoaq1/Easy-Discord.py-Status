# Easy-Discord.py-Status
Easy way to have Creative and Unique Statuses for your Discord.py bot.

# Basic
### Idle
```
await client.change_presence(status=discord.Status.idle)
```
### Do Not Disturb
```
await client.change_presence(status=discord.Status.dnd)
```
# Advanced
### Server Count
```
await client.change_presence(status=discord.Status.do_not_disturb, activity=discord.Activity(type=discord.ActivityType.playing, name=f'Online in {len(client.guilds)} Servers'))
```
![image](https://user-images.githubusercontent.com/93454464/152406794-fc62d3f2-25e4-4666-a81d-381b55186f18.png)

### Streaming With Any Twitch Channel
```
await client.change_presence(status=discord.Status.do_not_disturb,activity=discord.Streaming(name="Coding", url="https://twitch.tv/xqcow"))
```
![image](https://user-images.githubusercontent.com/93454464/152407269-7c32de17-6d9a-4238-b200-2eb9cda9de4c.png)
![image](https://user-images.githubusercontent.com/93454464/152407265-92321e30-97e2-4104-bfa4-7705098fc54f.png)

### Listening to Music
```
await client.change_presence(status=discord.Status.do_not_disturb, activity=discord.Activity(type=discord.ActivityType.listening, name='In The Car (ft. Lil Tracy)'))
```
![image](https://user-images.githubusercontent.com/93454464/152407474-62a6e159-6c3e-4859-824d-937cc412f922.png)

### Playing a Game
```
await client.change_presence(status=discord.Status.do_not_disturb, activity=discord.Activity(type=discord.ActivityType.playing, name='Visual Studio'))
```
![image](https://user-images.githubusercontent.com/93454464/152408660-73364c52-9c8b-41c8-8cf8-36c7dc4b140e.png)

### Competing in a Game
```
await client.change_presence(status=discord.Status.do_not_disturb, activity=discord.Activity(type=discord.ActivityType.competing, name='idk what this is'))
```
![image](https://user-images.githubusercontent.com/93454464/152408810-6ae6a805-e2e5-44e1-b10f-5693d75294f5.png)

### Watching a Video
```
await client.change_presence(status=discord.Status.do_not_disturb, activity=discord.Activity(type=discord.ActivityType.watching, name='you.'))
```
![image](https://user-images.githubusercontent.com/93454464/152409020-7f1e7863-5a68-49cf-a6d8-966712d622ba.png)

# Extreme
### Changing Status
```
status = cycle(["m!help", "anything", "add as many as u want", ""])

@tasks.loop(seconds=5)
async def changeStatus():
    await client.change_presence(status=discord.Status.do_not_disturb, activity=discord.Activity(type=discord.ActivityType.playing, name=next(status)))
```

# Issues:

* Please open and Issue for Help.

