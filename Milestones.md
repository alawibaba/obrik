# Milestones #
Here we list the next milestone we would like to achieve and the milestones we have already completed.  The most recent milestone is on top.


---

## v0.1.1 ##
We plan to add a user-study-type module that will record the use of Obrik, so we can record how people use Obrik and improve the system based on the recording.


---

## v0.1 ##
We plan to have a canvas that has simple gravity and the ability to draw boxes and anchors to boxes.  Hitting something like a "play button" will start the simulation.  We plan to integrate this with [Swing](http://java.sun.com/docs/books/tutorial/uiswing/) and [JBox2D](http://www.jbox2d.org/).  Hopefully we can limit these two to be the dependences of this project.

### 2009/08/30: ###
We got out v0.1!  You can check it out with:
```
svn co http://obrik.googlecode.com/svn/tags/v0.1/ ./obrik-java-0.1
```
There are no known bugs.  Please report one if you find one.

Also, we added a `JApplet` UI, so you can host it on your webpage (see `web/` folder for example of using the HTML `<applet>` tag).