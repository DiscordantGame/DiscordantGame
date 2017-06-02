# Discordant 

Discordant is a Discord-based bot that allows players to (solo or cooperatively) explore maps and battle monsters, as well as engage in a global market to earn gold

## Registering

To register, type:

    dbegin <class>

Your choices for class are `healer` and `mercenary`, for more information type `dclasses`

## Basic commands

To view your inventory, you can use 

    dinv

To use an item, for example your healing vial you can use

    duse vial

There is also a global shop that sales basic items

    dshop

## Forming a party

To form a new exploration party (even if you want to explore alone)

    dpnew <name of your party>

Once you have formed a party you can explore with

    dexplore

## Exploring the map

To interact with your current location use

    dinteract (or di)

<span style="color:blue">Note:</span> Tiles you can interact with have a message

---

To move around the map use

    dpmove <U|D|L|R>

<span style="color:red">WARNING:</span> Moving may cause a monster to attack!

## Battling

Battles are turn-based:

* A monster opponent will attack the party

* Each person in the party can take one action

* Actions: attack, use item, heal, run

To attack with your primary weapon use

    dattack (or da)

To attack with your offhand weapon

    doffhand (or doff)

New healers have a tablet that can heal in their offhand, new mercenaries have a shield that passively decreases damage.

Some attacks (like healing) require charges; to collect charges use

    dcharge (or dc)

## Returning to town

When you are done adventuring, you can use `dpdisband` to return to town

For additional information on available commands use `dhelp`, `dhelp <commandName>` or check out [the commands page](commands.md)