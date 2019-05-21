Download the data: https://raw.githubusercontent.com/washingtonpost/data-game-of-thrones-deaths/master/game-of-thrones-deaths-data.csv

[This data is published under an [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license](https://creativecommons.org/licenses/by-nc-sa/4.0/)]


# About this story

The Washington Post has [compiled an illustrated database of every single death in Game of Thrones](https://www.washingtonpost.com/graphics/test/pub/entertainment/game-of-thrones/) over the course of its eight seasons, including background extras and animals. These numbers only include on-screen deaths. For more information, read on.


# About the data

**location**:
The most specific location name available is used. For example, Hardhome is beyond the wall but is labeled by its own town name instead of `Beyond the Wall`. Therefore, there may be cases of location overlap despite different location values.

**method/method_cat**:
Method is a subset of the method category. E.g. `Dragonfire` is the specific method, but the category it falls under is `Animal` because of its origin. (See methodology section below for more details.)

**importance**:	
The importance level of a character is determined by his/her/its significance to the plot. This is why Lady has a less important rank than Grey Wind, even though they are both Stark direwolves.

- 1: Background extra
- 2: Minor character
- 3: Secondary Major
- 4: Major
				

# Methodology

**A death is counted only if**:

1. The character is killed on-screen.
2. The character dies off-screen, but the death is confirmed or assumed due to imminent death while on screen.
3. Only prominent off-screen deaths are listed. (Prominence is determined mainly by importance to the plot.)

**Other notes**:

- If a character orders the death of another, the character who does the direct killing receives credit, not the one who orders the kill. But for cases in which where the direct killer is unidentifiable, as when Cersei Lannister uses the caches of wildfire to blow up the Great Sept of Baelor, the order-giver receives credit.

- In cases of overlapping weapon types (e.g. magic fireball vs. fire vs. magic), the weapon category is assigned based on the origin. For example, dragonfire is considered an “animal” death and magic fireball is considered a “magic” death.

- If a character is mercy-killed, the mercy kill is used to categorize the death, not the injuries leading up to the moment.

- Season 5 notes:

	- In cases like the Massacre at Hardhome, normal human standards are applied to wights to simplify the process. In other words, an arrow through the skull or a sword through the spine counts as a death, even though officially speaking, a wight is never killed unless burned or stabbed with dragonglass.

- Season 6 unotes:

	- If a character dies but is brought back to life (e.g. Jon Snow), the death count stands and the revival is counted as a “second life.” Temporary deaths like Euron Greyjoy’s drowning ceremony are not counted. Beric Dondarrion has been added to the death count as a result of this rule. Gregor Clegane has not been added because it is unclear whether he died off-screen and was then reanimated, or was “altered” while still alive.

	- For the Battle of the Bastards, it is often unclear which side a dying soldier belongs to. Educated guesses are made based on the shape of the helmets (Bolton soldiers had pointier helmets) and sigils that can be seen on armor.

- Season 8 unotes:

    - Because dragonfire covers up the things it burns, educated guesses are made based on approximately the size of the dragonfire’s area of attack. For example, if the fire is about 11 people wide and 2 people deep, we would multiply 11 by 2 to get 22 people. We also assume that the fire only kills enemies and not allies by accident, though we can’t be sure.

	- For the Battle of Winterfell, both Ironborn and Karstark soldiers help protect Bran in the Godswood. But because we don’t know who is who, we’ve simplified it and labeled them all as Ironborn because Theon was the leader. Similarly, we’ve labeled all unknown soldiers during the main battle as “Stark soldiers” because we have no way of knowing who they actually are. (The soldiers who surrounded Lyanna Mormont, however, were assumed to be Mormont soldiers and labeled as such.)

	- Similarly to above, all foot soldiers in the attack on King’s Landing are labeled as either Stark or Lannister soldiers, unless obviously otherwise. (E.g. Unsullied have obvious uniforms and are therefore labeled as such.)

	- Though we do count the death of a wight-version of a character as a second death, the deaths of characters like “Wight Eddison Tollett” are not included because we technically didn’t see them die on-screen during the Battle of Winterfell.

	- When Euron Greyjoy’s fleet attacks Daenerys Targaryen’s fleet in episode four, we technically don’t see any Unsullied die on camera. Some soldiers were flung into the air and out of the boat because of the bolts’ force, but we can’t assume they all immediately died. Therefore, no Unsullied deaths were counted from that attack because we saw no on-screen deaths.

	- When Daenerys Targaryen burns Euron Greyjoy’s fleet, it is difficult to see how many soldiers are on each boat though we see movement that indicates they are there and therefore died “on-screen.” Educated guesses are made based on previous scenes showing that approximately seven people are needed to operate each scorpion. There may be more killed, but they could not be visibly seen.

	- Deaths by rubble/wildfire caused by Drogon’s dragonfire are attributed to Drogon, though they may be inadvertant. This is because Daenerys’s intent was to kill as many as possible; these aren’t just accidental deaths that wouldn’t have happened otherwise.


# Credits:

Research, Reporting, Design/Development and Illustrations by [Shelly Tan](https://www.washingtonpost.com/people/shelly-tan/)
