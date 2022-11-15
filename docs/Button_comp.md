---
layout: default
title: Button Component
nav_order: 8
---

{: .no_toc }

# Button Components

## Introduction

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=55745695-8b9e-4cc5-9ffd-af4d0139f701&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

We will look at creating a creating button components which contain a number of editable regions that allows a range of customisation for different states such as default, hover, disabled, pressed, focused etc.

Here's how the interaction works

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2Fhx2IyvFW2bdwPE0DmmExSY%2FButton_types_interactive%3Fnode-id%3D7%253A9%26scaling%3Dscale-down%26page-id%3D7%253A8%26starting-point-node-id%3D7%253A9" allowfullscreen></iframe>

[Link to test out Pressed State on a touch screen device](https://www.figma.com/proto/hx2IyvFW2bdwPE0DmmExSY/Button_types_interactive?node-id=7%3A9&scaling=scale-down&page-id=7%3A8&starting-point-node-id=7%3A9)
     
[Find out more about design systems](https://martinsolent.github.io/figma/docs/Design_Systems.html){: .btn .btn-purple } 

### Step 1

We will start off by selecting some free icons (plugins) from the Figma community

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=1b64afde-d4f7-4229-ae84-af4d00b6f9e2&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

### Step 2

Once the icons have been selected ns and created them as individual components we will move on to creating a auto layout button with a text label and an icon

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=1f384413-900b-46c5-8719-af4d00b7868f&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

### Step 3

Once we have created our button we will add editing functionality using component properties on the icon and the text label

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=4d9ff906-9d0e-44ff-942c-af4d00de4a33&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

### Step 4

We will now add two more variants of the bottom for the following states:

Enabled
Hovered
Pressed

We will name these properties using [naming protocols](https://help.figma.com/hc/en-us/articles/360055471353-Prepare-for-variants):

`componentName/property1value/property2value/property3value`

As the button type is filled we will name as follow:

`Button/filled/enabled`

`Button/filled/hovered`

`Button/filled/pressed`
 
 NOTE: In the video walk-through Button has been missed - so name as above in the Properties Panel

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=3a522f99-bb55-4f33-8fbd-af4d00b7598b&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

### Step 5

We will now add another component (Boolean) property to switch the icon on and off. 

Note: this could have been set up when we first added the properties for swapping the icon and editing the text label in Step 3

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=4b30f177-1269-422b-99ab-af4d00b782c1&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

### Step 6

Adding micro interactions to prototype the component

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=c9810eab-f78e-40f1-be39-af4d0166832a&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>


