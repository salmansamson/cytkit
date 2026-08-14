# Assemble the fluidics

*** pic fluidics before

## Assemble flow cell {pagestep}

>! **Caution** 
>!
>! Take care not to damage sealing surfaces (barbs, o-ring grooves, o-rings, cuvette ends). Use plastic tweezers when holding o-rings (not fingers or metal tools).
>! 
>! Wear gloves to handle the cuvette: don't contaminate it with fingerprints.
>! 

First remove the printed supports from the flow cell. Take care not to damage the barb connectors.

![](images/build diagrams/flow cell as printed.png)
![](images/build diagrams/flow cell supports removed.png)

Second, insert the o-rings at either end within the o-ring grooves. If handled gently, the o-rings should stay inside the grooves, due to a slight printed overhang. 

Thirdly flex the flow cell slightly as shown below to insert the cuvette between the o-rings. Tip: if using a square cuvette, you should be able to see through the cuvette side (with a magnifying glass) that the o-ring is sealing against the surface.

![](images/build photos/20260530_131204 flow cell.jpg)
![](images/build photos/20260814_111001 see o-ring through cuvette.jpg)
![](images/build diagrams/20260515_145654 sealing surface.jpg)
![](images/build diagrams/flow cell assembly.png)

Fourthly attach 120 mm of [Silicone tubing 2 mm OD 1 mm ID](fluidic/silicone_tubing_1mm.md){cat:fluidics} to the waste barb on top of the flow cell, and thread this tube through the duct on the side of the flow cell so it sticks out of the bottom.

![](images/build photos/20260814_111028 waste tube top of cuvette.jpg)


Note how the flow cell works and how it will interface with the optics. Inside the flow cell is a sheath flow chamber with concentric sheath and sample inputs. The laser beam enters and leaves through opposite faces of the cuvette, with fluorescence (and SSC) collected by a condensing lens at 90 degrees, and a camera viewport for alignment opposite the condensing lens.

![](images/build diagrams/flow cell transparent view.png)
![](images/build diagrams/flow cell laser path.png)

## Prepare sheath and waste tank caps {pagestep}

The caps of the sheath and waste tanks must first be drilled with the right size holes to fit the required tubing connections. 

Note that the sheath flow is pulled by a vacuum on the wate bottle. Take care therefore to drill cleanly, especially the waste tank cap, as these holes must seal against a vacuum after fitting with connectors and tubing as follows.

**Sheath tank cap:**

1. 5 mm hole (sheath tube), 
1. 1.5 mm hole (vent)

**Waste tank cap:**

1. 3.5 mm hole (vacuum pump) 
1. 3.5 mm hole (pressure sensor or vent)
1. 3 mm hole (waste tube)

Attach the following fitings and tubing to the caps, threading them from inside the cap as follows:

**Sheath tank cap:**

1. [Bottom-of-bottle filter](fluidic/bottom_of_bottle_filter.md){qty:1, cat:fluidics} + 250 mm of [Silicone tubing 6 mm OD 4 mm ID](fluidic/silicone_tubing_4mm.md){cat:fluidics}; pass through 5 mm cap hole from inside to outside, then add
[Tube barb union 2.4x6.4](fluidic/tube_barb_union2.4x6.4.md){qty:1, cat:fluidics}.

**Waste tank cap:**

1. For waste stream: 50 mm of [Silicone tubing 2 mm OD 1 mm ID](fluidic/silicone_tubing_1mm.md){cat:fluidics} + [Tube barb union 1.6x2.4](fluidic/tube_barb_union1.6x2.4.md){qty:1, cat:fluidics}; pass through 3 mm cap hole from inside to outside, then add 480 mm of [Silicone tubing 2 mm OD 1 mm ID](fluidic/silicone_tubing_1mm.md){cat:fluidics}.
1. For pressure sensor or vent: [Tube barb union 1.6x3.2](fluidic/tube_barb_union1.6x3.2.md){qty:1, cat:fluidics} + 400 mm of [Silicone tubing 3.2 mm OD 1.6 mm ID](fluidic/silicone_tubing_1.6mm.md){cat:fluidics}; pass through 3.5 mm cap hole from inside to outside.
1. For vacuum pump: [Tube barb union 1.6x3.2](fluidic/tube_barb_union1.6x3.2.md){qty:1, cat:fluidics} + 400 mm of [Silicone tubing 3.2 mm OD 1.6 mm ID](fluidic/silicone_tubing_1.6mm.md){cat:fluidics}; pass through 3.5 mm cap hold from inside to outside.

In the waste tank cap, push the tube barbs from the inside into the holes in the cap so that they seal. Screw the caps on both bottles. You can then put 2x cable ties on the bundle of tubing coming out of the waste bottle at 50 mm intervals to keep them tidy.


![](images/build photos/20260814_111533 drilled caps.jpg)
![](images/build photos/20260814_111641 sheath tube assm.jpg)
![](images/build photos/20260814_111737 sheath tank assm.jpg)
![](images/build photos/20260814_111935 waste cap assm A.jpg)
![](images/build photos/20260814_112114 waste cap assm B.jpg)
![](images/build photos/20260814_112146 waste tank assm A.jpg)
![](images/build photos/20260814_112419 waste tank assm B.jpg)

