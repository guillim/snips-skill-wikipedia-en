## Snips-Wikipeda

A skill for the [Snips voice platform](http://snips.ai) to get the information from Wikipedia in English.

#### Limitations

Snips ASR is not able to capture arbitrary slot values. When using Snips ASR all searchable items must be
pre-defined. This is almost impossible for systems like Wikipedia. This may work in theory with injection,
but that means loading many thousands of terms (searchable items) into the skill.

## Installation

```
sam install skills --git https://github.com/guillim/snips-skill-wikipedia-en.git
```

## Usage

### CrystalMethod:searchWikipedia

#### English Assistant

* *"What do you know about __James Bond__?"*
* *"I wanna hear about __World War II__."*
* *"What is called a __disease__?"*
* *"Can you tell me something about the __polar lights__?"*
* *"Define __universe__."*
* *"I would like to know about the __grizzly__."*

## Credits
Credits go to  
[MyCroft Wiki](https://github.com/mycroftai/skill-wiki/tree/master)  
[snips.ai](https://gitlab.smb-tec.com/snips.ai/skills/snips-wikipedia)  
