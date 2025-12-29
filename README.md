# Rotom Draft

![](https://raw.githubusercontent.com/miggtorr/RotomDraft/refs/heads/main/icon.iconset/icon_256x256.png)

### The All-In-One VGC Draft League Software Suite for macOS.

**Rotom Draft** is a feature-rich suite of software tools to help **VGC Draft League** players bring their best game to their matches. 
Powerful integrations with [Pokemon Showdown](https://play.pokemonshowdown.com), the [PokeAPI](https://pokeapi.co/), and **PokePast.es** let you quickly design the optimal strategy for your next match!

## Requirements

macOS 14 Sonoma or higher.

NOTE: There are currently no plans to port the software to Windows/Linux.

## Features

**Rotom Draft** features three main workspaces: the **Analysis Panes**, the **Tool Drawers**, and the **Damage Calculator**. 

The **Tool Drawers** features **powerful applets** that let you: 
- Build your best Roster
- Calculate optimal tera-types
- Keep track of the league's schedule and standings
- keep notes, records, and replay URLs (Showdown, YouTube, Twitch, etc.) for each match
- Build Teams based on the Pokémon on your Roster

The **Analysis Panes** are where you go to deep dive into a Roster's strengths and weaknesses, including:
- Moves
- Stats
- Type Matchups
- Battle Strategies
- Ability Interactions
- Weather/Terrain Synergies
- Speed Control Methods
- and More!

You can also keep track of your League's **Draft Board** here, filtering Pokémon by draft point value and availablity status to plan trades and free agency swaps!

Finally, the **Battle Calculator** lets you quickly make critical calcs between Pokemon on different teams and rosters, saving tweaks, as needed. It's a fully-embedded version of the [Pokémon Showdown calculator](https://github.com/smogon/damage-calc), so all the results and interactions are identical to what you would calculate [online](https://calc.pokemonshowdown.com/). 

## Organizing Principles

The basic organizing principle behind Rotom Draft is that groups of Pokémon are organized hierarchically like so: 

**League => Roster => Team**

### League

A League is the event in which the player is participating. Essentially, a tournament. 

Leagues have Rulesets associated with them that specify what's available on the Draft Board, how many draft points each player receives, and how many pokemon can be selected.

In Rotom Draft, a League also features its own schedule, leaderboard, and playoff bracket. 

If you are participating in several Draft Leagues at the same time, **Rotom Draft** helps you keep those different Leagues sequestered—along with their associated Pokemon, Players, Standings, etc.—so you're never confused as to which League your looking at!

### Roster

A Roster is a player's selection of drafted Pokémon, usually 10 in standard VGC formats. In Rotom Draft, Rosters can be associated with a particular League. Multiple rosters typically associate with a single League. 

All of Rotom Draft's analysis functions apply to entire Rosters so you can see the plethora of interactions and counter-interactions that you or an opponent can create using the Pokémon on a roster. 

For exmaple, tools like [Marrilan's Pokémon Team Builder](https://marriland.com/tools/team-builder/en/) help you see the defensive type profile of a group of up to six Pokémon—brilliant for ladder or tournament teams. But the Rotom Draft Type Matchup Analysis Pane lets you see the defensive type profile of all your entire roster, factoring in moves like Freeze Dry and abilities like Neutralizing Gas that turn off things like Levitate and Flash Fire. 

All Rosters can be imported via PokePast.es or exported to the clipboard in Showdown format, so you can easily move data to and from Showdown for backup, analysis, or playtesting.

### Teams

Teams are the party of six Pokémon a player brings to a match. 

Teams are typically composed of a subset of the Pokémon in a Roster. They can be customized and tweaked just like on Showdown, with Abilities, Movesets, Natures, Items, and the like. 

Teams can be created and edited inside of Rotom Draft's powerful Team Builder. They can also be imported or exported to/from Showdown for backing up or play testing. 

Teams are what you load into Rotom Draft's Battle Calculator, and can feature more than 6 Pokémon, e.g., if you need to calc your team against an opponent's entire roster. 

## Tool Drawers


