Here is a simple flow chart:

```mermaid
graph TD;
    start[You are walking down a dark hall and see two doors, green and blue, which one do you go in?]
    dog[You see a big dog looming in front of you, what do you do?]
    run[The dog jumps on you and rips you to shreds.]
    pet[The dog happily licks your hand and sits and your side.]
    goblin[You see a goblin with his back towards you, what do you do?]
    sneak[You sneak past the goblin without it hearing you]
    attack[You run at the goblin but it pulls a sword out of its cloak and stabs you to death]
    start-->|green|dog
    dog-->|run away|run
    dog-->|pet him|pet
    start-->|blue|goblin
    goblin-->|sneak past|sneak
    goblin-->|attack it|attack
```
