Modding Getting Started
=======================

Mod Locations
--------------

* **Windows:** ``%USERPROFILE%\AppData\Roaming\songsofsyx\mods``
* **Linux:** ``~/.local/share/songsofsyx/mods``
* **MacOS:** ``TODO``
* **Steam:** ``<steam-library-location>\steamapps\workshop\content\1162750``

Mod Structure
-------------

The structure resembles the games configuration folders structure.

::

    /Your Mod Name
    |-- V63
    |   |-- assets
    |   |-- campaigns
    |   |-- examples
    |   |-- saves
    |   `-- script
    |       |-- _src
    |       |   `-- your-mod-sources.jar
    |       `-- jar
    |           `-- your-mod.jar
    `-- _info.txt

* **Your Mod Name:** Folder containing all necessary files for your mod. Should be named after your mod.
* **V63:** Version of the game your mod is for.
* **assets:** Images, sound, configuration, texts and so on go here.
* **campaigns:** TODO
* **examples:** TODO
* **saves:** TODO
* **script:** Java code of your mod

Creating a Mod
--------------

Dependent on what you want to do with the game you may require an integrated development environment (IDE) or just a simple editor.
The game comes with configuration files, which can easily be edited with a simple editor. For more complex modification you'll need an IDE though.

Get an Editor
*************

* `VS Code <https://code.visualstudio.com/Download>`_ (recommended)
* `Sublime Text <https://www.sublimetext.com/download>`_
* `Notepad++ <https://notepad-plus-plus.org/downloads/>`_


Get an IDE
**********

If you are experienced with Java you may already have your preferred IDE. These are the two most used ones:

* `Intellij IDEA Community Edition <https://www.jetbrains.com/idea/download/>`_ (recommended)
* `Eclipse <https://www.eclipse.org/downloads/>`_








