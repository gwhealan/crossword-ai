# crossword-ai

## Project Goal:
This is an extension of a [previous project](https://github.com/wilsprouse/422-proj2) I worked on during college focused on designing a crossword builder using simple machine learning algorithms. While conceptually advanced, due to a combined inexperience from my group members and I steming from my overconfidence in the field, we made many mistakes in that initial project. By using an A\* search algorithm, inificient python structures, and a underdeveloped heuristic the program proved taxing even for 5x5 crosswords. By restructuring and improving these elements, I hope to develop a capable and quick crossbuilding tool with my further experience.

## Initial Issues:
The main issues seen in the initial project are, as previously stated, mainly due to runtime issues. Specifically,
- **Search Algorithm Structure:** The initial project used an A\* search algorithm. This lead to issues during development as it was diffucult to develop a valid heuristic within the limited development time along with supporting structures. In this project, as there is no defined due-date, I hope to expand the heuristic or, if the A\* search algorithm proves to difficult to develop, pivot towards a more advanced algorithm such as Q-learning.
- **Dictionary data structure:** While the initial trie structure provided a viable system for returning multiple words for a given row, the allocation storage and means of returning data created both a runtime and storage issue for the remaining system. To improve this I will replace the return structure to return 1 word at a time and save the trie state instead of returning a list of all words. If this proves taxing still I will port the structure to embeded C/C++ code for more proper data management.

## Issues List:
- [ ] Improve Heuristic.
- [ ] *\(Optional) Swap to Q-learning*
- [ ] Restructure trie return system
- [ ] *\(Optional) Port trie to embeded C/C++ code*

## Contributers:
Graham Whealan.

Initial code forked from [project](https://github.com/wilsprouse/422-proj2) by Graham Whealan, Shoshanah Bernhardt, and William Sprouse.
