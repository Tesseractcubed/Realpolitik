README file.

This project is an attempt to rebuild Realpolitik into a program that does 3 parts: 
interface with players, adjudicate, and peer to peer / peer to server communication. 
The version will be a full number upgrade should it publish.

License: Creative Commons Attribution Share Alike 4.0 International
(^For working purposes)

Measurable Goals: 
Backwards compatability with Realpolitik, probably one way upgrade of files. (Medium)
Set standards to load games, maps, rulesets, and adjudicators into program. (Main goal)
Create logic to load datapacks synchronously across platforms.
C++ and python cross compatability for rulesets.
Start at windows / linux application, expand outwards.
Functionally equivalent at minimum to Realpolitik (Latest Version)

New File Types:
.dpy - Game file for diplomacy. Holds a header with information about how the
    game was created, and also the type of game file. A few different modes 
    (tracking vs turn state) of data storage will be included, some easier than others.
.dpymap - Map file for diplomacy. Defines home centers, starting positions,
    variant specific info, etc. Lays out map data (should eventually create an 
    svg to .dpymap tool) in a computer readable format. Unlike Realpolitik, the
    spaces are stored from svg to be rendered as a shape that is clickable.


Version History:

2.0.0.1
First alpha version. Lots of work ahead.