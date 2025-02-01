




## How to reach Me ?
<a href="https://telegram.dog/starky0"><img src="https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=Telegram"></a>
<a href="https://telegram.dog/starkbotss"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>

## COMMANDS
### AVAILABLE COMMANDS 
```
start - check whether bot is alive 
pw - For Physics Wallah..
e1 - For E1 Coaching App..
vidya - For Vidya Bihar App..
ocean - For Ocean Gurukul App..
winners - For The Winners Institute.
rgvikramjeet - For Rgvikramjeet App..
txt - Rojgar with ankit
cp - For classplus app
cw - For careerwill app..
exampur - For exampur app..
khan - Khan Gs app..
down - For Downloading Url lists
forward - To Forward from One 
restart - To restart the bot
```

ADD THIS IN PYROGRAM/FILTERS.PY NEW LINE 253
````
# region edited_filter
async def edited_filter(_, __, m: Message):
    return bool(m.edit_date)


edited = create(edited_filter)
"""Filter edited messages."""


# endregion
````
