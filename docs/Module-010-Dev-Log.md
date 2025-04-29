<!-- Markdown Docs: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
## Name: Fernando Mantilla
### Module: 010

<!-- Repeat the below as needed-->
### Date: [04/28/2025]

#### Goals for this Module
<!-- Example Template (include the brackets to make a checklist, fill them in as appropriate
- [ ] Goal 1
- [ ] Goal 2
- [ ] Goal 3
-->
- [ ] Fully implement current version onto unity
  -  [ ] Cards
  -  [ ] Objectives
- [x] Redo map with gameObjects and appropriate behaviors for general tiles on tilemap
  -  [ ] Specify behaviors depending on the type of tile
- [ ] Create card control mechanism and round mechanism

#### Progress
- **What I accomplished**:
  - *Summarize completed tasks or progress made.*
  -  Mapped the grid to tile gameObjects using the tile palette editor provided by Unity. Created a script for a main menu which loads the appropriate scenes.

- **Challenges faced**:
  - *Describe blockers, bugs, or issues encountered.*
  -  Issues with tilemap system not properly rendering gameobjects and drawn tiles. It seems like the tilegrid prioritzes tiles to be drawn on top first. Sorting layer does not help the situation.
  -  Issues with remembering how components interact with one another.
- **Solutions**:
  - *Detail how you addressed challenges or your thought process.*
  - Plan to use gameobjects on all tiles until I figure out how to draw them on the same sorting level.
  - Reading documentation and quick google searches to recall appropriate script
#### Learnings
- *Key insights, techniques, or concepts explored.*
- Learning about tags, script, and attaching these to entities will allow me to standardize behaviors for particular tiles


#### Free Thinking
- *Brainstorm or reflect on design ideas, architecture patterns, or potential improvements.*
-  Want to support both mouse and keyboard control.

#### Next Steps
- *Tasks or experiments to focus on during the next session.*
- Create game loops, controllers, and logic on game board tiles.
- Goal is a fully working game loop.
