# Heal us, Mara

Modification for Crusader Kings 3.

Allows a landed owner to pray to goddess Mara for healing. During a special ceremony, that costs 1000 piety, Mara attempts to heal all diseases on all who is present. With a non-zero probability, every curable disease might be healed immediately.

## Technical requirements

* Crusader Kings version Crown 1.15.0.2.
* Elder Kings modification version 0.15.1.

## Languages supported

* English.

## Motivation

There are many gods in Nirn. However their influence is minimal. For instance, Mara never helps court physicians heal wounds or diseases. They say those who worship Mara may get random events that result in healing, but these events are quite rare and should not be relied upon.

*"I created a custom faith that worships Mara among other gods, I am a mighty emperor, I am a paragon of virtue, I have tons of piety, prestige and money. Now how do I heal my daughter who caught lovers pox? — No way, rare random event only".*

## Healing ceremony

A player or NPC

* who owns land,
* whose pantheon includes Mara,
* is not at war or at special activity,
* is physically present in his residence,
* has reached piety level 3 (Devoted Servant) or above,

may organize a special ceremony that costs 1000 piety. The ceremony is attended by all courtiers who are present at court and have a curable disease. During the ceremony, every curable disease has a chance to be healed. The chance depends on Mara's attitude towards liege and sick courtier and is at least 5% (20% for children). If liege has highest piety level and many children and love relations, the chance might be 50% or more, even if courtier is a sinner in eyes of Mara.

To organize healing, activate decision "Pray to Mara to heal diseases". AI character may choose this, too, especially if they are compassionate and someone they care about is sick. You will see decision "Pray to Mara to heal diseases" once you if you oen land.

Before spending 1000 piety, you see an option "Ask Mara to heal THIS_MANY people". After the ceremony you will see report: how many diseases and people were cured. Courtier is considered to be cured if at least one of his diseases is gone.

Mara's healing is more useful for old and established liege and courtier and less useful for young rules and sinners. But, if you are not buying claims or reforming religion, you probably have no use for your piety. Thus the healing ceremony might be useful for young rulers, too.

## Bonus effect

If someone rejected-from-marriage-bed healed their sexually-transmitted-disease, they lose the rejected-from-marriage-bed status. This happens silently and automatically regardless of treatment method.

## Installation

1. Put all files except `readme.md` into `mods` directory, where you put `elder-kings-ck3.mod` file and `elder-kings-ck3` directory.
2. Activate via launcher called `dowser.exe`.

For more details, see [wiki](https://ck3.paradoxwikis.com/Modding#Installing_mods_manually).

## Load order

"Elder Kings", then "Heal us, Mara".

## Bugs

Send bugreports and suggestions via github. If you found the mod elsewhere, you better visit primary page [on github](https://github.com/krisk0/heal_us_mara/).

## Q&A

1. Can you port this mod to a newer version of the game? — Absolutely, as soon as Elder Kings for that version is released.
2. Can you add support for another language? — No, I am terribly busy, I am taking Imperial Island.
3. Can you change this mod so it does not require Elder Kings? — No, I live in this universe. Hire someone in that universe or make modifications yourself.

## List of my CK3 modifications

1. [Heal us, Mara](https://github.com/krisk0/heal_us_mara)
2. [Focus and guardian](https://github.com/krisk0/focus_and_guardian)
3. [Elder Kings fixes and tweaks](https://github.com/krisk0/ek_fixes_and_tweaks)
4. [Disable achievements](https://github.com/krisk0/disable_achievements)
5. [Scarab blood icon](https://github.com/krisk0/scarab_icon)
