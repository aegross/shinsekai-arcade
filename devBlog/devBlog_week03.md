# Shinsekai Arcade - Development Blog - Week #3

## Main Accomplishments
### Technical
- Finished the dialogue system for now, not including audio implementation. What is currently there may need tweaks later (and there might be some bugs, particularly related to one of the functions for reversing dialogue progress)
- Made significant progress on object interaction
  - Objects can now be subclassed from an interatable object blueprint class, which implements an interactable interface with events that the player can receive
  - There's also an actor component that is placed on interactable objects, which includes functions for the start, end, and "purpose" of interactions (the last of which is meant to be overriden)
- Begun the creation and implementation of an inventory system (from this tutorial series: https://www.youtube.com/playlist?list=PL4G2bSPE_8umjCYXbq0v5IoV-Wi_WAxC3)
  - Objects can now be subclassed from a "pickup" blueprint class, which contains item info (relevant to an inventory) and allows the object to be destroyed
  - The inventory isn't visual yet; just data being held in an array of structures (inventory slots) which hold other structures (inventory item data)

#### Material Related
- Made a post-processing outline material for objects or meshes (from this tutorial: https://www.youtube.com/watch?v=INiUXnNlB1I)
  - since this is a post-process material, it's visible through everything (including the character), so it might not be usable
- Made a regular outline material (although it isn't as good) for objects or meshes (combined from a couple tutorials).
  - This is the one that's currently used in-game, for when objects or NPCs are interactable

### Artistic
-

### General
-
