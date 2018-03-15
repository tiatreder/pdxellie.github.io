---
layout: post
---
The first project I did in Python was a simple game in which the player is prompted to respond to choices.
The player can either be eaten by the monster or survive depending on the choices they make.
This is the code for that game.

```python
#introduction
print("welcome to the APOCALYPSE")
print("do you want to SURVIVE?")
print("type YES or NO")

#saving the user's response for survival
survival_choice = input()

#responding to the choice: yes
if survival_choice == ("YES"):
    print("GOOD CHOICE.")
    print("there is a GIANT MONSTER! do you")
    print("1: FIGHT IT,")
    print:("2: TELL IT IT LOOKS PRETTY TODAY, or") 
    print("3: RUN FOR YOUR LIFE?")
elif survival_choice == ("yes"):
    print("GOOD CHOICE.")
    print("there is a GIANT MONSTER! do you")
    print("1: FIGHT IT,")
    print("2: TELL IT IT LOOKS PRETTY TODAY, or")
    print("3: RUN FOR YOUR LIFE?")
#responding to the choice: no/not yes
else:
    print(("LOSER. YOU'RE DEAD NOW.") + (" I HOPE YOU'RE HAPPY ABOUT IT."))
    
#saving the user's input for defeating the monster
monster_choice = int(input())

#naming and giving responses
fight_death = ("it's a giant monster, you idiot. you can't fight that. YOU'RE SUPER DEAD.")
run_death = ("it's a giant monster, you idiot. you can't run from that. YOU'RE SUPER DEAD.")
love_survive = ("the monster has spent its whole life unloved. you've showed it the meaning of joy. ALSO YOU SURVIVED AND ARE NOW BETROTHED TO THE GIANT MONSTER.")

#responding to the user's choice of reaction
if monster_choice == 1:
    print(fight_death)
elif monster_choice == 2:
    print(love_survive)
elif monster_choice == 3:
    print(run_death)
```