## Prepare and assemble sample loader  {pagestep}

The sample loader is a linkage of several mechanical bodies that are printed in a single piece. Before using, it must be loosened and lubricated. 

To loosen the hinges, apply pressure to the two sets of adjacent hinges as shown. The outer hinges down and the middle hinge up. Alternate between the two sets. If printed well, very little pressure applied with the fingers should be required to loosen the hinges. Once the linkage is loose, add light lubricating oil to the hinges. Then work the linkage back and forth repeatedly until it can move with very little friction. 

![](images/build diagrams/sample loader as printed.png)
![](images/build photos/20260814_113657 sample loader flat.jpg)
![](images/build photos/20260814_113832 sample loader set loose.jpg)

20260814_113858 flex sample loader lubricate.mp4

Attach the two sample loader range limiters to the holes as shown using 2x [M3 self-tapping posi head screws 8 mm](mechanical/screws.yaml#self_tapping_m3x8_posi){qty:1, cat:mechanics}.

Attach the sample loader retaining spring ([Stainless steel extension springs, 0.3 mm wire, 20 mm length, 6 mm diameter](mechanical/extension_springs_20x6x0.3mm.md){qty:1, cat:mechanics}) with a 1x [M3 self-tapping posi head screws 8 mm](mechanical/screws.yaml#self_tapping_m3x8_posi){qty:1, cat:mechanics}.

![](images/build diagrams/sample loader set loose.png)
![](images/build photos/20260814_114021 sample loader limiters.jpg)
![](images/build photos/20260814_114120 sample loader spring.jpg)

Finally, check that the SIP tube will fit in the sample loader: you may need to carefully ream the hole with a 1.6 mm drill bit. The SIP tube is a 78 mm length of [Peek tubing 1.6mm OD 0.25mm ID](fluidic/peek_tubing.md){cat:fluidics}. Cut the required length, straighten it if it was supplied curved, and gentle push it into the hole provided.

![](images/build diagrams/20260530_125001 fit SIP.jpg)

>i **How the sample loader works** 
>i
>i The sample loader is based on a [Kempe Kite Inversor 2](https://www.thingiverse.com/thing:7035940) which is a parallel line linkage: it allows a single degree of freedom, while keeping the SIP and sample tube parallel to each other.
>i
>i ![](https://resize.thingiverse.com/?url=https://cdn.thingiverse.com/assets/f8/a0/0a/b3/31/20250512_135252.jpg&w=1024&h=1024&fit=inside&n=-1)

## Prepare sample (peristaltic) pump assembly  {pagestep}

First fit the barb connectors to the peristaltic pump tubing.

>? **Help Block** 
>?
>? if no barb connectors were supplied with your pump, these can be substituted with 10 mm sections of [Peek tubing 1.6mm OD 0.25mm ID](fluidic/peek_tubing.md){qty:1, cat:fluidics}.

If building the Cytkit 2S-14F, fit the stepper motor connector board to the pump, and ribbon cable to the stepper motor connector board.

Then fit the following tubing to the sample pump:

1. For flow cell sample inlet: 20 mm of [Silicone tubing 2 mm OD 1 mm ID](fluidic/silicone_tubing_1mm.md){cat:fluidics}.
2. For SIP tube: 55 mm of [Silicone tubing 2 mm OD 1 mm ID](fluidic/silicone_tubing_1mm.md){cat:fluidics}.
3. SIP tube itself (as described above).

![](images/build photos/20260814_105418 sample pump with barbs.jpg)
![](images/build photos/20260814_105452 sample pump with barbs and connector board.jpg)
![](images/build photos/20260814_105600 sample pump with tube to SIP.jpg)

## Prepare sheath (vacuum) pump assembly  {pagestep}

If building the Cytkit 1S-1F configuration, first cut 2 x 200 mm wires for positive and neutral connections to the vacuum pump. Solder on end of each to the vacuum pump terminals. Leave the other ends as bare wire to connect to the screw terminals of the motor controller. 

>i If building the Cytkit 2S-14F configuration, the vacuum pump is already supplied with the correct length of wires and a connector to attach to the main board

Place the pump body in the sheath pump holder (flexible printed part). Then cut 90 mm of  [Silicone tubing 6 mm OD 4 mm ID](fluidic/silicone_tubing_4mm.md){cat:fluidics} and put on the end a [Tube barb union 2.4x6.4](fluidic/tube_barb_union2.4x6.4.md){qty:2, cat:fluidics}.


![](images/build photos/20260814_114200 sheath pump assm.jpg)
![](images/build photos/20260814_114216 sheath pump assm 2.jpg)

## Attach tubing to flow cell {pagestep}

Now attach the following:

1. The flow cell sample inlet barb to the open tubing on the sample pump.
1. A barb connector (or 10 mm length of [Peek tubing 1.6mm OD 0.25mm ID](fluidic/peek_tubing.md){qty:1, cat:fluidics}) on the end of the waste tube coming from the flow cell.
1. 470 mm of [Silicone tubing 2 mm OD 1 mm ID](fluidic/silicone_tubing_1mm.md){cat:fluidics} on the flow cell sheath inlet barb.

![](images/build photos/20260814_111404 fluidic system.jpg)
![](images/build photos/20260814_111116 sample pump to flow cell.jpg)
![](images/build photos/20260814_111213 tubing bottom of flow cell.jpg)

## Attach fluidics system to instrument {pagestep}

Insert the flow cell through the hole in the bottom of the base, and screw it tight with 2x [M3 self-tapping posi head screws 16 mm](mechanical/screws.yaml#self_tapping_m3x16_posi){qty:1, cat:mechanics}.

![](images/build photos/20260814_114333 insert flow cell.jpg)
![](images/build photos/20260814_114342 insert flow cell 2.jpg)
![](images/build photos/20260814_114441 screw in flow cell.jpg)

Put the sample pump holder over the sample pump and fasten with 1x [M3 self-tapping posi head screws 8 mm](mechanical/screws.yaml#self_tapping_m3x8_posi){qty:1, cat:mechanics}.

![](images/build photos/20260814_114718 screw on sample pump holder.jpg)

Thread the SIP tube into the sample loader and attach the sample loader to the base with 4x [M3 self-tapping posi head screws 16 mm](mechanical/screws.yaml#self_tapping_m3x16_posi){qty:1, cat:mechanics}. Make sure the flexible tube from the SIP sits in the groove on top of the sample loader and is not pinched by fastening the sample loader.

![](images/build photos/20260814_114824 insert SIP tube in sample loader.jpg)
![](images/build photos/20260814_115103 screw on sample loader.jpg)

Fasten the retaining spring with 1x [M3 self-tapping posi head screws 10 mm](mechanical/screws.yaml#self_tapping_m3x10_posi){qty:1, cat:mechanics}.

![](images/build photos/20260814_115149 screw on retaining spring.jpg)

If building the Cytkit 2S-14F configuration, screw on the sample pump connection board with 2x [M3 self-tapping posi head screws 8 mm](mechanical/screws.yaml#self_tapping_m3x8_posi){qty:1, cat:mechanics}. 

![](images/build photos/20260814_115318 screw on pump connector board.jpg)

Screw on the sheath pump holder to the inside of the stand (left hand side) with 2x [M3 self-tapping posi head screws 10 mm](mechanical/screws.yaml#self_tapping_m3x10_posi){qty:1, cat:mechanics}.

![](images/build photos/20260814_115541 screw on sheath pump holder.jpg)

Connect tubing:

1. Thread the sheath and waste tubing through the respective top holes in the left hand side of the stand. 
1. Connect the sheath tubing to the barb at the end of the sheath tank assembly. 
1. Connect the waste tubing to the barb hanging from the flow cell waste outlet.
1. Thread the pump tubing from the waste tank through the front hole of the second row of holes in the left hand side of the stand, and connect it to the barb coming out of the vacuum pump assembly.
1. If building the Cytkit 2S-14F configuration, thread the pressure sensor tubing from the waste tank through the remaining hole in the second row of holder in the left hand side of the stand.
1. If building the Cytkit 1S-1F configuration, insert a 30 mm section of [Peek tubing 1.6mm OD 0.25mm ID](fluidic/peek_tubing.md){cat:fluidics} in the waste tank vent tubing.
1. Thread the dangling sheath and waste tubes through the serpentine retaining groove.

![](images/build diagrams/20260814_121001 tubing through stand outside.jpg)
![](images/build photos/20260814_115952 route tubing.jpg)
![](images/build photos/20260814_120011 tubing through stand inside.jpg)

## Attach fan holder to stand {pagestep}

These instructions are for the Cytkit 2S-14F only:

1. Insert the blower fan in its printed holder.
1. Route the fan cable, the sheath pump cable and the pressure sensor tubing through the hole in the left rear of the stand to the electronics compartment behind it.
1. Screw on the fan holder
1. Check that the cables emerge at the rear of the stand (in the electronics compartment).

![](images/build photos/20260814_120120 fan assm.jpg)
![](images/build photos/20260814_120515 route tubing and wires to electronics compartment.jpg)
![](images/build photos/20260814_120712 screw on fan holder.jpg)
![](images/build photos/20260814_121154 tubing and wires to electronics compartment from rear.jpg)

## Test and check the fluidics

Make sure SIP tube reaches the bottom of a sample tube placed in the sample loader. 

![](images/build photos/20260814_122331 check sip reaches bottom of FACS tube.jpg)

Make sure the sample loader goes up and down smoothly, stays stably at both the top and bottom positions, and that a sample tube can be inserted and removed easily. You may need to straighten the PEEK SIP tube by bending it in the opposite direction from whichever way it naturally curled.

<video width="640" height="360" controls>
  <source src="images/build photos/20260814_122227 test sample loader compressed.mp4 type="video/mp4">
  Your browser does not support the video tag.
</video>

You have now build the fluidics system and are ready to build the optics!