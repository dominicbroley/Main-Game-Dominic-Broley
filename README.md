# Main-Game-Dominic-Broley
consumables = ["Apple", "Tomato", "Banana"]
weapons = ["Sword", "Axe", "Spear"]
# prints the consumables in a numbereical list
print("\nAvalable Consumables:")
for number, consumables in enumerate(consumables, 1):
    print("{}. {}".format(number, consumables))
# prints the weapons in a numberical list
print("\nAvalable Weapons:")
for number, weapon in enumerate(weapons, 1):
    print("{}. {}".format(number, weapon))
