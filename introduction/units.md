---
description: Gives a general overview of units and their conversions.
---

# Units

Geometry Dash has three immediate units obvious for measurement: pixels, blocks, and (internal) variables. We describe the notation for each one here, and their conversions.

## The Block Unit

A block represents a single, standard `RegularBlock` item. It is equivalent to one grid in the Level Editor. We denote it using a non-italicized "b."

## The Delta Unit

The Delta Unit, denoted using the capital Greek Delta letter, gives the length of one unit in terms of the internal x-y positioning inside of the Geometry Dash engine.

## The Pixel Unit

The Pixel Unit, denoted with a non-italicized "p," gives the length of a single pixel.

## Conversions

$$
1 \cdot \mathrm{b} = 30 \cdot \Delta
$$

$$
1\cdot \mathrm{b} = 135 \cdot \mathrm{p}
$$

Generally computations are done in blocks, but it may be useful to use either pixels or the Delta unit, especially for internal computation. The pixel unit is most useful for visual editing, but it has some relevance with Cocos2dx.
