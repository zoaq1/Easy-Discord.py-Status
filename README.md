# Easy-Discord.py-Status
Easy way to have Creative and Unique Statuses for your Discord.py bot.

### Server Count
```
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.playing, name=f'Online in {len(client.guilds)} Servers'))
```
![image](https://user-images.githubusercontent.com/93454464/152406794-fc62d3f2-25e4-4666-a81d-381b55186f18.png)

### Streaming With Any Twitch Channel
```
await client.change_presence(activity=discord.Streaming(name="Coding", url="https://github.com/zoaq1"))
```
![image](https://user-images.githubusercontent.com/93454464/152407193-db507717-4ce3-4fbd-9950-98b4a151547e.png)
