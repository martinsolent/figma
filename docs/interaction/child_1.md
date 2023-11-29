---
layout: default
title: Overlay Draw
parent: Interaction
nav_order: 2
---

{: .no_toc }

# Overlay Draw

## Overview

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=c7a51eea-3ce5-46c0-9a2b-af6301582dde&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>


#### Create a Draw Overlay Interaction

**Create your Components**

1. Create a title bar -with a menu icon, a title and an icon in this case a search/magnifying glass

![](../images/draw_1/draw_2.png)

2. Now we will create a label item this will consist of the frame with an ellipse shape containing an avatar and the name label.

![](../images/draw_1/draw_3.png)

3. Create a bottom Stroke with the colour black

![](../images/draw_1/draw_4.png)

4. Text justified left - centred vertically and fixed size

![](../images/draw_1/draw_5.png)

5. Create a list item save it as a component then create a variance with the second variant this will be the hover state so change the background colour

![](../images/draw_1/draw_6.png)

![](../images/draw_1/draw_8.png)

6. You can add interaction either do a while hovering interaction or a mouse enter leave

![](../images/draw_1/draw_9.png)

![](../images/draw_1/draw_10.png)

7. You will need to create a component to be the drawer navigation which will come in from the right of the screen this has a header with an avatar and a list of items

![](../images/draw_1/draw_11.png)

![](../images/draw_1/draw_12.png)

![](../images/draw_1/draw_13.png)

![](../images/draw_1/draw_14.png)

8. You can now copy out an instance of your list item and duplicate it before creating it as a component

![](../images/draw_1/draw_15.png)

9. You will now have the following components in the asset panel

![](../images/draw_1/draw_16.png)

**Now publish (this vwill only work if in a Teams Plan)**

Once published we can create a new project/ Figma File and import if you do not have a Teams Plan you can use the in your Figma file.

![](../images/draw_inter/asset_publish.png)

#### Using your Components in a UI Layout
Create a new Figma File (Project) if you have a Teams Plan otherwise create a new page and create you UI layout on it.

1. Create a new **Frame 360 x 800**
Call it **Home** 

![](../images/draw_inter/2.png)

2. The Assets (Components) have already been created and/or imported as a shared library into out File (Project)

Drag out the **titlebar** on to the **Home** Frame and position

![](../images/draw_inter/3.png)

3. Drag out **List**  component and position

![](../images/draw_inter/drag_list.png)

4. Resize by dragging down the **List** component to make it **1659** high. It this case this is the "height" of the component that has been created to allow for a scroll affect

![](../images/draw_inter/5.png)

![](../images/draw_inter/1659.png)

5. Now select the **titlebar** in the **Properties** panel switch **Design** to **Prototype**

Within the **Scroll Behaviour** section change to **Fixed (stay in place)**

![](../images/draw_inter/6.png)


![](../images/draw_inter/fixed_close.png)

6. Change **Overflow** to **Vertical**

![](../images/draw_inter/8.png)

7. Now in click Run to test the interaction

The Device has been set at **Android Large**

![](../images/draw_inter/run.png)

Your interaction should behave like this

![](../images/draw_inter/scroll_gif.png)

**Customise the layout**

All **Avatar** images are the same, we need to change this. As we have called all of the Avatar we can install and use the

**Select Similar Plug-in**
[Select Similar Plug-in](https://www.figma.com/community/plugin/792767780551514994) 

Select one of the Avatar images.

Then right mouse to bring up yje plugins and select **Select Similar Plug-in**

Check **Layer Type** and the Select **Layer Sample** button

Then click the **Select Similar** button

![](../images/draw_inter/new_avatar.png)

This will select ALL layers called **Avatar**

![](../images/draw_inter/selected_new.png)

Now to change the images using the User Profile [User Profile Plug-in](https://www.figma.com/community/plugin/749945157855564842/User-Profile)

Once installed, right mouse and select **User Profile**

![](../images/draw_inter/user_pro.png)

Select **Male & Female** and click **Insert Random Images**

![](../images/draw_inter/profile_2.png)

The image will be replace by random images

![](../images/draw_inter/done_1.png)

**Add a left Side Draw Overlay**

1. Drag **Draw** Component from the **Asset** Panel

![](../images/draw_inter/drag_draw.png)

2. Slect the Hamburger Menu icon on the Titlebar on the Home Screen

![](../images/draw_inter/select_ham.png)

In the Prototype Panel on the Interaction section, click on tap

![](../images/draw_inter/over_1.png)

Change **None** to **Open Overlay**

![](../images/draw_inter/over_2.png)

Select **Draw**
Move in Right
And **Top Left**


![](../images/draw_inter/move_in_1.png)

![](../images/draw_inter/move_in_2.png)

Final run the prototype again to test and check on your phone using the Figma app.

