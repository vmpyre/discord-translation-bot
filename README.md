# Discord Translation Bot
A very basic discord bot that translates a message to the desired language based on the type of reaction emoji used. For example, reacting to a message with the 'France' flag emoji would translate the message to French from any other language.

Note: We are utilizing the [google-trans-new](https://pypi.org/project/google-trans-new/) python library here. Follow the instructions below for Installation and Usage.

## Installation
1. Install both **discord.py** and **google-trans-new** package:
```python
pip install discord.py
pip install google-trans-new
```

2. Replace the **BOT_TOKEN_HERE** string with the actual discord bot token in the [translator.py](https://github.com/moomar0505/usr-discord-translation-bot/blob/main/translator.py) file.
```python
token = "BOT_TOKEN_HERE"
```
3. Run the bot:
```python
python translator.py
```

## Usage
React to a message with the desired flag emoji to translate the message to the appropriate language. *Only French, Spanish and English supported as of 03/08/2021.*
&nbsp;
![alt text](https://github.com/moomar0505/usr-discord-translation-bot/blob/main/usage_image.JPG)

## Contributing
Pull requests are welcome. 

Please help enhance the code to add more languages since only French, English, and Spanish are supported as of yet. 

## License
[MIT](https://choosealicense.com/licenses/mit/)
