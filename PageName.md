# Introduction #

This section describes the code structure of the sketch recognition module, its design philosophy, and possible improvements.


# Details #

The sketch module consists of 3 parts.  The first is the shape recognizer.  This part takes strokes (timestamped point data) and classifies them as a shape.  The second part is the item recognizer.  Items are objects which have physical properties.  The item recognizer takes the list of recognized shapes and determines if they make up some item.  The third and final step is the global recognizer (later, this may be called the action recognizer).  This step determines how items can interact with one another.  For example, this step looks at whether any anchors (X's) were drawn on any closed regions, and if they were, it removes the anchor from Obrik's list of items and marks the closed region as "anchored."  Now it will remain immobile when the simulation is run.

## Shape Recognizer ##

## Item Recognizer ##

## Action Recognizer ##