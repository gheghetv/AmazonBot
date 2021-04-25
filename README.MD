# AmazonBot

🤖Fast and simple bot to transform links from Amazon into a nice post with your referral link in Telegram 🛒

### Prerequisites
* You need Python 3.6 or higher

```
pip3 install requeriments.txt
```

### Setup
In order to setup the bot you need to copy `example_credentials.json` to `credentials.json` in `config/example_credentials.json`.
Then add Bot Token (get it from [@BotFather](https://t.me/Botfather)) and Amazon configuration to the file `credentials.json`

### Running
```
#If you want just run the bot
python3 main.py

# Or maybe run forever in to a VPS in linux
nohup python3 main.py &
```

### Changelog
```
Version 1.0.0
  - Initial Release
```

## Built With
* [python-amazon-paapi](https://github.com/sergioteula/python-amazon-paapi)
* [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)

## License  
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details