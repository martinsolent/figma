---
layout: default
title: Pixel Perfect 2
parent: Pixel Perfect
nav_order: 3
---

{: .no_toc }

# Pixel Perfect 2 - Top App Bar

![](../images/pixel_perfect/top_bar/M3_guide.png)


 We are going to create a "pixel perfect" Component using Google Material Design guidelines. Making components is one of the first things you do when creating a UI project, you either create the Component yourself or you import them into your project by using a copyright free Library/UI Kit.

[M3 Material Design Guidelines](https://m3.material.io/components/top-app-bar/overview)

We will be creating the **Top App Bar** Component which is part of the [Material Design kit M3](https://www.figma.com/community/file/1035203688168086460)

![](..images/pixel_perfect/../../../images/pixel_perfect/pp_12.png)

The Material Design Guidelines will give you all the inforamtion you need to know for createing Components such as sizes and spacings

![](..images/pixel_perfect/../../../images/pixel_perfect/pp_13.png)


This is what we are aiming to create:

![](../images/pixel_perfect/top_bar/work_to.png)


1. Create a Frame with Frame Tool or press `F` on keyboard
2. Call the Frame **Top-App-bar**
3. Set Height & Width **360x64**
4. Set Grid to **8pt**

![](../images/pixel_perfect/top_bar/bar_1.png)

 We could bring in icons using a plug-in, but we will import a icons libary this gives us the option to swap out (change) any of the icons. This will only work in the teams (Education Teams) version of Figma.

Go to [figma.com/community](https://www.figma.com/community) and search for Material Design Icons.

![](../images/pixel_perfect/top_bar/FC_1.png)

Click **Add to Figma** button - Once in figma it needs to be within the shared Team area rather than in your drafts folder and you need to have permissions to access where it is stored.

![](../images/pixel_perfect/top_bar/FC_2.png)

 1. From the panel on the left click on **Assets** 
 2. Then click on the **Library icon**

You should see all the libraries you have access to

 3. Click **Add file** next to **Material Design Icons**

![](../images/pixel_perfect/top_bar/asset_lib_1.png)

It should now display **Added** - You can now close the panel `X`

![](../images/pixel_perfect/top_bar/asset_lib_2.png)


 Make sure in the asset panel you have all library selected. You should now the **Material Design icon** Library.

 **Note:** Imported libraries do not live inside your project they are only linked to it, so you can have a number of projects or a number of people can share one library when updates are made to the library they can then be pushed out to all the projects that used the components and assets.

 ![](../images/pixel_perfect/top_bar/asset_3.png)

#### The Leading Icon

  In the Layers panel select the **top-app-bar** Frame and create another Frame inside of this **48x48** and call it **leading-icon**


  ![](../images/pixel_perfect/top_bar/leading_1.png)

  Give it a **Stroke** (border) of **0.1** this will be just work with we will turn it off later.
  
![](../images/pixel_perfect/top_bar/01_stroke.png)

In the **Assets** panel search for **Back** This should display the back arrow in the **Material Design icon** library.

Click on **Insert Instance** to place it on the Frame
![](../images/pixel_perfect/top_bar/back_ico_insert.png)

It should be inside the **leading-icon** Frame - we need to reposition it.

![](../images/pixel_perfect/top_bar/before.png)

1. Move it so it's on top of the **leading-icon** Frame.
2. It should noe be inside the **leading-icon** Frame

![](../images/pixel_perfect/top_bar/moved.png)

**Note:** You can also reposition it by dragging it in the Layers panel

#### Headline

 1. Create a text box **152x28** by press `T` on keyboard or selecting the text Tool
 2. Font: **Roboto, Medium, 22pt** & **align left**
 3. Type in the word **Title**
 4. Name the Layer **headline**

![](../images/pixel_perfect/top_bar/headline.png)

We will now create 3 more icons for the **Trailing Icon** section of the bar.

1. Create three frames at 48x48
2. Align them up so they have no gaps

![](../images/pixel_perfect/top_bar/trail_icon.png)

Re-name these 3 Frames (in the Layers panel) as follows from left to right:

**trailing-icon 1
trailing-icon 2
trailing-icon 3**

![](../images/pixel_perfect/top_bar/rename_as.png)

We now will add a icon to each frame.

1. Go to the **Assets** panel
2. Search for **Attach**

![](../images/pixel_perfect/top_bar/insert_instant.png)

Repeat with searching for **Today** & **More**. 

**Note:** Make sure you unselect the icon you imported before you bring in another one otherwise it will just replace the selected icon.

![](../images/pixel_perfect/top_bar/today.png)

![](../images/pixel_perfect/top_bar/more.png)

 The icons may be in the wrong position they need to be in each of the **Trailing Icon** frames

![](../images/pixel_perfect/top_bar/wrong_place.png)

 Drag drop them so they are inside each of the Frames, you can also do this by dragging them in the layers panel

 ![](../images/pixel_perfect/top_bar/all_done.png)

  You can get them to the centre in each of the container frames by moving them until you see the alignment guides in red

 ![](../images/pixel_perfect/top_bar/align_more.gif)

  We need to apply **Auto Layout** to each of the frames, This will mean the frames will collapse and we need to re-align them back to the original size and positions.

  Select **trailing-icon 1** in the properties panel on the right 
  
1. Click the `+` on **Auto Layout**
2. Centre
3. Horizontal and Vertical padding set to 0

![](../images/pixel_perfect/top_bar/re_1.png)

 Repeat this with the remaining icons

 ![](../images/pixel_perfect/top_bar/re_2.png)

![](../images/pixel_perfect/top_bar/re_3.png)

The layouts have now been broken, So we need to fix them.

 Shift click to select all three layers.

![](../images/pixel_perfect/top_bar/broken.png)


In the **Frame Properties** Panel on the right:

Reinstate the **height and width to 48**
**Horizontal and Vertical resizing** should both be set to **Fixed**

![](../images/pixel_perfect/top_bar/back_fin.png)

Select all 3 **Trailing Icon** Frames

 **Auto Layout** them and align **centre right**

 Rename layer **trailing-icon**

![](../images/pixel_perfect/top_bar/All_DONE_FINAL.png)


#### Create Component

With the **top-app-bar** selected either **Right-Mouse** and select **Create Component**

![](../images/pixel_perfect/top_bar/create_comp.png)

...or clivk the **Create Component icon** on the Menu bar

![](../images/pixel_perfect/top_bar/comp_icon.png)

Done. Make sure the Layers or ordered from Top to Bottom:

**leading-icon
Headline
trailing-icon **   

![](../images/pixel_perfect/top_bar/comp_down.png)

#### Add Text Property on the Headline text box

We  need to set-up the Title on the **Headline** text to be editable through the text properties when an **Instance** is drag out in the UI layout.

Select the **Headline** text

In the **Text Properties** click on the **Add Text** icon
![](../images/pixel_perfect/top_bar/layer_prop_1.png)

**Name: Headline
Value: Title**

![](../images/pixel_perfect/top_bar/layer_prop_2.png)