A collection of PennMUSH softcode (in-game code), also known as MUSHcode,
that I've seen fit to publish.
MUSHCode is a Lisp-like language to control objects in a virtual MUSH environment. It has a lot of neat features for a language, and is moderately beginner-friendly. An interesting paper on the features of MUSHCode and arguments for why learning it is a good programming foundation are here: [http://community.pennmush.org/book/enough-be-dangerous-conceptual-models-mushcode-5](http://community.pennmush.org/book/enough-be-dangerous-conceptual-models-mushcode-5 "A treatise on MUSHcode")



* function\_manager: Easily manage what @functions load when the server starts.

* guest\_identity: Change the names of guests when they connect, based on custom mappings. Examples are given to bind guest names to IP addresses, produce pseudo-random names, and rotate through a fixed list (like on M\*U\*S\*H).

* kilt: A unit-testing and mocking system for PennMUSH Softcode.

* Myrddins\_BBoard: Performance and cosmetic improvements to Myrddin's BBoard System. Currently, a mirror of Myrddin's BBS can be found here: [http://myrddin.annelions.com/](http://myrddin.annelions.com/)

* ooc: A simple +ooc command for room-local out-of-character communication.

* oocc: A simple teleportation command that takes a player on or off a defined IC grid.

* typical\_who: An easily alterable online player listing. Designed for rapidly prototyping +who appearance.

* pathfinder: [library] A functional, breadth-first pathfinder. Can be used in code such as teleportation and map systems, for giving directions.

* playstatus: Allow players to set their playstatus (IC/OOC/AFK) with the +ps command and shortcuts. New statuses are easy to build and restrict, and can have side-effects (like a Wizard being set off-duty when IC).

* posemeter: Award EXP or points for roleplaying based on number of alternating poses, content length, etc.

* where: A simple +where that sorts by unique location. The appearance is easily altered.


Other good sources of MUSHCode:
* Talvo's Globals: http://keyboardzombie.com/mush/code
