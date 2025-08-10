# 2025-summary-project

- This is a simple MUD game about exploring a dungeon hunting rascal (or mega knight) Data designer DO YOUR JOB NOW 😡😡😡😡😡😡

## About

[Drop Lore Here]

## Members

- Edward Yee (Team Lead)
- Lohith Ishan (Test Enginneer)
- Luke Yeo (Game Programmer)
- Matthew Na (Game Programmer)
- Matthew Sim (Data Designer)

## Project Structure

```
.
├── README.md
├── main.py (pls remove either this or the mud.py file, depending on which one will become the acutal project)
├── mud.py
├── environment
├───── map.py (linkedlist using room's child classes)
├───── room.py
├───── treasure.py (inherit from room)
├───── battle.py (inherit from room)
├───── boss.py (inherit from room)
├── entities
├───── stats.py (name is subject to change, i added this because both monster and player have stats(id assume) --> inheritance, maybe polymorphic method actions() also?)
├───── monster.py (could become enemy if it goes to mega knight lore)
├───── player.py 
├── objects
├───── item.py
├───── inventory.py (potential hashtable, not necessary to overcomplicate though)
```
(subjected to change)

## Classes

- Room
  - Treasure
  - Battle
  - Boss
- Map
- Item
- Inventory
- Monster
- Player

# Footnote

This is a J1 Summary Project. Names, characters, businesses, places, events and incidents are either the products of the author’s imagination or used in a fictitious manner. Any resemblance to actual persons, living or dead, or actual events is purely coincidental. Apologies to those who feel distress due to unintentional fate alignment.
