---
layout: default
title: Drop-down walk-through
parent: Dropdown Menu
nav_order: 2
---

{: .no_toc }

# Drop-down menu walk-through



Create a new Figma project create a page for components and another page for the layout

![](../images/drop/drop_1.png)

## Setting up icons

On the component page add two icons for up and down

![](../images/drop/drop_2.png)

Select both of these icons and convert them into components

![](../images/drop/drop_3.png)

![](../images/drop/drop_4.png)

## Create a Menu title bar

Now create a frame 120 x 32, change it to Auto Layout, aline centre middle and change the height and width from hug to fixed. Name the frame menu_bar

![](../images/drop/drop_7.png)

Select the text tool or press `T` on your keyboard type in the word Menu at 12 point font size

![](../images/drop/drop_8.png)

![](../images/drop/drop_9.png)

Select the back Parent frame and change it fill colour to black

![](../images/drop/drop_10.png)

Select the text label and change the fill colour to white

![](../images/drop/drop_11.png)

From the acid panel drag out the down arrow icon onto your frame

![](../images/drop/drop_14.png)

You can increase the gaps between the Menu text and the icon by dragging out the purple line in between the items

![](../images/drop/drop_15.png)

![](../images/drop/drop_16.png)

Now select the menu text box. In the properties panel on the right in the content section click on the icon to create a component properly

![](../images/drop/drop_17.png)

From the pop-up name the component property Menu Bar Label and click great property

![](../images/drop/drop_19.png)

Now select the icon in the properties panel on the right click on the image swap property icon

![](../images/drop/drop_20.png)

In the pop-up name the property icon

![](../images/drop/drop_21.png)

We will now take time to organise our icon components. To group them together type `icon / ` before their names.

![](../images/drop/drop_23.png)

Check the Assets panel and you will see the icons will be grouped together

![](../images/drop/drop_24.png)

## Creating a List item

We will now create a list item for the drop-down list. Create a frame 120 x 32, give it a light grey colour, auto layout - centred left with the width and height fixed (not hug)

![](../images/drop/drop_28.png)

It's like the textual `T` on keyboard type in Item

![](../images/drop/drop_29.png)

Select the frame and convert it into a Component

![](../images/drop/drop_31.png)

Now created into a Variant

![](../images/drop/drop_32.png)

Select the top Variant item (Default) in properties panel on the right in the  Variant properties change Property-1 name to State

![](../images/drop/drop_33.png)

Now select the second variant change it State name to hovered

![](../images/drop/drop_34.png)

Now, change the colour of the second Variant - this will be the colour it will turn into when the mouse is hovered over this item

![](../images/drop/drop_35.png)

We will need to put a stroke at the bottom of each of the variant items to separate them in the list. Shift-click both the variant items

![](../images/drop/drop_39.png)

Add a black stroke.

![](../images/drop/drop_40.png)

Change the stroke from All to Bottom

![](../images/drop/drop_41.png)

## Add a list item group to the menu bar

Click on the Assets panel and drag out an instance of the menu bar

![](../images/drop/drop_36.png)

Now drag out an instance of the Item component

![](../images/drop/drop_37.png)

Who is the item so it sits directly underneath the menu bar

![](../images/drop/drop_42.png)

Hold hold and shift on your keyboard to drag copy of the list item

![](../images/drop/drop_45.png)

You can press Command+D on an Apple Mac or Control+D on a PC to duplicate a third item

![](../images/drop/drop_46.png)

Shift click each of the 3 items to select them - either on the canvas or in the layer outline

![](../images/drop/drop_47.png)

Group these items together either by right mouse-clicking and selecting Group Selection or on a PC Command+G and on a PC Control+G

![](../images/drop/drop_48.png)

Name the group list in the layers outline

![](../images/drop/drop_49.png)

Select both the group list and the menu bar then create a Component - call this new Component dropdown

![](../images/drop/drop_50.png)

Now turn the Component into a Variant and select the top Default Variant

![](../images/drop/drop_51.png)

In the property side panel in the variance section rename property to open

![](../images/drop/drop_52.png)

Do you name default to false

![](../images/drop/drop_53.png)

Your layer outline will now look like this

![](../images/drop/drop_54.png)

A turn off the list layer on this variant

![](../images/drop/drop_55.png)

Now select the second variant (bottom) and range is open property state to true

![](../images/drop/drop_56.png)

We now need to swap out the down arrow for the up arrow. Select the arrow icon and in the properties change it for the up icon

![](../images/drop/drop_58.png)

![](../images/drop/drop_59.png)

Go to the layout page, create a new frame and drag out an instance of the Drop-down Component onto this frame

![](../images/drop/drop_60.png)

Use the toggle switch in the properties panel to open close the drop-down menu

![](../images/drop/drop_61.png)

![](../images/drop/drop_62.png)

## Prototyping and creating interaction

We will now create the hover interaction on the list item. Select the top varian. Switch to Prototype in the right panel then drag out a connection to the second hovered variant.

Change click to while hovering - and the State should be displaying hovered

![](../images/drop/drop_63.png)

Click on the top down icon on the top variant drag out a connection to the bottom variant - On click and Change to interaction with the toggle switch for open switch on

![](../images/drop/drop_64.png)

Click on the up arrow icon on the bottom variant and set up an interaction for On click change with the toggle switch for open off

![](../images/drop/drop_65.png)

Select the whole of the bottom variant

![](../images/drop/drop_66.png)

Click on the plus icon next to interactions in the side panel, set up Mouse Leave and Change to with Open toggle off

![](../images/drop/drop_67.png)

Now go to your layout page and run the prototype it should now be able to open and close and the rollovers should work on the list items

![](../images/drop/drop_68.png)
