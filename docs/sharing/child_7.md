---
layout: default
title: Prototyping - Text Fields
parent: Prototyping
nav_order: 8
---
{: .no_toc }

# Prototyping - Text Fields

Creating a prototype in Figma that allows users to fill in text fields can be challenging. While there are solutions available through plugins and UI components in the Figma Community, these can be difficult to implement, especially for simpler projects. The most straightforward way to simulate a user adding text to a field is to mimic the experience.

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%; margin: 24px 0;">
	<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=b479f63d-53d9-4529-b62e-b225016483ce&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" style="border: 1px solid #464646; position: absolute; top: 0; left: 0; width: 100%; height: 100%; box-sizing: border-box;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player" title="Figma Prototyping - Text Fields"></iframe>
</div>
 

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%; margin: 24px 0;">
	<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=9526b42f-4402-4e28-85a5-b39301612981&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" style="border: 1px solid #464646; position: absolute; top: 0; left: 0; width: 100%; height: 100%; box-sizing: border-box;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player" title="Figma Text Prototype Text Input"></iframe>
</div>

 
<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%; margin: 24px 0;">
  <iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=2baee47b-01de-471f-9ddf-b22501802ea1&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" style="border: 1px solid #464646; position: absolute; top: 0; left: 0; width: 100%; height: 100%; box-sizing: border-box;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player" title="Prototype - Text Field Walk-through"></iframe>
</div>

### Plugin Resources

**Plugins for adding text into fields on Figma prototypes (Figma Community)**

1. **Interactive Text Input Fields (mobile & desktop)**  
	![Interactive text input fields screenshot](../images/txt_plugs/Picture%201.png)  
	[Open on Figma](https://www.figma.com/community/file/1327351869279090015/interactive-text-input-fields-for-keyboards-mobile-and-desktop)

2. **Text Inputs for Prototypes**  
	![Text inputs for prototypes screenshot](../images/txt_plugs/Picture%202.png)  
	[Open on Figma](https://www.figma.com/community/file/1253625006223812080)

3. **Google reCAPTCHA v2 (checkbox & invisible badge)**  
	![Google reCAPTCHA components screenshot](../images/txt_plugs/Picture%203.png)  
	[Open on Figma](https://www.figma.com/community/file/882757166127187575)

4. **Interactive Text Fields – Typing with Keyboard**  
	![Interactive keyboard typing fields screenshot](../images/txt_plugs/Picture%204.png)  
	[Open on Figma](https://www.figma.com/community/file/1437033953557395543)

**Download:** [Text Input Figma Plugins PDF](../images/Plugins%20for%20adding%20text%202%20fields%20in%20Figma%20prototypes.pdf)


## Overview

We are going to create three screens that simulate typing an email address and password to log into an application. When it comes to user testing, it may not always be necessary to simulate something as basic as a login; however, this serves as an example of how you can simulate entering text into fields, which may not be possible in a Figma prototype.

![](./text_update/all_text_screens.png)


### Set-up

In your Projects or Dashboard click **Create** and select **Design**

![](./final_text_picts/create_newDes_file.png)

* Make sure you **name your design file.**
* Select **Assets** in the left panel
* Click on the **Library icon** to add Design System Libraries 

![](./final_text_picts/name_get_libs.png)

#### Add Libraries (Design Systems)

We will add two Design System Libraries which are availble through **Figma Comunity**

Search for **Material 3 Design Kit** & **Simple Design System** & click on **Add to file** and close **Manage Libraries** panel.

![](./final_text_picts/libs_add_file.png)

These libraries will appear and their components be available from the Assets panel

![](./final_text_picts/libs_iassets.png)

In the right panel change Assets **back** to **File**

### Adding Design System Kit to Components

We've already added our design kits to the Assets, so switch from File to Assets in the left panel.

![](./text_update/files_assets.png)

If you have several Design System Kits in your Assets, you'll need to select the one you want to search.

![](./text_update/lib_switch_assets_MD.png)

**Add the Status Bar Component**

Search for ``Building Blocks/status-bar`` in the Material design 3 library

![](./final_text_picts/mat_des_search_status.png)


Now drag out Status Bar onto the screen & postion it at the top

![](./final_text_picts/drag_status.png)

You will need to switch centre camera off as it might conflicted withe the on in the prototype preview

![](./text_update/cam_on.png)

In the properties panel on the right in the Status Bar section switch of Camera Cutout

![](./text_update/can_off.png)

**Add the App Bar Component**

Search for ``App bar`` in the Material design 3 library

![](./final_text_picts/search_app_bar.png)

Drag **App Bar** onto the screen

![](./final_text_picts/drag_app_bar.png)

**Add the Bottom App Bar Component**

Search for ``Bottom app bar`` in the Material design 3 library

![](./final_text_picts/search_bot-bar.png)

Drag out the ``Bottom app bar`` to the bottom of your screen

![](./final_text_picts/drag_bot_bar.png)

**Re-order layers**

The order of your layers might not match the design hierarchy shown on your screen

![](./final_text_picts/out_line_order_wrong.png)

If that's the case, you'll need to reorder the layers by dragging them into the correct order

![](./final_text_picts/show_out_line_order.png)


**Add Log in Form Field**

Search for ``Form Log In`` in the **Simple Design**

![](./text_update/add_email.png)

![](./text_update/)

Screen 1 is now complete.

Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181019.png)

Press ``Alt and Shift`` on your keyboard, hover over Screen 1, and drag to the right to create a copy. Rename this new screen to Screen 2, either by updating the frame label or within the Layers panel.


Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181147.png)

Now, hover over Screen 2, then hold down the Alt and Shift keys on your keyboard and drag to the right to create a copy—this will become Screen 3.

Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181252.png)



ALT drag Screen 2 to right to copy it - then re-name it Screen 3

In the Layers panel, make sure the frames for each screen are arranged in order: one, two, and three. If they’re not, drag them into the correct sequence. It’s a good idea to close each frame before you do this, to make organising them easier.

Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181335.png)

