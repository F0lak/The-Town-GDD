# Player Control Overview
***
### Basic Controls
Movement is done with WASD

Most actions are performed with the mouse.  As the mouse moves about the players screen, the head will tilt towards its direction and the character sprite will flip to face the cursor. When the UI is open to interaction windows (inventory, writing in a book, typing, etc) the character body ignores the cursor. (might play around with this to see how it looks and feels with the character still following the cursor with a small overlay to indicate they are typing or rummaging through a bag, just to see how it looks and feels)
***
### Basic Actions and Hands
LMB / RMB are used to perform a Passive Action with the Left / Right hand respectively

Ctrl + LMB / RMB is used to force an Action with the left / right hand respectively
(this may be a toggle, or maybe a user setting to choose between the two)

Passive Actions are things like opening a door, opening a chest, etc.

Actions are dictated by what is held in the hand in question.
	For example, an Action with most things would be an attack (LMB holding a Sword or a Stick in the left hand)
	Every object will have an Action defined that dictates what this action would be.

CTRL + Q / E is used to drop the item in the left / right hand
	This is done with CTRL to avoid accidentally dropping items (ie dropping your sword during combat)
***
### Grabbing Mechanic
Q / E are used to "Grab". If a player grabs with one hand then they are "holding on to" what ever they grabbed and will follow it if it moves.  If they grab with both hands then they will restrict movement of whatever they have grabbed.
When a player is grabbed by another player they can mash the "Space bar" to escape the grab.  Likewise, when a player has grabbed another player, they can mash the spacebar to maintain their hold.
It's like a bar that goes back and forth.
