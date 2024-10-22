These notes accompany the [drawings](https://cad.onshape.com/documents/4f4f7c02e75b1c43639cfe17/w/a39e86fb38e2100b868e28ef/e/c6c7652937759c546924c0b4?renderMode=0&uiState=64ac2b52e79b6d6e9e25d7ee) and should help you should you decide to actually build this thing.
# Base design
This is the top-down view of the pad, from which other layers are created. It helps to see how everything should fit together. Use a copy of this if you want to change the design. Use the stuff in "layers" directory if you want to go ahead with this design unchanged.
# Wood layers
Layers are the sketches for cutting from a single sheet of plywood. I used 3 mm plywood — this is the minimum thickness for the PCB to fit in the original design. After cutting each layer, you will glue them together to get a 3d pad.
## Layer 1: Base lower
Layer 1 is just the entire base of the pad. This will be the bottom-most layer. If your plywood sheets are not big enough to fit this, see Layer 2.
## Layer 2: Base mid
Layer 2 should be exactly the same as Layer 1, with two caveats: 
1. You might be saving plywood like I did, and fitting 1.5 layers per sheet. In that case here's a half of a base for you to fit onto offcuts. If your sheets fit the whole thing just fine, then simply cut another copy of Layer 1 instead. 
2. When gluing layers 1 and 2 together, make sure to criss-cross the grain of the wood. Take your sheet of plywood and try to bend it gently. Now turn it 90 degrees and try again. It will most likely bend easier in one of these orientations. When you glue the parts together, make sure they aren't parallel in their bendy directions — this will make the whole pad bend too much. How you position the part during cutting doesn't matter, because the base is symmetrical.
## Layer 3: Base upper
This is the top-most layer of the pad. You can see the square bits that will support the sensors, the rectangular bits for velcro pieces, and the big cutout for the PCB and the USB cable going out.
> [!WARNING] 
> On this sketch, you should only cut the outer border and the PCB-cable hole. The square and rectangular bits should be **engraved** (use your laser cutter software) or removed altogether. They are just there to help position the details you will cut in Layer 4. They are not supposed to be holes.


## Layer 4a: Supports
And these are all the extra square and rectangular bits mentioned in Layer 3, lumped together. Not sure why I made so many, probably spares. They will hold your sensors and velcro.

## Layer 4b: Borders
These are the outer borders of the pad. They go on top of Layer 3 when everything is assembled. There are a couple spares. I used three layers of border on every side except the back, which uses 4 to prevent the back panel from being kicked over. The ones with the holes go on the USB side, I used two layers with a hole, and I put a solid one on the top to cover it up.