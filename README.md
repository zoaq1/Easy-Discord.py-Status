# Easy-Discord.py-Status
Easy way to have Creative and Unique Statuses for your Discord.py bot.

### Idle
```
await client.change_presence(status=discord.Status.idle)
```
### Do Not Disturb
```
await client.change_presence(status=discord.Status.dnd)
```

### Server Count
```
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.playing, name=f'Online in {len(client.guilds)} Servers'))
```
![image](https://user-images.githubusercontent.com/93454464/152406794-fc62d3f2-25e4-4666-a81d-381b55186f18.png)

### Streaming With Any Twitch Channel
```
await client.change_presence(activity=discord.Streaming(name="Coding", url="https://twitch.tv/xqcow"))
```
![image](https://user-images.githubusercontent.com/93454464/152407269-7c32de17-6d9a-4238-b200-2eb9cda9de4c.png)
![image](https://user-images.githubusercontent.com/93454464/152407265-92321e30-97e2-4104-bfa4-7705098fc54f.png)

### Listening to Music
```
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.listening, name='In The Car (ft. Lil Tracy)'))
```
![image](https://user-images.githubusercontent.com/93454464/152407474-62a6e159-6c3e-4859-824d-937cc412f922.png)

# Issues:

* Please open and Issue for Help.

