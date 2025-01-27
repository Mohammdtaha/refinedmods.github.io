So far you've set up autocrafting for items. Since Refined Storage has support for [[Storing fluids|storing fluids]] as well, it speaks for itself that Refined Storage can also autocraft with fluids.

Every autocrafting pattern that uses fluids is a processing pattern. If you forgot, a processing pattern is a [[Pattern|pattern]] that outputs items to an external inventory and expects an output back, as declared in the [[Pattern|pattern]].

With fluid autocrafting, you get the ability to make the [[Crafter]] output fluids (or items), and when the "result" fluid (or item) is back in the storage network, Refined Storage will detect the task and mark it as finished.

This means that you can also declare fluids as an output in the processing pattern. It also means that you can request fluids from the [[Fluid Grid]].

You can mix fluid and item inputs/outputs freely.

## Creation of the mixed pattern
To make a mixed (fluid or item) processing pattern, toggle the [[Pattern Grid]] in fluid or item mode.

You can then use JEI transfer to transfer item and fluid ingredients. You can also use a filled fluid container (like a bucket) to specify the fluid.

Use left or right click on the fluid slot to modify the mB.

## Other resources
- [Demo video](https://www.youtube.com/watch?v=6v-e_NdLEnI)