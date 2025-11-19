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

In the Properties panel on the right in the Status Bar section switch of Camera Cutout

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

The order of your layers might not match the design hierarchy shown on your screen **to do this you need the swicth back to Files in the left panel**

![](./final_text_picts/out_line_order_wrong.png)

If that's the case, you'll need to reorder the layers by dragging them into the correct order

![](./final_text_picts/show_out_line_order.png)


**Add Log in Form Field**

Search for ``Form Log In`` in the **Simple Design** you will need to make sure you have switched to the Simple Design kit in the Assets

Then drag it onto the screen & prosition

![](./final_text_picts/drag_form_log_in.png)

**Update Headline on Labal on Top App Bar**

We now need to change the generic label on the top app bar headline.

Click the top app bar to select it, either directly on the screen or from the layers outline.

![](./final_text_picts/label_0.png)

Press ``Shift + 2`` on your keyboard to zoom in on the component.

In the properties panel on the right, go down to the Headline field. Replace the word Label with Sign in, press Enter on your keyboard, and the headline title in the component will update.

![](./final_text_picts/label_2.png)

You can now press ``Shift + 1`` on your keyboard to zoom back out to full view.

![](./final_text_picts/zoom_out_sc1.png)

**Final Check**

In the left panel make sure you have **File** not **Assests**


![](./text_update/Assest_click.png)

Make sure your layer outline matches the hierarchy shown on your screen. If it doesn’t, simply drag and drop the layers into the correct order.

It should look like this.

![](./final_text_picts/SC_1_final_layers.png)

### Create Screen 2

Press ``Alt and Shift`` on your keyboard, hover over Screen 1, and drag to the right to create a copy. Figma usually works out the screen name for you, so you might not need to rename it – but if it doesn’t, you can do it manually rename new screen to Screen 2, either by updating the frame label or within the Layers panel



![](./final_text_picts/Recording%202025-11-19%20202359.gif)


### Create Screen 3

Now, hover over Screen 2, then hold down the ``Alt and Shift`` keys on your keyboard and drag to the right to create a copy, this will become Screen 3, just like with the screen 2, Figma usually updates the label automatically. If it doesn’t, you’ll need to update it manually.

![](./final_text_picts/Recording%202025-11-19%20210210.gif)



#### Adjust Screen Layers

In the Layers panel, make sure the frames for each screen are arranged in order: 1, 2and 3. If they’re not, drag them into the correct sequence. It’s a good idea to close each frame before you do this, to make organising them easier.

![](./final_text_picts/sc_layer_final.gif)

Select the **Log In** component on Screen 3 and delete it.

![](./final_text_picts/Recording%202025-11-19%20211403.gif)

We’ll now update the headline title on the top app bar and change it to **Review**.

Click to select the component, then go to the properties panel on the right. Scroll down to the Headline field in the app bar component settings, type **Review** to replace the existing text, and press Enter to apply the change.


![](./final_text_picts/review_33.png)


**Add the final component to Screen 3.** On the panel on the left, make sure you're in the **Assets** tab and using the **Simple Design Kit**. You might need to select this kit in the Assets panel before searching. 

![](./final_text_picts/kit_switch.png)


Once you're in the right kit, search for the ``Review Card`` component

Then drag and drop it onto Screen 3, positioning it in the centre if needed.

![](./final_text_picts/rev_comp.png)





![](../images)

In the right Properties panel change Design to Prototype

![](../images)


Open Screen 2 in the layers

![](../images/)

Click on ``Form Log In`` to highlight this component, press ``Shift 2`` on your keyboard to zoom in
:
![](../)

 Select the e-mail input field either by selecting it in the layers or within the design

![](../images/)

In the properties on the right change the value type From Default Placeholder and in the value field type in a fake e-mail address



![](../images/)

This will now appear in the e-mail field now select the password input field either in the layers or within the design

![](../images/)


Delete 
![](../images/t)

 With it selected in the properties change value type from default to placeholder
Delete Swop:
![](../images/)

 In the value field type in four stars ``****`` to represent a password. This will now appear in the password field
Delete Swop:

![](../images/text_input_n/)


Delete??

![](../images/text_input_n/)

Delete??

![](../images/text_input_n/)

c

![](../images/text_input_n/)

![](../images/text_input_n/)

Highlight the Log In  component on screen 2, you will see a blue circle with a + click this

![](../images/text_input_n/)

 and drag out a flow arrow to screen 3 an interaction pop-up will appear with the default settings, you can now close this

![](../images/text_input_n/)

We will now create a link back to the home screen, click on the hamburger icon for the blue circle with + to appear. (On a real design you would change this to a more appropriate icon like a back arrow)


![](../images/text_input_n/)

drag out a flow arrow to link back to screen 1 (Home) interaction popup will appear with the default settings you can now close this

![](../images/text_input_n)

Now run/present your prototype, the click on the e-mail field to simulate typing in




This will automatically take you to screen 2 where the e-mail and password will appear in the fields



Now click on the sign in button to move on to through screen 3

![](../images/text_input_n/#)


Remember:

![](../images/text_input_n/)

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




Make sure the Forn Login is select eith in the layers of non screen

![](./final_text_picts/scree_1_ready_to_zoom.png)

Press ``SHIFT + 2`` to zoom in

![](./text_update/add_email.png)

Select the Log In Form compnonent either on the screen or in the Layers

![](./final_text_picts/scree_1_ready_to_zoom.png)

![](./final_text_picts/)

Screen 1 is now complete.