On screen 3 highlight the log-in component delete it

Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181342.png)

 Click on Assets in the right panel

Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181348.png)

Select the simple design system then search for Review Card

Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181426.png)

Then drag and drop it onto screen 3 adjust if necessary

![](../images/text_input_n/Screenshot%202025-11-18%20181437.png)

 In the panel on the right click on Files to see the layer list You may need to open up screen 3
Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181451.png)

In the right Properties panel change Design to Prototype
Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181506.png)


Open Screen 2 in the layers
Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181644.png)

Click on ``Form Log In`` to highlight this component, press ``Shift 2`` on your keyboard to zoom in
Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181702.png)

 Select the e-mail input field either by selecting it in the layers or within the design
Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181710.png)

In the properties on the right change the value type From Default Placeholder and in the value field type in a fake e-mail address

Delete Swop:

![](../images/text_input_n/Screenshot%202025-11-18%20181826.png)

This will now appear in the e-mail field now select the password input field either in the layers or within the design
Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181837.png)


Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181930.png)

 With it selected in the properties change value type from default to placeholder
Delete Swop:
![](../images/text_input_n/Screenshot%202025-11-18%20181942.png)

 In the value field type in four stars ``****`` to represent a password. This will now appear in the password field
Delete Swop:

![](../images/text_input_n/Screenshot%202025-11-18%20181947.png)


Delete??

![](../images/text_input_n/Screenshot%202025-11-18%20182009.png)

Delete??

![](../images/text_input_n/Screenshot%202025-11-18%20182019.png)

c

![](../images/text_input_n/Screenshot%202025-11-18%20182040.png)

![](../images/text_input_n/Screenshot%202025-11-18%20182049.png)

Highlight the Log In  component on screen 2, you will see a blue circle with a + click this

![](../images/text_input_n/Screenshot%202025-11-18%20182103.png)

 and drag out a flow arrow to screen 3 an interaction pop-up will appear with the default settings, you can now close this

![](../images/text_input_n/Screenshot%202025-11-18%20182112.png)

We will now create a link back to the home screen, click on the hamburger icon for the blue circle with + to appear. (On a real design you would change this to a more appropriate icon like a back arrow)


![](../images/text_input_n/Screenshot%202025-11-18%20182128.png)

drag out a flow arrow to link back to screen 1 (Home) interaction popup will appear with the default settings you can now close this

![](../images/text_input_n/Screenshot%202025-11-18%20182155.png)

Now run/present your prototype, the click on the e-mail field to simulate typing in




This will automatically take you to screen 2 where the e-mail and password will appear in the fields



Now click on the sign in button to move on to through screen 3

![](../images/text_input_n/#)


Remember:

![](../images/text_input_n/Screenshot%202025-11-18%20182253.png)

## Adding an Avatar 

Select the placeholder image inside the Avatar, selecting it in the Layers is the best approach

![](./final_text_picts/av_first_select_img_laayer.png)


Now ``SHIFT + 2`` to zoom in on avatar image

![](./final_text_picts/add_av_1.png)

Use either **Unsplash** or **User Profile/Avatar** plug-in - right mouse to open and select plug-ins

![](./final_text_picts/add_av_2.png)

In this example we are on using Unsplash and we are searching for a face image

![](./final_text_picts/add_av_3.png)

We will select square and free license

![](./final_text_picts/add_av_4.png)

Choose an image
![](./final_text_picts/add_av_5.png)

This will swop out the placeholder

![](./final_text_picts/add_av_6.png)

``SHIFT + 1`` to zoom back out

![](./final_text_picts/av_complete.png)










![](./final_text_picts/name_sc_1.png)






If you have several Design System Kits in your Assets, you'll need to select the one you want to search.

![](./text_update/lib_switch_assets_SD.png)

![](./text_update/lib_switch_assets_MD.png)


Hover +
![](./text_update/B_out_ready_sc_3.png)

Back arrow change
![](./text_update/back_arrow_change.png)

Back arrow flows
![](./text_update/back_arrow_flow.png)
Back ready

![](./text_update/back_but_ready.png)


default_to_placeholder
![](./text_update/default_to_placeholder.png)

All Flows
![](./text_update/new_flows.png)

place_defualt_whole
![](./text_update/place_defualt_whole.png)

sc_1_flow_sc_2
![](./text_update/sc_1_flow_sc_2.png)


sign_but_to_sc3
![](./text_update/sign_but_to_sc3.png)

sign_click_to_sc_2
![](./text_update/sign_click_to_sc_2.png)


sign_in_but_start
![](./text_update/sign_in_but_start.png)

swop_back_arrow
![](./text_update/swop_back_arrow.png)


![](./text_update/)
