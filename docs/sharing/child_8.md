---
layout: default
title: Testing OBS Set-Up
parent: Prototyping
nav_order: 9
---

{: .no_toc }

# Testing - OBS Studio

## WebCam Set-up

We will use the **FREE** [OBS Studio](https://obsproject.com/) to set up feeds from multiple devices to help us conduct user experience testing within a lab environment.
You will need to install OBS Studio on your own computer, or you can access it in the university labs (if installed).

In this walkthrough, we will use HUE gooseneck webcams to capture testers’ interactions with a mobile application. 

![](../images/proto_share/hue_web_cam_picts/1_hue_wc%20copy.jpg)

The HUE webcam kit includes the camera, the base, and a USB extension cable. 

![](../images/proto_share/hue_web_cam_picts/5_hue_wc.jpg)

Plug the camera and the (mini) USB extension cable into the base. Place the other end of the USB cable into the computer.

![](../images/proto_share/hue_web_cam_picts/11_hue_wc.jpg)


The setup should now look like this

![](../images/proto_share/hue_web_cam_picts/10_hue_wc.jpg)



We will use the webcam together with a mobile phone cradle. This cradle has a hinge that lets you adjust the phone’s position. Keeping the phone in a cradle like this makes it steady while being filmed, but still allows the user to interact with the app on the screen.

![](../images/proto_share/hue_web_cam_picts/14_hue_wc%20copy.jpg)

Phone set up in the cradle.

![](../images/proto_share/hue_web_cam_picts/15_hue_wc%20copy.jpg)

We have placed the phone in the cradle and positioned the HUE webcam over the screen, using a book to add some height. Make sure the setup is secure and that the cables are not causing any obstruction or hazard.

![](../images/proto_share/hue_web_cam_picts/PXL_20251124_121517599_copy.png)


## OBS Studio Set-up

We will add a standard **Logitech webcam** to record the participant, which is important when they are **"thinking out loud"** Then we will connect one of the **HUE webcams** to capture the interaction on the phone. You can add more devices if needed, but we will focus on these two. The principle for adding and using them is the same, as long as you have enough USB connections on the computer.

![](../images/proto_share/obs/1_OBS.png)

Once you’ve installed and opened OBS Studio, the first thing you need to do is add feeds and sources. In the Sources panel at the bottom of the screen, click on the +.

![](../images/proto_share/obs/4_OBS.png)

Then select the appropriate source type.

![](../images/proto_share/obs/6_OBS.png)

You can now name the device.

![](../images/proto_share/obs/7_OBS.png)

In this scenario, we are using a webcam, so we will call it Logi cam and click OK.

![](../images/proto_share/obs/8_OBS.png)

Now select the model (C920) and click OK.

![](../images/proto_share/obs/9_OBS.png)

The image will appear.

![](../images/proto_share/obs/10_OBS.png)

You can move this around and enlarge it by dragging one of the corners.

![](../images/proto_share/obs/11_OBS.png)

### Creating the presenter in a rounded circle

{: .note }
In most user testing environments, **you probably don’t need to place the tester in a circle.** You can just leave them in the normal rectangle layout it comes with. However, this might be useful for other uses of OBS Studio.

To do this, create a new scene. In the Scenes panel at the bottom of the screen, click on the +.


![](../images/proto_share/obs/12_OBS.png)

Name it Circle.

![](../images/proto_share/obs/13_OBS.png)

It will now appear as an extra scene under your main scene.

![](../images/proto_share/obs/14_OBS.png)

Add the video capture from the webcam you’ve already set up. In the Sources panel, click on the +, then select Video Capture Device from the pop-up.

![](../images/proto_share/obs/15_OBS.png)

Click on Add Existing to bring in the Logi cam you set up in the main scene.

![](../images/proto_share/obs/16_OBS.png)

The webcam feed will now appear in the circle scene.

![](../images/proto_share/obs/17_OBS.png)

Right-click on the webcam source in the Sources panel and select Filters.

![](../images/proto_share/obs/18_OBS.png)

In the Filters panel, click on the + at the bottom left.

![](../images/proto_share/obs/19_OBS.png)

From the pop-up, select Image Mask/Blend.

![](../images/proto_share/obs/20_OBS.png)

As we only have one mask, you don’t need to rename it, just click OK.

![](../images/proto_share/obs/21_OBS.png)

Browse for the mask image. This mask was created in PowerPoint: a black background with a white circle in the centre, saved as a JPEG.

Click Browse, select the image, and click Open.

![](../images/proto_share/obs/22_OBS.png)

It should appear as a preview.

![](../images/proto_share/obs/23_OBS.png)

 Select it 

![](../images/proto_share/obs/24_OBS.png)

and close the Filters panel.

![](../images/proto_share/obs/25_OBS.png)

The webcam feed will now appear in a masked circle. It may not be perfectly aligned.

![](../images/proto_share/obs/26_OBS.png)

Adjust it by resizing the bounding box and dragging it to centre align.

![](../images/proto_share/obs/27_OBS.png)

![](../images/proto_share/obs/28_OBS.png)

Click outside the selection to preview, and click the padlock in the Sources panel to lock the mask to the image.

![](../images/proto_share/obs/29_OBS.png)

Go back to the main scene in the Scenes panel.

![](../images/proto_share/obs/30_OBS.png)

In the Sources panel, click on the +

![](../images/proto_share/obs/31_OBS.png)

select Scene, then click Add Existing and choose the Circle scene. Click OK.

![](../images/proto_share/obs/32_OBS.png)

This will add the circular webcam feed alongside the original image.

![](../images/proto_share/obs/33_OBS.png)

You can rescale and move it, although it will have a large bounding box.

![](../images/proto_share/obs/34_OBS.png)

Turn off the original webcam feed.
![](../images/proto_share/obs/35_OBS.png)

Click on the + in the Sources panel and select Video Capture Device.

![](../images/proto_share/obs/36_OBS.png)

Name it Hue and click OK.

![](../images/proto_share/obs/37_OBS.png)

This will bring in a video feed from a phone in the cradle. Click OK.

![](../images/proto_share/obs/38_OBS.png)

Right-click on this element,

![](../images/proto_share/obs/39_OBS.png)

 select Transform, then choose Rotate 90° Clockwise.

![](../images/proto_share/obs/40_OBS.png)


![](../images/proto_share/obs/41_OBS.png)

The phone will now be the right way up. You may need to adjust it in the cradle to centre it within the webcam’s field of view.

![](../images/proto_share/obs/42_OBS.png)



Open your Figma design and select Prototype from the properties panel.

![](../images/proto_share/obs/44_OBS.png)

Your prototype will render in a new tab.

![](../images/proto_share/obs/45_OBS.png)

Make sure you are on the Figma page where your Prototype is - in this case the page is called Prototype

![](../images/proto_share/obs/46_OBS.png)

Click the three dots (top right) and choose View Prototype.

![](../images/proto_share/obs/47_OBS.png)



Back in the Figma preview, you may see duplicate profiles

![](../images/proto_share/obs/49_OBS.png)

One for your login on the device and one in the browser. 


![](../images/proto_share/obs/50_OBS.png)

Select the device login to follow.


![](../images/proto_share/obs/51_OBS.png)

In OBS Studio, click +

![](../images/proto_share/obs/48_OBS.png)

Select Window Capture.

![](../images/proto_share/obs/52_OBS.png)

 Name it Figma and click OK

![](../images/proto_share/obs/53_OBS.png)

Select the browser page where the Figma Prototype is



![](../images/proto_share/obs/55_OBS.png)

You will now have the Figma feed and the feed from the Hue Webcam on the testers ohone screen


![](../images/proto_share/obs/58_OBS.png)

Now when you interact with the Prototype on the device it with reflect in the Figma Prototype on the computer


![](../images/proto_share/obs/62_OBS.png)



**You will now have:**

* The webcam feed of the presenter/user tester
* The phone feed
* The window feed of the Figma prototype


**In a user test you can use MS Team to Record the screen to  analyse it later**
