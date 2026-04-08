# TODO

- [ ] Ensure lay-flat with stand attached.
- [ ] Ensure lay-flay stand: smaller legs and/or longer face feet.
- [ ] Light Pipe install and tool
- [ ] Pre-drill all but 1 mm of display posts
- [ ] Consider though-holes on posts for center-of-gravity
- [ ] Create full-face stub-out for ULX side (non-developer version, only using display)
- [ ] Improve mounting plate screws and fillets
- [ ] Add stabilizing bolt hole in stand
- [ ] Extend post tube to ULX3S board surface at mounting holes
- [ ] Ensure chamfer is deep enough for flat hex head screws; currently only Philips are flush. Issue only with mounting plate. See `M3_Countersink_Chamfer` dimension. A value of 1.3 mm works for Philips, but hex heads protrude a bit. Edit to 2.0 mm. Added second set of files for Hex Head.
- [ ] Reposition stand mounting screws for symmetry. Recent change extending plate to face broke symmetry.
- [ ] Consider recess for volume knob

## Adapter

- [ ] Add 3rd cable to strain relief
- [ ] Add alternate version for thicker 4 mm USB cables

## Display Blank

- [ ] Increase diameter and measure M2 post sizes
- [ ] Add speaker and other interesting references
- [ ] Recheck stub-outs

## Other

- [ ] Create practice heat set install block
- [ ] Improve USB restrain cap & allow for multiple cable sizes
- [ ] OLED connector blank
- [ ] Buttons blank
- [ ] Full panel blank
- [ ] Recheck (Display_Offset_Post_Height - Display_Post_Height) =  (4)

## Done

- [x] Display has tight fit left-right. Adjusted Bezel_Fit from 0.1 to 0.2, then reverted to 0.1 after chamfer to fillet change
- [x] ULX3S side is too far from PCB
- [x] Display audio input hold is misaligned, 43.16 is 2mm too far; No, it is adjustable!
- [x] Volume Control hole misaligned, no it is adjustable@!
- [x] USB internal USB strain relief posts both misaligned. Fixed, but recheck.
- [x] HDMI alignment can be improved. HDMI position incresed from 34 to 35 mm
- [x] Add fillet to HDMI hole/ (Skipped)
- [x] Move ULX3S USB cable exit holes
- [x] Consider HDMI cap? (Maybe later)
- [x] Loosen Button Diameter. Adjusted to Button_Post_Diameter + 0.3 mm
- [x] Remove display clip chamfer. Suppressed, replaces with 0.5 fillet.
- [x] Add display positioning bracket
- [x] Resize Display Offset Posts (2 only! or all with USB strain relief after moving exit?)
- [x] Keyhole Hanger
- [x] OLED mounting holes
- [x] Fan
- [x] Mounting pin hole depth
- [x] Confirm all header fit
- [x] Confirm OLED and 6 pin TDO position
- [x] Fit button labels arrow alignment
- [x] gojimmypi final ULX3S embossed link (swap, ulx3s on that side!)
- [x] check fan bracket vs USB strain relief on ULX3S side
- [x] Consider higher headers for more room
- [x] or consider arms to mount OLED display
- [x] Thin edges of stand plate
- [x] HDMI Stub-out
- [x] Move USB cable restraint to make room for HDMI internal cable
- [x] Adjust mounting pin USB side
- [x] Check button fit
- [x] Stabilize stand
- [x] Add new front stand clip (skipped, adjusted clips)
- [x] Consider moving chamfer for display mount clip.
- [x] Adjust OLED header Fit. Prior Header_Block_Perimeter = 1.45, updated to 1.5. Confirmed hole increase from 2.9 to 3 mm
- [x] Chamfer OLED post
- [x] Check M3 resize now at 3.1 from 3.05 holes
- [x] Add snap clip (skipped, adjusted clips)
- [x] Remove snap clip post at USB exit (skipped, adjusted clips)
- [x] Test 40 pin header in 12F angled!)
- [x] Create optional shorter stand
- [x] Add HDMI exit holes
- [x] HDMI hole reduces from 15.5 to 15
- [x] Alignment post hole anomalies (see depth)
- [x] Recheck stubout-sizing, USB
- [x] Panel thickness now 1.95
- [x] No display stubout board
- [x] Non-dev ULX3S Side (no cutouts) - will not do, but will add a full-panel stub-out
- [x] M2 - NOT M3 holes for OLED frame
- [x] Keyhole adapter should be a single piece; offset moved when thickness shrank to integral number of print layers: 1.95 mm
- [x] Add Adapter inserts in standoffs
- [x] Roadway restraints
