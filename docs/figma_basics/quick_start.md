---
layout: default
title:  Quick Start
parent: Figma Basics
nav_order: 6
---

{: .no_toc }

# Figma Basics

### Quick Start

![](../images/NEW_FIGMA_2024/quick_start.gif)

#### 1. Setting up a Design File

Create a new Design File
![](../images/NEW_FIGMA_2024/Create_new_file_2.png)

Give the file a name
![](../images/NEW_FIGMA_2024/name_project.png)


#### 2. Importing and IU Kit Library

Click on Assets & the click on the Libraries icon - change Current file to UI kits
![](../images/NEW_FIGMA_2024/lib_kits_select.png)

Add file for iOS18 UI kit
![](../images/NEW_FIGMA_2024/lib_add_fileOS_kit.png)

Close Library panel & the kit will now be added to the Asset panel on the left
![](../images/NEW_FIGMA_2024/Lib_added_close_2.png)

Double click the UI Kit icon
![](../images/NEW_FIGMA_2024/DD_click.png)

This will reveal all components in the UI kit
![](../images/NEW_FIGMA_2024/com_appear.png)

#### 3. Create UI Screens

We will now create a Frame (Screen) for our UI, click on File to change from Assets
![](../images/NEW_FIGMA_2024/go_to_file.png)

Click the Frame tool & select iPhone 16 Pro (402 x 874) this will match the size of our UI kit
![](../images/NEW_FIGMA_2024/select_frame_tool.png)

You will need to name your Frame, either do this on the label top left of the Frame or in the Layers panel on the left
![](../images/NEW_FIGMA_2024/name_frame_home.png)

Now change File to Assets in the left panel, within the UI Kit components Scroll down till you locate the System section & click to open
![](../images/NEW_FIGMA_2024/system_comp.png)


 Locate the Home Screen component and drag out on top of the Frame
![](../images/NEW_FIGMA_2024/drag_home_screen.png)


 Change back to File for Asset  this will make your Layers panel visible, check to see if the home screen component is inside the Home Frame - if it is, it will be underneath the Home Frame and indented - if it is above and/or not indented, then  drag and drop the Home screen component on top of the Frame layer.

![](../images/NEW_FIGMA_2024/screen_inside_frame.png)

You may need to drag-drop inside the Home Frame in  the layers panel on left
![](../images/NEW_FIGMA_2024/last_one_bigger.png)


Create another screen - Click Frame and the select iPhone 16 Pro (402 x 874) give it a name

![](../images/NEW_FIGMA_2024/new_screen.png)

Change File to Assets & click on Navigation Bars
![](../images/NEW_FIGMA_2024/select_nav_bar_1.png)

Click on Navigation Bar Compact 
![](../images/NEW_FIGMA_2024/nav_bar_compact.png)


This will preview the component & allow customisation - click insert
![](../images/NEW_FIGMA_2024/nav_insert.png)

As with the Home screen make sure the Nav Bar in inside the  Frame
![](../images/NEW_FIGMA_2024/make_sure.png)

Change File to Assets &within the UI Kit components locate Keyboards & click to open
![](../images/NEW_FIGMA_2024/keyboard_1.png)

Drag out iPhone Keyboard under screen 2
![](../images/NEW_FIGMA_2024/drag_keyboard.png)

#### 4. Interaction

On the Home screen hover your mouse over the Your App icon and continually click until you have selected this component. Then from the panel on the right change Design to Prototype
![](../images/NEW_FIGMA_2024/my_app_1.png)

Now hover your mouse over the My App component as you move the mouse a + in a circle will appear on the right side - click this and drag out a connection to Screen 2 - a popup panel will appear to allow customisation but this will have worked out what we intend to do
![](../images/NEW_FIGMA_2024/link_model.png)

This will create a hyperlink
![](../images/NEW_FIGMA_2024/app_link_1.png)

We now need to connect the Back button on Screen 2 so when clicked it will return to the Home screen - in this example we have not updated the Label, but you can update this to Back to give more meaning 
![](../images/NEW_FIGMA_2024/label_1.png)

As with the My app icon drag out a connection back to the Home screen
![](../images/NEW_FIGMA_2024/label_to_home.png)

We will now add an interaction on the Search field so when it is tapped it will display the Keyboard - click on the search field
![](../images/NEW_FIGMA_2024/click_search.png)


Make sure your in Prototype in the right panel & click `+`  in Interactions
![](../images/NEW_FIGMA_2024/add_inter_plus.png)

The Trigger will be On Tap, the action will be Open Overlay
![](../images/NEW_FIGMA_2024/open_over.png)

Within the Overlay you need to select Keyboard - iPhone
![](../images/NEW_FIGMA_2024/overly_key.png)

In Position change to Bottom Centre - this is where you want the component to move to when the interaction takes place
![](../images/NEW_FIGMA_2024/bot_ctr.png)

The Animation needs to be changed to Move In  - this is to set up an off screen interaction
![](../images/NEW_FIGMA_2024/move_in.png)

And finally, you need to check Close when clicking outside, this will mean when the user taps off the keyboard it will close
![](../images/NEW_FIGMA_2024/overly_final.png)

We can now run the prototype to see how the interactions work.
![](../images/NEW_FIGMA_2024/ready_proto.png)


The device your prototype will present within, will be the original device you selected at the beginning of your project when setting up your first Frame. If for any reason you want to change it to another device - you can do this through the Prototype Settings - in this example, we won't change anything as it will prototype to the iPhone 16 Pro dimensions

Click the the Play (Run) button.

The prototype will open up in a new browser window and you can test the links and interaction alternatively it will be available on your Figma mobile device app

![](../images/NEW_FIGMA_2024/run_Proto_2.png)


![](../images/NEW_FIGMA_2024/quick_start.gif)



