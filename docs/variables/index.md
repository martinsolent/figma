---
layout: default
title: Variables
nav_order: 18
has_children: false
has_toc: false
---

{: .no_toc }

# Variables - Number

![](./variables_number_2024/add.gif)

Create a new Design Project, name it and create a Frame 600 x 400 and call it Home

![](./variables_number_2024/var_1.png)

Bring in a Minus ico using the Mterial Design Icons (Community) Plug in - Right Mouse to go to plugins (you might to to add from Figma Community uf you have not got access to this plugin)

![](./variables_number_2024/var_2.png)

Search for Minus

![](./variables_number_2024/var_3.png)

Click on it to add

![](./variables_number_2024/var_4.png)

Drag to the frame if needed

![](./variables_number_2024/var_5.png)

Make it is inside the frame in the Layers panel - in this case it is not 

![](./variables_number_2024/var_6.png)

So drag the minus-circle frame on the home frame

![](./variables_number_2024/var_7.png)

In the Properties the size is 24 x 24

![](./variables_number_2024/var_8.png)

Click on chain icon on the roght to lock H & W, then type in 200 for width and press `Enter` on keyboard

![](./variables_number_2024/var_9.png)

Icon will have scaled - reposition if needed

![](./variables_number_2024/var_10.png)

Repeat with searching, inserting and scaling to 200 x 200 a Plus icon - **plus-circle**

![](./variables_number_2024/var_11.png)

Again make it is inside the frame in the Layers panel - in this case it is not 

![](./variables_number_2024/var_12.png)

Drag it onto the Home frame

![](./variables_number_2024/var_13.png)

Position them with a gap as below

![](./variables_number_2024/var_14.png)

Create a Text box in the centre type in 0 with a size 128 and centre content vertical & horizontal

![](./variables_number_2024/var_16.png)

![](./variables_number_2024/var_18.png)

Make sure you have nothing selected - From the Properties panel on right in the Local Variables section click on add Variable icon

![](./variables_number_2024/var_19.png)

![](./variables_number_2024/var_20.png)

Click Create variable

![](./variables_number_2024/var_21.png)

and Number from dropdown

![](./variables_number_2024/var_22.png)

You can rename to aff meaning - but we will leave it as Number - close this panel

![](./variables_number_2024/var_23.png)

Select the text box with the 0. From the Properties panl on the right in the Text section click on the apply variable icon

![](./variables_number_2024/var_24.png)

![](./variables_number_2024/var_25.png)

You will now see Number click it to apply it to the text box

![](./variables_number_2024/var_26.png)

You will now see it applied in the Text box section of the properties

![](./variables_number_2024/var_27.png)

In the Properties panel on right switch Design to Prototype - Select the Plus icon on the left

![](./variables_number_2024/var_28.png)

In the Interaction section click on the `+` with On click change None to Set variable

![](./variables_number_2024/var_29.png)

You will now see Number in Local variables

![](./variables_number_2024/var_30.png)

Click on it to add

![](./variables_number_2024/var_31.png)

You will be in the **to** field - click on Number below to add again and select **Addition**


![](./variables_number_2024/var_32.png)

This will add a `+` after the variable's name


![](./variables_number_2024/var_33.png)

Type 1 and press `Enter` on your keyboard

![](./variables_number_2024/var_34.png)

This will apply to the interaction

![](./variables_number_2024/var_35.png)

![](/docs/variables/variables_number_2024/var_36.png)

Now select the minus icon on the left

![](./variables_number_2024/var_37.png)

Add Interaction - On click and none to Set variable

![](./variables_number_2024/var_38.png)

Click on the Number variable

![](./variables_number_2024/var_39.png)

You will be in the to field

![](./variables_number_2024/var_40.png)

Click on Number again to add it and select Subtraction from the dropdown

![](./variables_number_2024/var_41.png)

it will a a `-` after the variable's name

![](./variables_number_2024/var_42.png)

Type in 1 and press `Enter` on your keyboard

![](./variables_number_2024/var_43.png)

You should now have this:

![](./variables_number_2024/var_44.png)

![](./variables_number_2024/var_45.png)

Preview your Prototype - adding works well but minus gos dow to negative values - we need it to stop a 0

![](./variables_number_2024/minus.gif)

Select the minus icon on the left

![](./variables_number_2024/var_46.png)

You should still be in the Prototype in the Properties panel - click on the current interaction. You will the see the On click panel open

![](./variables_number_2024/var_47.png)

Click on the `+` to add a Conditional

![](./variables_number_2024/var_48.png)

You should now see this - we need to set a Condition and an action which will stop the value going lower than **0**

![](./variables_number_2024/var_49.png)


Once you have selected Conditional, click in the Write Condition then select the Number Variable

Then select Greater than

‘>’  will appear after the Number Variable, type in 0 and press ‘Enter’ on your keyboard

We now need to add an Else action – which will be the same are what we already have set – so we can just copy the Variable Set from the top.

First close the Set by click on the arrow on its left.

Then drag it under the If action.

Now close the panel – and run prototype – it should now go no lower than 0.

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=bda8bffb-6681-4861-a3a1-b13100990833&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe>

