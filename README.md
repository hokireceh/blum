# Blumtod

AUTO CLAIM FOR BLUM / @blum

[Click to read the readme in Indonesian](README_ID.md)

# Table of Contents
- [Blumtod](#blumtod)
- [Table of Contents](#table-of-contents)
- [Warning](#warning)
- [Feature](#feature)
- [Register ?](#register-)
- [How to Use](#how-to-use)
  - [Bot.py parameter feature](#botpy-parameter-feature)
  - [About Config.json](#about-configjson)
  - [About Proxy](#about-proxy)
  - [Windows](#windows)
  - [Linux](#linux)
  - [Termux](#termux)
- [Video Guide to Get Data](#video-guide-to-get-data)
- [Javascript Command to Get Telegram Data for Desktop](#javascript-command-to-get-telegram-data-for-desktop)
- [Run for 24/7](#run-for-247)
- [Discussion](#discussion)
- [Support My Work](#support-my-work)
- [QnA](#qna)
- [Thank you \< 3](#thank-you--3)

# Warning

All risks are borne by the user

# Feature

- [x] Auto Claim
- [x] Auto Claim Daily
- [x] Proxy Support, see [About Proxy](#about-proxy)
- [x] Support Multi Account
- [x] Auto Claim Bonus Referral
- [x] Auto Complete Task, see [About Config.json](#about-configjson)
- [x] Auto Play Game (random input from user), see [About Config.json](#about-configjson)

# Register ?

Click the following url to register : [https://t.me/blum/app?startapp=tribe_ongkang_ongkang-ref_uJdjELBGq1](https://t.me/blum/app?startapp=tribe_ongkang_ongkang-ref_uJdjELBGq1)

# How to Use

## Bot.py parameter feature

Here are some parameters to enable feature

| parameter | description                                    |
| --------- | ---------------------------------------------- |
| --data    | set custom file data input (default: data.txt) |

## About Config.json

Here Config.json Description
| key                | description                                                                                                                                       |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| interval           | value type is integer/real number <br> interval is delay between accounts                                                                         |
| auto_complete_task | value type is bool (true/false), enable (true) to active auto complete task                                                                       |
| auto_play_game     | value type is bool (true/false), enable (true) to active auto play game                                                                           |
| game_point         | value type is integer/real number<br>low : minimum points earned when playing the game <br><br>high : maximal points earned when playing the game |

## About Proxy

Register on this site to get free proxy : [Here](https://www.webshare.io/?referral_code=pdrev4nizc76)

You can add your proxy list in `proxies.txt` and proxy format is like example below :

Format :

```
http://host:port
http://user:pass@host:port
```

Example :

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
socks5://127.0.0.1:6969
socks5://user:pass@127.0.0.1:6969
```

## Windows 

1. Make sure you computer was installed python and git.
   
   Suggestion: Use python version 3.8+ (3.8 and above or latest)

   python site : [https://python.org](https://python.org)
   
   git site : [https://git-scm.com/](https://git-scm.com/)

2. Clone this repository
   ```shell
   git clone https://github.com/hokireceh/blum.git
   ```

3. goto blumtod directory
   ```
   cd blum
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Find Account Token](#how-to-find-account-token). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Linux

1. Make sure you computer was installed python and git.
   
   Suggestion: Use python version 3.8+ (3.8 and above or latest)

   python
   ```shell
   sudo apt install python3 python3-pip
   ```
   git
   ```shell
   sudo apt install git
   ```

2. Clone this repository
   
   ```shell
   git clone https://github.com/hokireceh/blum.git
   ```

3. goto blumtod directory

   ```shell
   cd blum
   ```

4. Install the require library
   
   ```
   python3 -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Find Account Token](#how-to-find-account-token). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Termux

1. Make sure you termux was installed python and git.
   
   python
   ```
   pkg install python
   ```

   git
   ```
   pkg install git
   ```

2. Clone this repository
   ```shell
   git clone https://github.com/hokireceh/blum.git
   ```

3. goto blumtod directory
   ```
   cd blum
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Find Account Token](#how-to-find-account-token). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

# Video Guide to Get Data

The require data is same like [pixelversebot](https://github.com/akasakaid/pixelversebot) so you can watch same tutorial / video guide to get data !

Here : [https://youtu.be/KTZW9A75guI](https://youtu.be/KTZW9A75guI)

# Javascript Command to Get Telegram Data for Desktop

```javascript
copy(Telegram.WebApp.initData)
```

# Run for 24/7 

You can run the script bot for 24/7 using vps / rdp. You can use `screen` application in vps linux to running the script bot in background process
Buy cheap RDP Here : [Sign Up](https://console.idcloudhost.com/referral/1n60rk)

# Follow me
* https://facebook.com/hokireceh.official
* https://instagram.com/hokireceh <br />
  *You can contact me with social media in above*
# Support me

* (Indonesia) 
* (Global/International) https://sociabuzz.com/vania_gemash/tribe
* Ton ```UQBOGHJAp7EXL5WgAw3E2wfOF7HBapd8YyQxU6wa7V1WZD6N```
* Dogs ```UQBOGHJAp7EXL5WgAw3E2wfOF7HBapd8YyQxU6wa7V1WZD6N```
* TRON / USDT (Tron20) ```TChYgcKG6zRwz5FP9UTZrAik3xDPa12M94```

# QnA

Q : Is this bot/program script required to use a proxy?

A : No, this bot/program script is not required to use a proxy.

Q : How can I use a proxy?

A : Simply fill in the proxies.txt file according to the format I have explained.


# Thank you < 3
