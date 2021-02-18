# [E X A P U N K S](http://www.zachtronics.com/exapunks/)

- [E X A P U N K S](#e-x-a-p-u-n-k-s)
  - [About the Game](#about-the-game)
  - [About Me](#about-me)
  - [About the Repo](#about-the-repo)
  - [Submissions](#submissions)
  - [EXA Code Guides](#exa-code-guides)

---

## About the Game

**The year is 1997. You used to be a hacker, but now you have the phage. You made a deal: one hack, one dose. There’s nothing left to lose… except your life.**

`EXAPUNKS` is the latest open-ended puzzle game from Zachtronics, the creators of Opus Magnum, SHENZHEN I/O, TIS-100, and more.

![Exapunks Banner](exa.jpg)

- **READ ZINES** - Learn to hack from `TRASH WORLD NEWS`, the underground computer magazine. Tutorials, hacking tips, secret information, searing commentary—  `TRASH WORLD NEWS` has you covered.
- **WRITE VIRUSES** - Program your `EXA`s (EXecution Agents) to tear through networks, replicate themselves, trash files, terminate other EXAs— and leave without a trace.
- **HACK _EVERYTHING_** - Hack banks, universities, factories, TV stations, highway signs, game consoles, the government... oh yeah, and your own body.

Get it now on [Steam](https://store.steampowered.com/app/716490/EXAPUNKS/).

---

## About Me

Aspiring software engineer, and advanced idiot in the field of _doing a lot of things at once_. Feel free to judge my garbage code.

---

## About the Repo

This was written in Visual Studio, with the help of some Markdown plugins and the [`EXA Syntax Highlighting` plugin](https://marketplace.visualstudio.com/items?itemName=pizzafox.exa-syntax-highlighting). Feel free to add your own solutions by submitting a pull request.

The `missions.zip` file included in the repo is labelled for every level in the game, if you want to make a similar repo of your own.

---

## Submissions

The [`example.exa`](/example.exa) file will show you how to format your own files for this repo. Note the use of `;< EX1` and `;>` at the start and end of modules containing multiple Exas; this, coupled with a single-space indent, is enough to enable code collapsing in VScode.

Files in the `code` directory are labelled with their execution properties. To explain what I mean for this, consider the code of `4C 3S 2A.exa`;

``` EXA
LINK 800
GRAB 200
LINK 800
```

When executed in the level Trash World News 1, this code gives the following results:

|Cycles|Size|Activity|
|------|----|--------|
|    4 |  3 |      2 |

Simple, no?

---

## EXA Code Guides

There's a few fun resources available online for learning more about how to program in the EXA language.

- [Exapunks Fandom Wiki](https://exapunks.fandom.com/wiki/EXA_instructions)
- [No Spoilers Code Guide by Wracketeer](https://steamcommunity.com/sharedfiles/filedetails/?id=1594593250)
- [Seralphi's Repository](https://github.com/Seraphli/EXAPunks)
