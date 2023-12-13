---
layout: default
title: Linking Screens
parent: Interaction
nav_order: 6
---

{: .no_toc }

# Linking Screens

We are going to create 3 screen within 3 buttons on each and link them together.

![](../images/linking_screens/1.png)

We will create a new Figma file and import [Material Design Icons from Figma Community](https://www.figma.com/community/file/1014241558898418245) and libraries that have been created in [previous walk-throughs](https://martinsolent.github.io/figma/docs/comp_props/child_4.html)



### 1. Set-up

Create a new Figma file and give it a name

Re-name Page 1  Layout

Create a new Frame - **Android Small (360 x 640)** from Template in right hand Properties Panel 

Name the Layer **Home**

![](../images/linking_screens/ls_5.png)

In the left panel click on Assets and then the Library icon import

Import:

[Material Design Icons from Figma Community](https://www.figma.com/community/file/1014241558898418245)
and if studying with Solent import these: **variant_properties_Propstar_23** & **Title_Bar**

![](../images/linking_screens/4.png)

### 2. Layout

Click on **Assets** in the Left panel and drag out the Title Bar Component onto the screen and position

![](../images/linking_screens/ls_7.png)

 create a new frame directly below the title bar approximately 360 x 234 - Although this can be adjusted later.

  Rename the frame image in the layers panel.

   With the Frame still selected - Right Mouse Click on the baseboard, go to plug-ins, and select on **UnSplash** - (this plug-in will need to have already been set up from **Figma Community**)

![](../images/linking_screens/ls_8.png)

 Select an image and insert

![](../images/linking_screens/ls_9.png)

 You may need to adjust with the help with the **Image Properties** in the right panel.

![](../images/linking_screens/ls_10.png)

 Again from the asset panel on the left, drag out the button component.

![](../images/linking_screens/ls_11.png)

 Then select **Layers** in the panel on the left

![](../images/linking_screens/ls_12.png)


With the Button/Layer Instance selected

![](../images/linking_screens/ls_13.png)

In the **Component Properties** section in the right panel

![](../images/linking_screens/ls_14.png)

As we have imported, the Material Design Icons, we can now can select and swap an icon - In this case, we will search for **home** and come up with a suitable icon.

![](../images/linking_screens/ls_15.png)

![](../images/linking_screens/ls_16.png)

 Again with it still selected within the component properties we will update the label name to home and press enter

![](../images/linking_screens/ls_17.png)

![](../images/linking_screens/ls_18.png)

Now in the layers panel on the left, update the button name to **Button_home**

![](../images/linking_screens/ls_19.png)

 With the button selected change **Design** to **Prototype** in the **Properties** panel on the right

Set up a **While Pressing** **State** to **pressed** (This was set up within the imported library)

![](../images/linking_screens/press.png)

 Press `alt` and `shift` on your keyboard and drag copy two more buttons

![](../images/linking_screens/ls_20.png)

Repeat the process above for changing the icon and the label for each of the copied buttons

**Information**

**Contacts**

![](../images/linking_screens/ls_23.png)

 Rename the layer names of each of the buttons to match the content, you may need to drag to rearrange the hierarchy of each of the elements on the screen

![](../images/linking_screens/icon_1.png)

Now we will run to preview how the buttons respond when pressed

![](../images/linking_screens/prot.png)

OK, all look good

![](../images/linking_screens/pressing.gif)

Now we need to copy two more screens. Make sure you have the **Home** Frame selected hold `alt` and `shift` on your keyboard and drag two the right to copy to more screens.

![](../images/linking_screens/copy.gif)

 now you need to rename the layers to match the content

Second frame layer will be **info** and the third frame will be **contact**

You will need to re-order the hierarchy to match what on the pasteboard

![](../images/linking_screens/re_name_1.png)




![](../images/linking_screens/re_name_2.png)

 Switch to **Prototype** in the right **Properties** panel.

  Click on the **Information** button on the **Home** screen. Click on the `+` icon and drag out a link to the `Information` screen.

![](../images/linking_screens/drag_1.gif)

 Repeat with the contact button and drag out a link to the **Contact** screen

![](../images/linking_screens/drag_2.gif)

Now link the buttons on the **Information** screen

![](../images/linking_screens/drag_3.gif)

 and finally link the buttons on the **Contact** screen

![](../images/linking_screens/drag_4.gif)

Now change the images on the **Information** and the **Contact** screens using the **Unsplash** plug-in. You will need to make sure you've selected the image frame on each of the screens before launching the plug-in

![](../images/linking_screens/add_1.png)

![](../images/linking_screens/add_2.png)

 Finally test out your prototype click Run/Play button top right of your screen and test out the button interactions

 ![](../images/linking_screens/final.gif)