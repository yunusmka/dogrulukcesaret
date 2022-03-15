
----

<div align="center">
  <img src="https://github.com/AkinYoungSoftware/TgEglenceBot/raw/master/logo.png" width="300" height="300">
  <h1>Telegram Doğruluk mu? Cesaret mi? Oyun Botu</h1>
</div>
<p align="center">
        <a href="https://telegram.dog/TgEglence_Bot">~Bot~</a>
</p>

----

# Bot Hakkında
**Pyrogram Bot Api Kullanılarak yazılmış basit telegram doğruluk mu? cesaret mi? oyun botu!**

# Heroku'da Clonlamak

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/yunusmka/dogrulukcesaret)

## Alanları Doldurma
* ``BOT_TOKEN``:5103541089:AAH77obZwMXGQeo_LLbFfVYEy-DSx-1Wi4Q!
* ``OWNER_API_ID``:14672969!
* ``OWNER_API_HASH``:67819474b2c4ee77b04e8ec490ad5703!


# Örnek Start Komutu
```python
from pyrogram import Client, filters

K_G = Client(
    "Pyrogram Bot",
    bot_token=YOUR_BOT_TOKEN,
    api_id=YOUR_API_ID,
    api_hash=YOUR_API_HASH
    )

@K_G.on_message(filters.command("start"))
async def _(client, message):
    await message.reply_text(text="Merhaba")
```

# İletişim
Şikayet, bağış v.b. için benim ile telegram'dan iletişime geç [@YoungSoftware](https://t.me/YoungSoftware)


# Credit
Thanks for;

[Akın](https://github.com/AkinYoungSoftware)

[Dan](https://telegram.dog/haskell) [Pyrogram Library](https://github.com/pyrogram/pyrogram) Kütüphanesi için
