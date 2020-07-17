Modeling Process
================

The process of developing a character model in MB-Lab

=====
Tools
=====

Since **version 1.6.0**, the character production pipeline is divided in two different steps.

* **Creation** phase. In this part of the pipeline the character is initiated, and then morphologically defined setting the parametric values of age, muscles, mass, face details, measures, skin shader, skin textures, ecc. This phase also includes the use of quick characterization tools, as the random generator, the auto-modeler and the character library. During the creation process it's also defined the rest pose and the type of rigging to use (for example with inverse kinematic or not). The character is in "creation" mode until it's finalized.
* **Post-Creation** phase. With the finalization, the creation phase ends, and the character is converted in a standard Blender model ready to be imported and used in production scenes. The creation GUI is automatically replaced by the "after-creation" GUI, where the lab enables a set of useful animation and finishing tools: loading of poses and motion data (with automatic retarget), expression editor, automatic fitting of proxies (clothes, hair, etc)

**MB-Lab 1.7.8**

* **MB-Dev** This is a new framework of tools to edit existing models, as well as create new base characters for MB-Lab.

MB-Lab is designed to create a high quality character rigged and ready for animation using a parametric approach.

**What are modeling parameters???**

Parameters are physical features that can be modified by increasing or decreasing a numerical value.

Examples of parameters are the numerical values for noticeable features like weight, height, muscle and mass percentages or for detail features like nose length, eyes distance, mouth width.

