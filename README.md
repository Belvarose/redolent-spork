# redolent-spork
(name tbd)

a text-based adventure game

- multiple adventures to select from (only demo available initially)
- online multiplayer (2-6 players)
- items, weapons, armour
- player classes, skills, races (maybe later)
- turn based combat/actions
- real time chat for ui for both server and client

classes & design patterns:

- actor class -> player, npc, monster subclasses
- item class -> weapon, armor subclasses

- factory for adventures, actors, items, etc
- config for server settings, enable ui
- json serialization for players

- maybe port to java

server functionality (controller)
- process client input request
- sent output response

client functionality (view)
- gather user input
- display server response
