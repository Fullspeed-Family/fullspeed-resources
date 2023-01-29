---
title: "Skids Overlap"
date: 2022-08-30T11:28:40+02:00
draft: false
weight: 2
---

## Overlap Percentages per Surface
The following table shows the approximately how much you need to overlap your skid marks on flat ground. Remember that the amount of overlap changes depending on the elevation you drive in. You can use these overlaps as the base overlap for everything.

Obviously, plastic does not have visible skid marks, you'll have to feel or imagine the overlap you currently have for this to work.

| **Speed** | **Asphalt (Overlap)** | **Dirt (Overlap)** | **Grass (Overlap)** | **Plastic (Overlap)** |
|-----------|-----------------------|--------------------|---------------------|-----------------------|
| 220       |           -           |         80%        |         83%         |          83%          |
| 300       |           -           |         85%        |         88%         |          88%          |
| 400       |           -           |         87%        |         90%         |          90%          |
| 420       |          50%          |          -         |          -          |           -           |
| 500       |          60%          |         90%        |         92%         |          92%          |
| 600       |          67%          |         92%        |         93%         |          93%          |
| 700       |          72%          |         93%        |         94%         |          94%          |
| 795       |           -           |          -         |         95%         |           -           |
| 800       |          75%          |         94%        |          -          |          95%          |
| 895       |           -           |         94%        |          -          |                       |
| 900       |          78%          |          -         |          -          |          95%          |
| 995       |          80%          |          -         |          -          |          96%          |

### Visual: Asphalt/Tarmac
![Visual Asphalt SD Overlap](/img/visual_sd_overlap_asphalt.png)

### Visual: Dirt
![Visual Dirt SD Overlap](/img/visual_sd_overlap_dirt.png)

### Visual: Grass

![Visual Grass SD Overlap](/img/visual_sd_overlap_grass.png)

## Relationship between overlap and acceleration
For any given speed, you accelerate a certain amount when driving straight without drifting. This usually depends on which gear you are in, except after 800 where the acceleration drops to 3.6. We call this the base acceleration. If you were to initiate a speed drift, you get a boost on this base acceleration.

Depending on the overlap of the skid marks, this acceleration becomes better and better until you reach the optimal overlap for the current speed. However, if you overlap more than the optimal overlap, your acceleration boost will begin to decrease instead.

![Generic SD Graph](/img/generic_sd_graph.png)

The graph above shows the generic behavior of the relationship between skid overlap and acceleration. The Y axis is the acceleration, and the X axis is the overlap, with more overlap to the left and less overlap to the right. The gray straight line in the middle is the base acceleration for a given speed.

If you were to drift, the black line shows the acceleration boost relative to the base speed that you get. As you can see, with too much overlap (under sliding) or too little overlap (over sliding) you will get either less additional acceleration or even less acceleration to begin with.

An important practical note is that if you notice the black graph is much steeper on the left side than on the right side. The goal is of course to keep your skid overlap in a way that you are always at the top of the black graph, but this is simply not practical and requires extreme precision. But you can imagine that you have much more room to work with on the right side, or in other words if you are over sliding. Therefore, if you are unsure about the overlap required for some speed, it is better to over slide than under slide.
