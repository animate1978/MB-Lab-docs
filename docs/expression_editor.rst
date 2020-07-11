Expressions Editor
==================

The Expressions editor is split up between two types of editing.

The Base Expression editor 

===============
Base Expression
===============

How does it work?

It allows you, to make your own base expressions (like ears down, brow up, and so on) or change the existing ones.

The files are under \data\expressions_morphs and the files work exactly like other morphs, each expression is a list of vectors that modify the location of vertices.

The way the files are handled are equal, except that there are mechanisms to separate in the engine the vectors for morphs and for expressions.

what are the differences?

Each expression has the same kind of name, starts with "Expressions_" then the body part, then the movement itself, and if it is for max movement or for min.

Base expressions can have _max values, or min/max, but not only _min.


**IMPORTANT**

.. note::

    Each file has an special expression, named (for example) "Expressions_IDHumans_max" with no value.
    It's a special name used as an identity, and used by the engine to know what the file is for.

=================
Facial Expression
=================

