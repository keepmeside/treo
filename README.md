# KarutaSniper
A bot to automate collecting cards for the discord game Karuta


# Stuff in readme

1. [Known Issues](#known-issues)
2. [Installation](#installation)
3. [Use](#how-use)
4. [Changelog](#changelog)
5. [Todo](#todo)
6. [Credits](#credits)
7. [Disclaimer](#disclaimer)

## Known Issues

- Clicking on buttons returns error 400


## Installation

1. Download repo
2. Install requirements
3. Install [discord.py-self](https://github.com/dolfies/discord.py-self) from repo (you need version 2 or higher)
4. Install pytesseract (and add to path)

## How use

Run main.py, Characters and Animes to snipe are in keywords

## Changelog

### b0.1
- added ocr
- added levenshtein
- attempted to fix reacting at the right moment

### b0.2
- added reporting to console if grabbing the card was successful
- improved levenshtein for less falses
- added more debug info
- added more supported ocr characters

### b0.2.1
- added timestamps

### b0.3
- added cooldown support
- removed useless try statement

### b0.3.1
- fixed cooldowns to not break everything

### b0.3.2
- fixed triple reactions

### b0.3.3
- fixed typo
- fixed stackoverflow error
- fixed reactions not working due to me being stupid
- fixed cooldowns being longer than it should be

### b0.3.4
- Bugfix: the obtained card in the console will now be what was obtained

### b0.3.5
- added obtaining cards to log

### b0.3.6
- added more configurability
- began adding integration for 4 card drops

### b0.3.7
- Hotfix: fixed float and str incompatibilities
- Hotfix: fixed variable name issue

### b0.3.8
- Hotfix: fixed logs causing errors

### b0.4
- made ui better
- token finder if no token detected
- better title
- partial stats (not permanent)

### b0.4.1
- fixed stuff not working
- fixed stats
- added more config stuff

### b0.4.2
- the logo thing is now centered

### b0.4.3
- added update checking (can be disabled in config)

### v1.0
- made ocr work a lot better (hopefully)
- a lot of changes to readme file

### v1.0.1
- added blacklist
- added updating card lists without needing to restart

### v1.1
- added support for card drops with 4 cards (idk why it took so long)
- added auto dropping cards

### v1.1.1

- Hotfix: forgot to activate the autodrop &#128128;

### v1.2

- added support for buttons

### b1.2.1

- Added debug stuff
- turning timestamp off will turn it off on the log now
- fixed newlines not getting removed


## TODO

- support for bots similar to karuta (like SOFI); this might never happen/take a long time to be implemented
- improve stuff

## Credits

- [RiccardoLunardi](https://github.com/riccardolunardi/KarutaBotHack) for the code written in ocr.py

## Disclaimer

This is for educational purposes only blah blah blah, I don't condone breaking discord's TOS or karuta's, it is not my fault if you get banned from karuta or discord.
