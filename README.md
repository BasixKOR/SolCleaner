# SolCleaner
mass message cleaner for telegram (inspired by hasol)


## Install dependencies
```
pip install "telethon==0.11.1"
```
or
```
pip3 install telethon "telethon==0.11.1"
```


## Issue Telegram Api Key
https://my.telegram.org/


## Configuration
Open solcleaner.py, and edit these fields:
```
api_id = 12345
api_hash = '12345789abcefg'
phone = '<< place here your phone number (include + and nation code)>> '
```

## Use
1. Run script.
2. If you ran first, You must have enter auth code that is Telegram service sent
3. Enter command what you want to any channels

## Available Commands
### '#솔클리너'
This command cleans all messages you writed, until '#솔클리너포인트'  
After cleaning done, '#솔클리너' message changed to '#솔클리너포인트' for next cleaning.

### '#업데이트확인'
This command checks last update date of webtoon 'DENMA', that published on NAVER WEBTOON.

### TELEGRAM DOES NOT WORK IN CHINA
