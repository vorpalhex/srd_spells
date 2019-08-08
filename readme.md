# Spells from the SRD

This is a JSON formatted list of all the spells from the SRD, automatically pulled from @ephe's very nice [grimoire](https://github.com/jayrab/grimoire) with permission. This list has been both automatically and manually inspected, but is still likely to contain errors.

## General Format of a Spell

```javascript
{
  "name": "Acid Splash",
  "tags": [
    "sorcerer",
    "wizard",
    "cantrip"
  ],
  "type": "Conjuration cantrip",
  "ritual": false,
  "level": "cantrip",
  "school": "Conjuration",
  "casting_time": "1 action",
  "range": "60 feet",
  "components": {
    "verbal": true,
    "somatic": true,
    "material": false,
    "raw": "V, S"
  },
  "duration": "Instantaneous",
  "description": "You hurl a bubble of acid. Choose one creature within range, or choose two creatures within range that are within 5 feet of each other. A target must succeed on a Dexterity saving throw or take 1d6 acid damage.\n\nThis spell's damage increases by 1d6 when you reach 5th level (2d6), 11th level (3d6), and 17th level (4d6)."
}
```

## Formatting notes

The description preserves whitespace in the form of linebreak characters (\n). If you want to display descriptions correctly in html, either wrap the description with `<pre>` tags or replace the \n's with `<br>`.

## List of Tags

```
'sorcerer',
'wizard',
'cantrip',
'ranger',
'level1',
'bard',
'druid',
'cleric',
'warlock',
'paladin',
'cleric (trickery)',
'level3',
'level2',
'level4',
'level8',
'level9',
'level7',
'level5',
'level6'
```

## Users

_If you make use of this repo and would like to be added here, just open a ticket!_

Dungeons and Dragons 5th edition character sheet

### [My Spells](https://github.com/sharpshark28/my_spells)

_SharpShark28_

Web-based application to elegantly view spells and save them to your local spellbook.


## Licensing Bits
__Open Game License v1.0a Copyright 2000, Wizards of the Coast, Inc.__

`spells.json` contains content from the SRD and is restricted and covered by the OGL. You can find the OGL 1.0a at `ogl.html` in this repo, or online [here](http://www.opengamingfoundation.org/ogl.html). When using said data, please make sure to conform appropriately with the proper licenses and whatnot.
