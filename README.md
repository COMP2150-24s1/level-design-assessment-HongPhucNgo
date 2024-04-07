
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [Hong Phuc Ngo]
### Student number: [47479728] 

```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)


This level design report is meant to explain how my level design promote the core player experience goals that are used as marking rubrics for the assignment.

## 1. Player Experience (~700 words)

### 1.1. Discovery:
       Through the first section of my level, the players learn the basics of the game from simple platforming to attacking/evading enemies and getting comfortable with traversing the game as a whole via being introduced to mechanics gradually as opposed to being information dumped at the start of the game. By designing my level with a steady introduction to the game’s mechanics, starting from simple platforming and then gradually adding more options to the player’s arsenal, I avoid overwhelming the player with information from the start and emphasize on creating a sense of mastery and progression which also contributes to retaining player engagement.
       
DocImages: Section 1 ig (DocImages/Section 1 ig.png)
       
       When players navigate through the first section of the level, they are not only introduced to the core mechanics of the game but also given obstacles to practice on and build confidence in their own abilities. This gradual teaching method reward players with a sense of accomplishment as they overcome challenges and further develop their proficiency.
       Additionally, by scattering the mechanics throughout the level and having their first appearance to be where they are relevant for the game’s progression. The combination of gameplay and learning mechanics will help players remain actively engaged and want to continue playing.



### 1.2. Drama
       After getting through the tutorial floors of the section, players are given a checkpoint and are introduced to a floor that requires the players to implement their newly developed skills into one big platforming floor to end off the section. This floor serves as a climax for the section, requiring the player make full use of everything they learned in the section. My design effectively utilizes the concept of a difficulty curve as it gradually increases in intensity as the section progresses. 

DocImages: Difficult section
       
       Afterwards, players are given a reward floor with the key and a lot of Heart Pickup so that the players are ready for the next section. Following up on the climax of the section, players are given a safe area allow for a moment of respite and numerous valuables to further drive the sense of accomplishment in completing the level.
       By intertwining moments of tension and relief in my design, I managed to create an experience that doesn’t feel stagnant and instead is dynamic and engaging for the players.

DocImages: reward floor

### 1.3. Challenge
	The main challenges in this assignment were gradually introducing and integrating game mechanics while also moderating an appropriate difficulty curve and keeping player retention. In my design, by starting with simple platform and gradually introducing in more complex mechanics, I was able to help the players learn and adapt to new challenges incrementally instead of immediately. This approach to game design helps the player feel less overwhelmed and with basic test cases of how to use a mechanic provided by myself, players are allowed to be creative in their approach towards the game. As such mechanics are used for puzzle solving in the next sections.
	Furthermore, the climactic end to a section via challenging platforming followed by offering the players a resting point with treasured lined up develop moments of tension and relief as the platforming floor provides a satisfying difficult spike followed by a reward floor celebrating a player’s achievement and also serves as a buffer allowing the player to recharge before going onwards to the next section.


### 1.4. Exploration
       In my section 2 and 3, the players are given a choice between an easy route or a more challenging route, both will lead to the same next area, however players are given a choice to choose which path they want to take. By giving the player a choice through layouts and pathways, it encourages autonomy and invites exploration from the player, it also allows the player to tailor their experiences based on their skill level and preferences further enhancing player agency and engagement.
       Moreover, section 2 emphasizes the puzzle solving aspect of the game so players are incentivized to explore the floor the find a solution forward. By implementing puzzles throughout the floor, my design rewards attentive players with a sense of accomplishment while also enriching the gameplay by fostering deeper engagement in the game.

DocImages: section 2 ig / section 3 ig

## 2. Core Gameplay (~400 words)

### 2.1. Chompers: My level starts out with the player character Ellen spawning behind a door activated by a reusable switch. Getting of the door leads the player to encounter their first enemy: a Chomper. However, at this point the player has no means of attacking yet and touching the enemy results in taking damage therefore players learn to avoid doing so by jumping over the enemy. 

DocImages: Chomper encounter

### 2.2. Acid & Moving Platforms: Right afterwards, the player is introduced to the first moving platform and acid pit with a Chomper on the other side, this portion is meant for the players to get comfortable with the movement controls and learn patience to not rush the level or else risk falling into the acid and starting the level over

DocImages: Acid pool encounter

### 2.3. Health Pickups: After the 2nd Chomper, the player gets to interact with the first Health Pickup. Players get to experience relief after getting pass their first section of the game

DocImages: health encounter

### 2.4. Passthrough Platforms: Players are introduced to passthrough platform as a way to ascend and descend between floors.

DocImages: passthrough encounter


### 2.5. Weapon Pickup (Staff): After getting to the 2nd floor of the 1st section, players are introduced to the staff, granting players the ability to lunge forward and attack. With a Chomper at the end of the floor to test out the attacking abilities.

DocImages: staff encounter / weapon encounter


### 2.6. Spikes: Right after acquiring the staff, players are introduced to spikes which also deal one damage to the player if touched, unlike acid pit, it won’t send the player back to there starting position. The jumps over these spikes are deliberate made to be almost frame perfect as to introduce the usage of the staff as a semi-movement option as it does lunge the player forward a bit.

DocImages: spike encounter / staff jump


### 2.7. Spitters & Weapon Pickup (Gun): Introducing a range combat option for the players will also introducing range enemies help keep the balance of the game and increase player investment and hype as the two sides are fighting with increasing firepower on each side.

DocImages: gun encounter / spitter encounter

 
### 2.8. Checkpoints: After having been introduced to all the basic features of the game (leaving to the tutorial section), players are greeting with the first checkpoint, ensuring them that they don’t have to repeat the previous section anymore unless due to a game over.

DocImages: checkpoint encounter


### 2.9. Keys: After conquering the first actual difficult platform jumps, players ascend to the top floor of the first section where the can find the key indicating that the section that they were in has been completed.

DocImages: reward room section one (key is at end of room)




## 3. Spatiotemporal Design:

All in DocImages:

### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3. Level Map – Section 2

### 3.4. Level Map – Section 3

## 4. Iterative Design (~400 words)

       Iterative design has played a crucial role in helping me improved my level design evolving it to be more polished and refine coming off of the drafts I made in the beginning which were very bare bones. These drafts consist of basic section layouts and mechanics that served as a basis for further creative interactions. Playtesting played a big part in my updating my level design as a I could put myself in the player’s position and was able to find issues that the players were consistently running into. 
       One such issues, is that the players if failing the acid pit jump and was returned to the start was being spawn camp by Chompers in the beginning section This created frustration and hindered players from progressing smoothly. To address this issue, I introduced a switch door at the beginning to mitigate the possibility of being overwhelmed by enemies right from the start. This design change alleviated the spawn camping issue and encouraged players to strategize their timing when exiting through the door. 
       Another scenario was the pushable block stack in the 2nd floor section 2 where the player was getting stuck in falling animation as a result of get stuck on the blocks. Players were getting stuck in a falling animation due to collisions with the blocks, disrupting the flow of gameplay. In response, I readjusted the block stack placement to alleviate this issue, ensuring that players could interact with the puzzle mechanic without encountering frustrating obstacles.
       Throughout this process, I also utilized gray-boxed maps, as it helps me establish basic layouts and flow of the level. These maps served as a great point of reference as it allowed me to experiment with different ideas.
       In conclusion, iterative design is of vital importance to improving one’s understanding and refining of level design. Through playtesting, I was able to further refine interactions in the game and grey box maps help me visualize my direction for the level.
       
       DocImages: Falling / Spawn camp
