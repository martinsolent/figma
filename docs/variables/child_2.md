---
layout: default
title: Variables - String
parent: Variables
nav_order: 3
---

{: .no_toc }

# Variables - Strings

Create a circle 150x150 - colour it red

![](./variables_string_2024/spring_.png)

Make it into a component either right-mouse or click on the Create Component on the top bar

![](./variables_string_2024/spring_1.png)

Now make it into a Variant Set by clicking on the icon on the on the top bar

![](./variables_string_2024/spring_1.png)

Now there are two Variants, Create another Variant by clicking the purple `+` icon at the the bottom of the Variant Set

![](./variables_string_2024/spring_v2.png)

Create one more Variant

![](./variables_string_2024/spring_x.png)

Colour this green

![](./variables_string_2024/spring_3.png)

and colour the middle one blue

![](./variables_string_2024/spring_4.png)

With the Variant Set selected 

![](./variables_string_2024/spring_6.png)

Rename it **circles** either in the Layers panel or the label on the Variant Set

![](./variables_string_2024/rename_cir.png)

We need to rename each of the Variants to match their colours. Select the top Red circle and in the Properties Panel on the right, in the Current variant section type in **red** in lowercase

![](./variables_string_2024/spring_7.png)

Repeat with the Blue circle and call it **blue** in lowercase

![](./variables_string_2024/spring_8.png)

And finally repeat with the Green circle and call it **green** in lowercase

![](./variables_string_2024/spring_9.png)

Your Layer Panel outline on the left will now look like this

![](./variables_string_2024/spring_10.png)

Now create a new Frame either by press`F` or select it from the top Tools bar. In this example Android Large has been selected from the templates on the right

![](./variables_string_2024/spring_11.png)

Create 3 100x100 Rectangles at the top of this new frame

![](./variables_string_2024/spring_12.png)

![](./variables_string_2024/spring_13.png)


Fill each of the rectangles with their corresponding colours from the circles in the Variant Set using the Eye Dropper

![](./variables_string_2024/eye_drop.png)



![](./variables_string_2024/spring_14.png)

In the left panel switch to the **Assets** tab 

![](./variables_string_2024/draf_asset_-2.png)

and drag a **Circles** instance underneath.

![](./variables_string_2024/drag_asset_1.png)

Make sure nothing is selected by clicking on the pasteboard or press `ESC` on your keyboard

From the **Properties** panel on the right in the **Local Variables** section

![](./variables_string_2024/spring_24.png)

Select the Circle instance, then from the Properties panel on the right - in the instance properties section - click on the **Open Variables** icon

![](./variables_string_2024/spring_var.png)

Click on the **Create variable** button and select **String** from the dropdown

The variable **Collection** panel will now open

![](./variables_string_2024/spring_value.png)

Replave the String name a **Select Colour** and the Value a **red**

![](./variables_string_2024/string_naming.png)

Select the Red rectangle. In the Properties on the right in the Variant Section click on the **Assign Variable** icon

![](./variables_string_2024/assign_var_circle.png)

From the dropdown select the **select colour** variable

![](./variables_string_2024/assign_v2_1.png)

The circle instance with be now assigned to the **select colour** variable - the label will show this

![](./variables_string_2024/assign_2.png)

Now we need to 'wire-up' the Rectangles, select the red Rectangle - then switch the Design to Prototype in the lef Properties panel. Click on the `+` icon in the **Interactions** section and then change None to **Set Variable** from the dropdown  

![](./variables_string_2024/spring_35.png)

We only have one variable so select **Select_Colour**

![](./variables_string_2024/spring_36.png)

In the **to** field type **red** in lower case it will appear below in speak marks - Press `Enter` on the keyboard.

![](./variables_string_2024/spring_37.png)

When you click on the Variable tag on the red rectangle it will show its set up

![](./variables_string_2024/tag_one.png)

Now select the blue rectangle and repeat the process but the **to** field needs to be **blue**

![](./variables_string_2024/assign_blue_2.png)

After you press `Enter` you check the set-up by clicking the tag.

![](./variables_string_2024/blue_tag.png)

Finally select the green rectangle and repeat the process but type **green** in the **to** field

![](./variables_string_2024/spring_39.png)

After you press `Enter` you check the set-up by clicking the tag.

![](./variables_string_2024/green_tag.png)


