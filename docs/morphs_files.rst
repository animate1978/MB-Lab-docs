Morphs Templates
================

A quick tool for creating morphs template. Morphs are used to shape a character, but are also used for topics that need to know where vertices are, like measures. So some morphs are hard-coded, their name are used in many parts of the program, and can't be changed. There are all saved in the main morphs library used by all characters from a gender. For example, all female humans in the base addon use 2 morphs files, one for "core" morphs, one for "extras". Others morphs files are used too, but are specific to phenotypes (like Asian). The "core" morphs files contains many morphs, but also the ones needed for the engine to work properly.

So this tool make a template file with all needed morphs. It's very simple, as the morphs in fact do nothing, and user/creator will have to change their content with proper morphing.
Example: "Elbows_Size_min": [[1, 0.0, 0.0, 0.0]]
This is the morph for the size of elbows (at its minimum). There is just one vertex, index N°1, with zero displacement of the vertex. Creator has to sculpt this size later.

To create the file, user shows "Create morphs template" under "Model integration".

image

image

Then he must select manually the character he wants to work on. The base model for this character is showed, the others are hided. You have 3 things that can occur :

    The name of the the morphs file is already known ; user has already filled the name when creating the config file, In this case, the file can be checked, and if some needed morphs are absent, a warning is shown.
    The name is not in the config file, but user chooses an existing file in the list. Same as N°1 after that.
    The file has to be created. The user can fill a name, and create the file (below).

    image

    The main morphing name must be "unknown".
    The complete name of the file is shown.
    The user can create the file. It's saved automatically at the right place.

When the file is created or chosen, user can save the config file, but also check if the file has necessary morphs for working.

image

If "Check Morphs File" is clicked, a .txt file will be created (the name here would be "human_female_morphs.json.txt") with the result.

The template is created. To change, add or delete morphs, 3 tools exist, for simple and combined morphs:

image


