---
layout: default
title: Pixel Perfect 1
parent: Pixel Perfect
nav_order: 2
---

{: .no_toc }

# Pixel Perfect 1 - Icons
 Creating icons is more associated with general design or illustration, but is important for a digital designer/UX to understand the core principles of how an icon is constructed and implemented within a UI layout and more importantly how it structure relates to A given design system.

Creating a family of icons is time-consuming, although Figma can create and work with Vector Images these are basic in comparison to what you would find in [Adobe illustrator](https://help.figma.com/hc/en-us/articles/360040030374-Copy-assets-between-design-tools) and also there is a large amount of free to use icons available through [Figma Community.](https://www.figma.com/community) so it would be best to use these rather creating your own but it is important to learn how to make an icon. Here we will import an icon from [Material Design (Community)](https://www.figma.com/community/file/1014241558898418245) which can be found in [Figma Community.](https://www.figma.com/community)


#### 1. Set-up

We will create a new Frame on the Icon page, we will then bring in an icon from Material Design (Community) plug-in. We will use this to set up guides and copy icon.

1. On the **Icon-Create** page
2. Select the **Frame** Tool from the Toolbar or press `P` on keyboard
3. Resize to **100x50**
4. Name it **Make-icon**

![](../images/pixel_perfect/icon-set-up/icon-set_3.png)

1. Right-Mouse on the pasteboard
2. From the plug-ins select material design (Communinity) If you do not have this plug-in installed select manage plug-ins and
3. Search for it then run/install

![](../images/pixel_perfect/icon-set-up/icon-set_4.png)

4. From the icon panel search for **Power** then click on the **Power Switch** icon which will then appear on the pasteboard

![](../images/pixel_perfect/icon-set-up/icon-set_6.png)

**Tip:** With **Material Design** icons they have a bounding box (other icons may not have a separate bounding box) with the icon itself is inside - So there is a Container and then the actual vector icon inside this container the container box makes life easier to work getting spacings right with irregular shaped icons. 

Because of the Container (bounding box) it's a common mistake when moving the icon that you move either the container without the icon, or move the icon out of the container - **Also when it comes to icons do not scale them just use them as they are when it comes to material design the icons or 24x24**

![](../images/pixel_perfect/icon-set-up/b_box.gif)

 So the best way to move an icon is by clicking and holding the **name label** top left of its container

![](../images/pixel_perfect/icon-set-up/icon_move.gif)


#### 2. Create Copy Guides

 We will set up some guides using the Icon as a template

The Zoom drop-down menu on top right not only had settings to zoom in and out but you can also switch on the **Pixel grid** and also **Rulers** and toddle **Snap to grid.**

To help us with the layout switch on **Pixel grid**

 ![](../images/pixel_perfect/guides/zoom_menu.png)

To drag out Guides you must have Rulers switch on

![](../images/pixel_perfect/guides/drag.gif)

Drag out 3 guides to align up as below:

![](../images/pixel_perfect/guides/drag_1v.png)

We need a guide for Top, Bottom & Centre of the container

Make sure the container layer is select to show the outline - the container is **24x24** so we need a centre guide at **12**

![](../images/pixel_perfect/guides/drag_2v.png)


Finally we need a guide on the ontented cut points of the circle

Switch OFF **Snap to pixel grid**

![](../images/pixel_perfect/guides/snap_off.png)

Then drag a guide as below:    

![](../images/pixel_perfect/guides/drag_3.png)

Now drag out a Rectangle shape (select in the Toolbar or press `R`) on the left of the example icon size it to **24x24**

![](../images/pixel_perfect/guides/24_tempv.png)

Make sure **Snap to pixel grid** is switch ON and drag guides out as below:

![](../images/pixel_perfect/guides/rect_1v.png)


Finally delete the Rectangle shape

Then drag 2 guides 4 blocks in for the left & right outside guides

![](../images/pixel_perfect/guides/4_in.png)


#### 3. Create Copy

First of all we will create a **24x24px** container for our icon. Not all icons have a container.

1. Select the Frame Tool from the Toolbar Press `F` on your keyboard.

2. Drag out from the centre guide while holding `Alt` and `Shift` on your keyboard this will create a perfect square and created from the centre.

3. We will add a Stroke (border) **0.1pt** Just as a guide which will be switched off at the end.

![](../images/pixel_perfect/PPGIF1.png)

Inside this container we will create a circle using the **Ellipse** tool.

1. Select **Ellipse** tool from the Toolbar which is embedded in the shapes or press `o` on your keyboard 

2. Drag out from the centre while holding `Alt` and `Shift` on your keyboard this will create a perfect circle and created from the centre.

3. Set the Stroke to **2pt** and turn off Fill colour.

4. Make sure the Stroke is Centred

![](../images/pixel_perfect/PPGIF2.png)

 #### 4. Cut Off Top of Circle

![](../images/pixel_perfect/PPGIF3.png)

With the circle selected press `Return` on your keyboard this will bring up the Path in the centre of the stroke.

![](../images/pixel_perfect/pp_39.png)

Select the **Pen** tool from the Toolbar or press `P` on the keyboard.

Using the guides from the example we are copying click two points to cut off the top of the circle - You do this by clicking on one point on the right..

![](../images/pixel_perfect/pp_40.png)

...then moving across to the opposite side and clicking the second point - This will draw a line across the top of the circle.

![](../images/pixel_perfect/pp_41.png)


Now click on the top Vector point of the circle and press delete

![](../images/pixel_perfect/pp_43v.png)

This will delete the very top of the circle.

![](../images/pixel_perfect/pp_44.png)

Now click on the centre Vector point on the line you have just created and press delete

![](../images/pixel_perfect/pp_45.png)

This will chop off the top of the circle.

![](../images/pixel_perfect/pp_46.png)


 #### 5. Add Final Line
 
 Finally with the Line Tool - find this in the Toolbar embedded in the shapes or press `L` on your keyboard drag out the line as per guides and give it a stroke of 2pt.

 ![](../images/pixel_perfect/pp_47.png)

![](../images/pixel_perfect/PPGIF4.png)

![](../images/pixel_perfect/pp_47.png)

![](../images/pixel_perfect/pp_48.png)

![](../images/pixel_perfect/pp_49.png)

Delete Container Stroke

![](../images/pixel_perfect/guides/del_stroke.png)


![](../images/pixel_perfect/guides/done.png)


