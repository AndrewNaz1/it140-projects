# Project One Storyboard | Text-Based Adventure Game

## Theme and Storyline

**Theme:**

A quiet study in how small comforts hold a community together. The Bramble Hollow Apiary and its bees sit at the edge of a village that has started to forget what its own honey once meant. The game rewards patience and looking closely: the player fixes the hive in the order a real beekeeper would, and the reward is a cellar that smells like September.

**Storyline:**

The player wakes as the night-shift beekeeper of the Bramble Hollow Apiary and finds the hives silent: Marrow, the Hollow Queen, has carried the hive's entire brood away into the ruined Old Orchard to raise an army that will strip every blossom from the valley. To call the colony home the player must gather six things - the Foghorn Press, the Copper Smoker, the Wax Tablet, the Riverman's Net, the Harvest Ledger, and the Bone Key - then make the final walk down the Clay Road to the Old Orchard and face Marrow in the Hollow Queen's Chamber before the last of the summer light goes.

## Rooms

Eight rooms. The player starts in the Honey Gate and finishes in the villain's chamber.

1. **Honey Gate** (room0, start room, no item) - the gravel yard and painted gate where the beekeeper's shift begins.
2. **Bottling Shed** (room1) - where the honey is poured and the comb is pressed; holds the **Foghorn Press**.
3. **Wax Works** (room2) - the low, warm room where frames are built and sheets rolled; holds the **Copper Smoker**.
4. **Lavender Rows** (room3) - the terraced garden that feeds the bees; holds the **Wax Tablet**.
5. **Willow Bend** (room4) - the riverbank where the hives are floated downstream in spring; holds the **Riverman's Net**.
6. **Honey Cellar** (room5) - the cool cellar under the packing floor, stacked with labelled years; holds the **Harvest Ledger**.
7. **Clay Road** (room6) - the track at the edge of the property, leading away from the apiary toward the orchard; holds the **Bone Key**.
8. **Hollow Queen's Chamber** (room7, villain room, no item) - the rotted heart of the Old Orchard, where Marrow keeps the stolen brood.

## Items

Six collectable items. Every room except the start room and the villain room contains exactly one.

1. **Foghorn Press** - a cast-iron lever press used to squeeze the last comb; worked until the shed's alarm horn sounds, loud enough to carry down the Clay Road. (Bottling Shed)
2. **Copper Smoker** - a dented copper bellows smoker; puffed to lay a screen of smoke that keeps Marrow's foragers off a path. (Wax Works)
3. **Wax Tablet** - a scored sheet of beeswax the beekeeper presses notes into; records the route the bees took when they left. (Lavender Rows)
4. **Riverman's Net** - a fine-meshed net on a willow hoop; stretched to catch the swarm before it scatters. (Willow Bend)
5. **Harvest Ledger** - the apiary's record of every season's yield; names Marrow's lineage and the one thing she cannot take from the honey-house. (Honey Cellar)
6. **Bone Key** - a key cut from a split queen cell; turns the orchard's bone gate, which no amount of force will move. (Clay Road)

## Villain

**Marrow, the Hollow Queen** - an old queen bee gone solitary and wrong, roughly the size of a hound, her abdomen banded in dusty gold and her wings furred with grey mould. She has carried away the brood and every drop of the season's stores and hidden them in the Hollow Queen's Chamber at the heart of the Old Orchard. She does not chase the player; she waits, because she has taken everything the apiary needs to survive the winter and waiting is cheaper than hunting.

## Storyboard and Map Check

- [x] I included eight (8) rooms.
- [x] I included six (6) collectable items.
- [x] The start room has no item.
- [x] The villain room has no item.
- [x] Every room except the start room and the villain room contains one item.
- [x] Room, item, and villain names match my map.
- [x] The map allows the player to collect all required items before the villain is encountered.


## Project Two Handoff

Keep this file after Project One. In Module Seven, use these names and design choices when building the final room/item dictionary and player-facing output.

- Room keys and display names: room0-room7 as listed in **Rooms** above, in that order.
- Item keys and display names: the six items as listed in **Items** above, in that order, each bound to the room that holds it.
- Villain: **Marrow, the Hollow Queen**, placed in room7.
- Movement language is fixed to `go north`, `go south`, `go east`, `go west` and must stay consistent with the direction edges on the map.
