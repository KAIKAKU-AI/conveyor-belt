# Open Source Conveyor - Fusion

Access here, in Onshape!

[Open Source Conveyor Belt](https://cad.onshape.com/publications/9120640742d2d27755675fb9/w/c973e2a3aa9155f0db211b78/e/157d0eb66a47e83ecb2cf43a?renderMode=1&uiState=66e1bb9d53f06241e75a077c)

## Background
At the outset of developing Fusion, our low cost food assembly robot, we realised there was a lack of suitable low cost conveyor belts on the market, some of the cheapest costing in the thousands of pounds. In addition, most seemed better suited for industrial applications, using motors or belts that were incompatible with our space constraints.

![Conveyor Belt](conveyor_image.png)

Therefore we decided to design our own conveyor belt. Following countless iterations and three core versions, we're happy to release it as an open source project, hoping this will help other startups, hobbyists and makers. Feel free to use, modify, contribute or modify!

## Explanation
We've removed a few features related to our specific application:

- Mounting points for our custom PCB
- A mount and passthrough for two time of flight sensors
- Guides that encourage an object into the centre of the belt

If there is significant demand, we may release a future version with these added back.

The belt has also been designed to work with an existing length of conveyor belt, and to fit on 3030 extrusion separated by a fixed distance. Feel free to modify these, or present an updated parametric design.

## What you'll need

The conveyor has been designed to be as 3D printed as possible, while remaining rigid. To achieve this it predominantly uses 3030 extrusion. We've used the closed groove type to make it easier to clean, but feel free to use the more common, open groove variety. In addition to a printer, and some filament, you'll need:

- X1 37mm DC motor (we recommend the Pololu variety)
- X4 50mm length of 8mm steel rod
- X1 XT60 panel mount (to power PCB interally)
- X1 USB C panel mount (to transfer data to PCB / microcontroller internally)
- X6 688 bearings
- X1 flange coupler (for the driving spur gear)
- Assorted fasteners (see BOM)

-- KAIKAKU
