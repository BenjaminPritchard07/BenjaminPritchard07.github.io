Here is a simple flow chart:

```mermaid
graph TD;
    start[You are walking down a dark hall and see two doors, green and blue, which one do you go in?]
    dog[You see a big dog looming in front of you, what do you do?]
    run[The dog jumps on you and rips you to shreds.]
    pet[The dog happily licks your hand and sits and your side.]
    goblin[You see a goblin with his back towards you, what do you do?]
    start-->|green|dog;
    dog-->run
    dog-->pet
    start-->|blue|goblin;
```
