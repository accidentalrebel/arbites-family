## Documentation is none-existent, please bear with me


Yep, this is mostly a personal project and you are free to look around and take what you want, but please note that there is no documentation for this project at all and most pull requests will probably be ignored.

Yes, I am aware of the spaghetti code going on inside, I wrote the entirety of the core code in 18 hours, bear with me, I'll refactor them *someday*.

Do note the projects above are as follows:

* Arbites4: Outdated testing use layout uploader
* ArbitesR: Outdated Arbites software based on Winforms
* ArbitesEto: Up to date and working software based on Eto.Forms + Mono, runs smoothly in windows, linux, and mac.

## To install Arbites, follow the instructions below

For UNIX platforms that support .deb packages, run the following commands:

First, we will install mono-complete from apt:

```
sudo apt-get install mono-complete
```

Then we could install the .deb package for arbites:

```
URL='http://raw.githubusercontent.com/blahlicus/arbites-family/master/release/Deb/arbites_1.2-0.deb'; FILE=`mktemp`; wget "$URL" -qO $FILE && sudo dpkg -i $FILE; rm $FILE
```
