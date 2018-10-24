# lazybot

A simple class that can call arbitrary methods and make a request to Telegrams bot api.

## But why ?
While writing my userbot I wanted a easy way to make calls to the bot api without needing a full blown lib with handlers etc..

## Where are the docs ?
Use the [Telegram Docs](https://core.telegram.org/bots/api) and the following example as base.
```
import lazybot
bot = lazybot.Bot('TOKEN')
# you can use snake case
bot.send_message(chat_id=123456, text='Text')

# or camelCase
bot.sendMessage(chat_id=123456, text='Text')

````

## Installation
`pip install lazybot`
