MB-Lab Modules
==============

The Modules of MB-Lab are the Python files, the engines that run under the hood.

============
Main Modules
============

The main modules are derived from the original code of **ManuelBastioniLAB ver 1.6.1**

Since the beginning of the fork this code has evolved and expanded over time.

-----------
_ init _.py
-----------
This is the core of the addon.

* Function calls
* GUI Elements

-------------
algorithms.py
-------------

Contains various functions for every engine.

------------------
animationengine.py
------------------

Handles the animation import and assigning to skeleton

* Retargeting
* Identifies Bones
* Similar functions (expand)
* Loads BVH files, saves and loads poses.

-----------
humanoid.py
-----------

Handles much of the character changing functions including Auto-Modelling.

-----------------
materialengine.py
-----------------

This is where the image textures get loaded and applied to nodes

--------------
morphengine.py
--------------

This is where the morphs of the character are loaded from JSON files


--------------
proxyengine.py
--------------

Handles the Proxy Fitting functions

-----------------
skeletonengine.py
-----------------

Loads and applies the skeleton (either FK or IK) to the character

===========
New Modules
===========

The new modules have been added over time to support the main code.


-------------
hairengine.py
-------------

This is the code that applies the hair to MB-Lab characters

-----------
file_ops.py
-----------

Contains code that handle file operations

---------------
morphcreator.py
---------------

Module to create and edit the JSON morph library

---------------
material_ops.py
---------------

Contain functions that control some of the materials in MB-Lab

-------------
object_ops.py
-------------

Contain functions that help in object manipulation

----------
facerig.py
----------

This is the code that controls the face rig

--------------
preferences.py
--------------

Related to the Auto-updater along with other options for Preferences

--------
utils.py
--------

Contain helper code for other engines

---------------------
creation_tools_ops.py
---------------------

Main code for the MB-Dev framework

---------------------
expressionscreator.py
---------------------

Code to help create new expressions

----------------
jointscreator.py
----------------

Code to make the joints JSON

------------------
measurescreator.py
------------------

Creates the measurement JSON files

---------------
skeleton_ops.py
---------------

Helps in the creation of the Joints and Skeleton

-----------
transfor.py
-----------

Contains code for the transformation files

-----------------
vgroupscreator.py
-----------------

Creates the Vertex Weight JSON files

-----------
mesh_ops.py
-----------

Functions to help with the mesh editing

-----------
node_ops.py
-----------

Code to help with the Hair shader creation

------------
numpy_ops.py
------------

Code to place the Hair JSON data into compressed NPZ files

---------------------
humanoid_rotations.py
---------------------

Contains code for the human rotation limit feature

=====================
Addon Updater Modules
=====================

The Addon Updater code was adopted from CGCookie's original code.

----------------
addon_updater.py
----------------

The main code for the auto-updater

--------------------
addon_updater_ops.py
--------------------

Contains functions and the settings for the auto-updater