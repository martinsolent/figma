---
layout: default
title: Figma & AI
nav_order: 19
has_toc: false
---

{: .no_toc }

# Figma & AI

**Figma Make** is an AI-powered app-building tool. You describe what you want in ordinary language, and AI generates a working, interactive prototype without requiring coding skills. You can test the prototype, ask AI to make changes and share the result with others.

Traditionally, Figma focuses on designing how an app looks. **Figma Make** moves towards building something users can interact with.

For UX projects, tools such as **ChatGPT** and **Claude **offer an alternative approach. They generate working prototypes through AI-assisted coding, often providing a quicker route to testing ideas with users and gathering feedback. Rather than focusing solely on design tools, you should consider which approach best supports rapid prototyping and user testing.

Sources: [Figma Make](https://help.figma.com/hc/en-us/articles/31304412302231-Explore-Figma-Make?utm_source=chatgpt.com) | [Claude Artifacts](https://www.anthropic.com/news/artifacts?utm_source=chatgpt.com) | [ChatGPT](https://openai.com/chatgpt/?utm_source=chatgpt.com).


####  Copy a UI Screen-Capture & Convert to a Figma Design File

![Figma Make screenshot 1](../images/figma_make_img/spotify_SC.png)

Open a folder or create a new one. Then go to the blue Create button and select Make.

![Figma Make screenshot 1](../images/figma_make_img/1_figma_make.png)

You will be prompted to add an attachment. Alternatively, click the plus (+) icon in the bottom-left corner of the chat field.

![Figma Make screenshot 2](../images/figma_make_img/2_figma_make.png)

Then select Upload File/s.

![Figma Make screenshot 3](../images/figma_make_img/3_figma_make.png)

I have already taken a screenshot. I will browse to the file I want to use, select it, and click Open.

![Figma Make screenshot 4](../images/figma_make_img/4_figma_make.png)

Now I will provide instructions. Type "Recreate this" and click the Send button in the bottom-right corner of the chat.

![Figma Make screenshot 5](../images/figma_make_img/5_figma_make.png)

Figma will begin using AI to recreate the screen capture. It will document its progress in the left-hand panel.

![Figma Make screenshot 7](../images/figma_make_img/7_figma_make.png)

Once completed, the design will appear on the canvas. This will include all the components and interactions. As I have copied Spotify, Sigma will replace the original images with Creative Commons Zero (CC0) images from Unsplash that are available in the public domain.

Now go to the top-left corner and click the Preview button. 
![Figma Make screenshot 10](../images/figma_make_img/10_figma_make.png)

This will open the preview in a new browser tab.


![Figma Make screenshot 15](../images/figma_make_img/15_figma_make.png)

Next, click Copy Design.

![Figma Make screenshot 16](../images/figma_make_img/16_figma_make.png)

#### Paste into a Design File 

Now return to your files by clicking the Figma icon in the top-left corner. Then navigate to your folder and create a new Figma design file.

![Figma Make screenshot 19](../images/figma_make_img/19_figma_make.png)


Right-mouse Click on the canvas and select Paste Here.

![Figma Make screenshot 20](../images/figma_make_img/20_figma_make.png)

The design will now appear.

It is now fully editable. You may need to capture additional screens for other pages that you want to link together when creating your prototype.

![Figma Make screenshot 21](../images/figma_make_img/21_figma_make.png)


### Figma Make with a AI Chat Prompt

```
I'm a UX student who doesn't write code. Please build a clickable prototype.

DESIGN SYSTEM
- Use Tailwind CSS via its Play CDN script (cdn.tailwindcss.com), using utility classes with one accent colour and consistent spacing throughout.
- Use the design system's own components and patterns. Only write custom CSS for small layout adjustments.

THE PROTOTYPE
- Product: A tracker that helps flatmates share the care of their houseplants
- Users: Students sharing a house who keep forgetting whose turn it is to water the plants
- Main task users must be able to complete: See which plants need watering today, mark the fern as watered, and check that it moves to "Done today".
- Screens, in order:
  1. Today: plants that need water now
  2. Plant details with a care tip and watering history
  3. Mark as watered (choose who did it)
  4. All plants list
  5. Add a new plant
- Content: realistic fake content in UK English — 6 plants (fern, cactus, snake plant, pothos, basil, peace lily) with different watering schedules, shared by 4 flatmates. No lorem ipsum and no real people's data.

REQUIREMENTS
- Everything needed to complete the main task must work, including going back and correcting mistakes.
- Anything outside the task should show a short message: "This part isn't in the prototype yet."
- Accessibility: semantic HTML, a label on every input, visible keyboard focus, sensible heading order, colour contrast that meets WCAG 2.2 AA, and helpful error messages.
- Design mobile-first for a 375px-wide phone screen; it should still work on a laptop.
- Low fidelity: greyscale only, simple placeholder boxes instead of images, so people focus on the flow rather than looks.
- Add a small "Reset prototype" link in the footer that returns to the first screen and clears any entered data, so I can start again cleanly.
- Add comments in the code marking where each screen starts, so I can describe the structure in my report.



```

