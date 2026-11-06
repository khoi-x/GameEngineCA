
# Card Escape
Student Number: A00085105

Class Group: TU856

Video:

# Description of the project
Vocabulary matching game, where the user picks up a card and matches to one of 3 Boxes before an enemy attacks the player / while preventing an attack.
The user will learn vocabulary through recall and repetition 
# Instructions for use
Look around and pick up a card via gesture or keyboard&mouse and match it with the correct word
# How it works
Spawns cards with images/words to the floor that the user has to match with one of the boxes with images. Potentially with extra "power" cards to e.g. freeze the enemy
# List of classes/assets in the project
Card Class

Hands Repo: https://github.com/skooter500/hands

# References
Hands Repo: https://github.com/skooter500/hands

# What I am most proud of in the assignment

# What I learned

# Proposal submitted earlier can go here:

**Summary**
Vocabulary recall while under pressure from enemies. Players must look around for cards and rapidly pick up vocabulary cards scattered around them on the floor and assign them to the correct target boxes before an approaching enemy attacks/reaches them. By immersing the player with physical movement (looking for cards, enemies and picking up cards) and creating an environment for repetition and recall, the game reinforces vocabulary acquisition through high-stakes repetition.

**Gameplay Mechanics & Core Loop**
_Core Loop_
1.	Spawn Cards: cards with images and words, target words, non-target words and power cards
2.	Monitor target boxes and enemies: through visually looking and sound they make
3.	Shoot: shoot at target box or enemy
4.	Success: next level removes 1 of the training wheels

_Controls_
Primary: pick up hand-gesture and release to shoot(tbd) 
Secondary: mouse and keyboard

_Power Cards:_
•	Freeze card
•	Destroy
•	Tbd

**Learning objective**
Vocabulary acquisition while under fun and engaging mild pressure

_Technologies and libraries_
•	skooter500 Hands repository for hands & Godot XR Hand Pose Detector 
•	Json for word storage
•	Blender to make assets
•	GDFXR for sound effects / Spatial audio3D?
•	Digital drawing software for art

_(Visual Example)_ 
<img width="719" height="619" alt="Screenshot 2026-10-25 003218" src="https://github.com/user-attachments/assets/0bd3d055-5cb7-40bb-9e65-234c37f436ed" />

**Development goals**
1.	Spawn cards: spawn logic
2.	Picking up and throwing cards: physics and raycasting
3.	Matching cards: data store
4.	Enemies and power cards: path to player
5.	Audio and visuals: Sfx and 2/3D assets creation
