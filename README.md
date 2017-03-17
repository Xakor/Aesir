
# Aesir
Aesir is a Zelda inspired top down action adventure game, set in Viking esque age, where you venture into dungeons, to find the sacred mcguffin pieces.
It features exciting and unique ideas such as; ~~Multiple Weapons~~, ~~Heavy and Emphasized Combat~~, ~~Challenging Bosses~~, ~~Viking Graves~~, ~~Deep and Immersive Story~~, ~~Graphics~~, ~~Gameplay~~, and of course: The true, and unquestioned meaning of life!

The Project is for our 4th semester computer science Game Development Elective, and is made with Unity Engine & C#, and is made by: @biancehelbo, @burasdiana, @Xakor & @Muunjuze

# Design Document
The core principle of Aesir is to combine the adventurous feel of top down Zelda Games, with the tense and emphasized combat of the Souls Series.

### Gameplay
The player takes control of a burly bearded viking warrior.
The warrior is controlled with with basic Orthogonal inputs, and is moving at a fairly brisk pace.

Beyond basic movement the character is also able to perform a roll, that allows him to dodge around enemy attacks, though only in the four primary directions, as the character movement is locked for the duration of the roll.

The player is equipped with a mighty battle-axe  that required some serious strength to swing around! Therefore most attacks in the game will have a bit of ramp up-, and swing -time. Much like the dodge roll, the characters movement is locked to four directions while an attack is performed (though the swing arc should allow the player to attack enemies besides him). 

The Core gameplay loop is gonna involve the player walking traversing "Dungeons" in where their gameplay skills, regarding combat, puzzle solving, and spatial awareness should be tested... And of course rewarded, with either loot, or upgrades (Still working on this part). At the end of a given dungeon the player should face of against a boss that should try to "sum up" the various lessons that the player have been "taught" allthrough the dungeon.

When not in a dungeon, the player is placed in an overworld map, that serves and the primary hub, to link story related progress, as well as potential secrets and dungeon entrances.  

### Input and control
As mentioned in the gameplay section the character is able to move in eight directions, corresponding to WASD, or the arrow keys. 

The Attack button is a shared key, that can become context sensitive given the player is in a situation where it would be nescersary. (If the player was in front of an NPC or a Sign, the attack button would switch to either "Interact" or "Read")

The dodge roll button should allways serve as a movement option for the player, and should be quickly accessable when the player have their hand on the attack button. ALSO: The dodge roll should be a fast way for the player to dodge an attack, but should potentially have a cooldown, to prevent it from being faster than running in the overworld, as having to press the roll button every two seconds would become quite annoying after a while (should be bound to a button close to the attack button)
### Story & Setting
The setting og Aesir is a viking world where all inhabitants have a big, burly beard. <more to be determined>
