# Discord Bot
Basic discord bot developed to be executed on Jupyter Notebook and Google Collab to get you started with running tests. 

**NOTE** 
Although Discord Bot can be coded in python and executed on a terminal easily. Executing the bot on Jupyter notebook (or Google Collab) requires the following extra line:

```
import nest_asyncio 
nest_asyncio.apply()
```
Which can be installed with `!pip install nest_asyncio`.   

### Perquisites 
- [discord.py](https://discordpy.readthedocs.io/en/latest/) 
- nest_asyncio
- [python3](https://www.python.org) and above. 

## Basics
- The server prefix can be set by :
```
client = commands.Bot(command_prefix = "$")
```

- The commands can be initialized by: 
```
async def [command name]() :
```

For more advanced commands check the documentation linked above. 

