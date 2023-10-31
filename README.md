<p align="center">
    <a href="https://github.com/pyrogram1/pyrogram1">
        <img src="https://docs.pyrogram1.org/_static/pyrogram1.png" alt="Pyrogram1" width="128">
    </a>
    <br>
    <b>Telegram MTProto API Framework for Python</b>
    <br>
    <a href="https://docs.pyrogram1.org">
        Documentation
    </a>
    •
    <a href="https://docs.pyrogram1.org/releases">
        Releases
    </a>
    •
    <a href="https://t.me/pyrogram1">
        News
    </a>
</p>
#Powerful
## Pyrogram1

> Elegant, modern and asynchronous Telegram MTProto API framework in Python for users and bots

``` python
from pyrogram1 import Client, filters

app = Client("my_account")


@app.on_message(filters.private)
async def hello(client, message):
    await message.reply("Hello from Pyrogram1!")


app.run()
```

**Pyrogram1** is a modern, elegant and asynchronous [MTProto API](https://docs.pyrogram1.org/topics/mtproto-vs-botapi)
framework. It enables you to easily interact with the main Telegram API through a user account (custom client) or a bot
identity (bot API alternative) using Python.

### Support

If you'd like to support Pyrogram1, you can consider:

- [Become a GitHub sponsor](https://github.com/sponsors/delivrance).
- [Become a LiberaPay patron](https://liberapay.com/delivrance).
- [Become an OpenCollective backer](https://opencollective.com/pyrogram1).

### Key Features

- **Ready**: Install Pyrogram1 with pip and start building your applications right away.
- **Easy**: Makes the Telegram API simple and intuitive, while still allowing advanced usages.
- **Elegant**: Low-level details are abstracted and re-presented in a more convenient way.
- **Fast**: Boosted up by [TgCrypto](https://github.com/pyrogram1/tgcrypto), a high-performance crypto library written in pure C.  
- **Type-hinted**: Types and methods are all type-hinted, enabling excellent editor support.
- **Async**: Fully asynchronous (also usable synchronously if wanted, for convenience).
- **Powerful**: Full access to Telegram's API to execute any official client action and more.

### Installing

``` bash
pip3 install pyrogram1
```

### Resources

- Check out the docs at https://docs.pyrogram1.org to learn more about Pyrogram1, get started right
away and discover more in-depth material for building your client applications.
- Join the official channel at https://t.me/pyrogram1 and stay tuned for news, updates and announcements.
