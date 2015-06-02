# milkrap
Organized version of the files for the MilkRap RepRap 3D printer detailed here:

[Original Instructable](http://www.instructables.com/id/MilkRap-Milk-Crate-RepRap/)

Full credit for design goes to the original author, gmdownes: http://www.instructables.com/member/gmdownes/

Files have been dividd into STL (for printing) and SKP (for editing in SketchUp). I have also included the original pictures and generated gCode files, although if you're printing, you'll want to be creating your own from the STL files.

# Reorganized README
![alt_text](http://cdn.instructables.com/FOV/SK4Q/HIW896HB/FOVSK4QHIW896HB.MEDIUM.jpg "Image Title")

This instructable describes how and why I made a RepRap Prusa Mendel V2 integrated into a Milk Crate (Dairy Crate).

![alt_text](http://cdn.instructables.com/F5D/WXMJ/HIW896I4/F5DWXMJHIW896I4.MEDIUM.jpg "Image Title")

## Step 1: Background

I have been a Maker in the purest form since I was a kid, and I am so glad that there is now a name (and community and movement) for what I am. Just a few years ago I would have to refer to myself as a "guy who liked to take things apart to see how they worked and also build stuff". Just saying "I'm a Maker" is sooo much easier. 

I purchased a RepRap Prusa Mendel V2 kit from the good folks at Maker Farm (thank you Colin for all your support) about 8 months ago and immediately fell in love with the machine and with 3-D printing.  But a few things about the Prusa struck me as opportunities for improvement. In particular was that to build a Prusa, the first thing to do is make a frame out of thin air (not literally of course, but constructing the frame from threaded rods is a slow process requiring lots of measuring, cutting, joining, leveling, and plumbing). So I began thinking of ways to build a Prusa into a rigid frame that was easy to construct (good) or already constructed (better). 

I am also an avid fan of recycling and finding alternative uses for objects borrowed from other industries. Then, I either saw or remembered seeing piles of milk crates sitting behind a convenience store getting dirty and abused, or milk crates being used as shelving in a college dorm, or as a  step stool in a mechanics garage, etc. It struck me that milk crates are everywhere you look and are also built to be very strong. As it turns out, the interior dimensions of a rectangular milk crate is big enough to insert the working parts of a Prusa Mendel and achieve the same build area in the X and Y direction and...

## Step 2: Advantages over a RepRap Prusa Mendel V2

![alt_text](http://cdn.instructables.com/FLI/19H0/HIW896HV/FLI19H0HIW896HV.MEDIUM.jpg "Image Title")

## Step 2: Advantages over a RepRap Prusa Mendel V2

get even more buildable area in the Z direction!

Because the rigidity of the milk crate comes from the sides and base, it doesn't need upper crossing members for support (as the Prusa does). This allows the X carriage to move and print as high as your imagination (provided you use Z axis threaded rods long enough and create support towers (see step 10) large enough to hold them. A  standard Prusa that comes with a Greg's Accessible Extruder like the one I ordered has an actual print area of about X=7.5" before the extruder motor hits the Z axis threaded rod, Y=8.5", and Z=4.5" before the large extruder gear hits the upper threaded rod crossing member. That is an actual build area of about 287 cubic inches. 

Changing the extruder to a smaller Bowden tube style would capture another inch in the X direction and almost 3" in the Z direction so the print area increases to 542 cubic inches but there is still an eventual limit in the Z direction due to the crossing members. 

Other advantages of the MilkRap design are: 

1. Easier to build for a novice or non-technical person
2. Much faster to build
3. Extremely portable
4. Very durable
5. Milk crates are cheap (please remember that taking a milk crate from behind a store, etc is stealing. I purchased my milk crate from http://www.milkcratesdirect.com/ for $8 plus shipping
6. Milk crates provide lots of places to attach unruly wires
7. All belts are tension-able in place using tensioning screws
8. Lighter/minimalist X and Z carriages to reduce weight and increase speed
9. Simplified custom Bowden Tube / Direct Drive extruder
10. Z axis threaded rods are easily plumbed
11. No more bulky 5/16" bolts in the Y and X idlers
12. A great conversation starter!

## Step 3: Download and print the STL or SKP files for the plastic parts

![alt_text](http://cdn.instructables.com/FV6/FEF8/HIW896QK/FV6FEF8HIW896QK.MEDIUM.jpg "Image Title")

Files are HERE!!

[Original Dropbox Files](www.dropbox.com/sh/37b4i8u9jlcf2ct/Q4O8GUcQ5J)

You can also use the `Download as ZIP` option from GitHub's side menu for the reorganized version included with this repo.

See comments for extra notes.

## Step 4: Use the jigs

![alt_text](http://cdn.instructables.com/FV1/U606/HIW896IE/FV1U606HIW896IE.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FW2/MMFE/HIW896IF/FW2MMFEHIW896IF.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FPP/QYLP/HIW896IG/FPPQYLPHIW896IG.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FKC/978H/HIW896IH/FKC978HHIW896IH.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/F4N/6GSB/HIW896II/F4N6GSBHIW896II.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/F3G/CL09/HIW896IJ/F3GCL09HIW896IJ.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FQ6/M633/HIW896PD/FQ6M633HIW896PD.MEDIUM.jpg "Image Title")

1. Use the printed jigs to position and drill attachment holes for the Y axis smooth rod, motor, and idler mounts as well as the Z axis motor mounts. The jigs are designed to be a negative match of the physical geometry of the milk crate and ensure exact placement of mounting holes. 
2. Slide linear bearings over Y axis smooth rods and Insert rods into rod mounts. 
3. Attach mounts to the milk crate via holes from previous step with 6-32 screws and nuts. 
4. Attach Y motor to motor mount and motor mount to milk crate. 
5. Now attach Y idler to milk crate the same way. The Y idler uses a standard 608 skate bearing. Lots of Prusa kits come with 5/16 bolts to attach these bearings. To me that was like using a sledge hammer as a fly swatter so I printed some 5/16" OD 9/64"ID inserts to be able to attach the bearings with 6-32 machine screws. I used the same inserts to attach the 608 bearing in the X idler. Attach Z axis motors to mounts and mounts to milk crate via holes drilled previously.

## Step 5: Standard RepRap stuff

![alt_text](http://cdn.instructables.com/FTK/MC6I/HIW896PW/FTKMC6IHIW896PW.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/F1N/ELVS/HIW896PY/F1NELVSHIW896PY.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/F9V/S8OC/HIW896PX/F9VS8OCHIW896PX.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FSS/7Y9Q/HIW896PV/FSS7Y9QHIW896PV.MEDIUM.jpg "Image Title")

Because this is a RepRap based printer, a lot of the build procedures are very similar to building a RepRap. So, to save time I will refer you to the myriad online sources of instructions for building a RepRap including (https://docs.google.com/file/d/0B80A_woXoRWdYmZFeFBkR3NvOXM/edit and http://reprap.org/wiki/RepRap_Options) These web pages will guide you through the basic processes used in building these parts of your Milk Strap: Y axis smooth rods to linear bearings and build plate (heated or not), X axis motor mount and idler attachment to X axis smooth rods and Z axis threaded rods, attaching all wires and electronic components.

## Step 6: Milk Crate reinforcement

![alt_text](http://cdn.instructables.com/F3B/JV52/HIW896JH/F3BJV52HIW896JH.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/F42/ZULY/HIW896JI/F42ZULYHIW896JI.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FBZ/NNVZ/HIW896JL/FBZNNVZHIW896JL.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FAD/NXJR/HIW896JK/FADNXJRHIW896JK.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FVP/GGFS/HIW896JG/FVPGGFSHIW896JG.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FCI/X3J6/HIW896JN/FCIX3J6HIW896JN.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FL3/DOBQ/HIW896JF/FL3DOBQHIW896JF.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FHM/LIZI/HIW896NT/FHMLIZIHIW896NT.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FAE/P7XS/HIWONPHH/FAEP7XSHIWONPHH.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FOM/Q03L/HIW896N7/FOMQ03LHIW896N7.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/F05/BDHH/HIW896JE/F05BDHHHIW896JE.MEDIUM.jpg "Image Title")

Although milk crates are designed to be very tough, I did find it necessary to add a piece of 3/4" x 3/4" x 1/8" thick aluminum angle to the long edges at the top of the crate. I chose to mount the aluminum in a way that did not require drilling through it (though in hind sight that may have been easier or at least used smaller/fewer printed parts. The jigs used to position the mounting holes remain in place after the holes are drilled and become a permanent part of the machine. Jigs are placed and holes drilled for the two outside brackets and one middle bracket. Aluminum is manually held in place while the other parts of the brackets are bolted on. Now the aluminum is secure. The middle bracket is much larger than the outer brackets and becomes the Z axis tower. This tower holds the tops of the Z axis threaded rods in place.

## Step 7: Z axis towers

![alt_text](http://cdn.instructables.com/F8K/ETGU/HIW896BV/F8KETGUHIW896BV.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/F3C/97JN/HIW896CB/F3C97JNHIW896CB.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FN0/AA1H/HIW896D0/FN0AA1HHIW896D0.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/F86/FH42/HIW896CS/F86FH42HIW896CS.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FNP/6R85/HIW896CT/FNP6R85HIW896CT.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FNB/5IXK/HIW896CD/FNB5IXKHIW896CD.MEDIUM.jpg "Image Title")

The Z axis towers are the key to the "unlimited" Z axis printing height of this machine. Because this is the first iteration of this machine I have produced, I chose a Z tower height I was absolutely sure would be stable while the machine was printing. I highly encourage you to manipulate the SKP files to create larger/higher towers and push the envelope, just make sure the wall thicknesses and geometry of the towers can support the height you choose. I will be doing the same when I get a chance. I hope to hear from you! The towers are topped with a two piece system. The first piece is inserted into the main body of the tower and is designed as a "track" in which the second piece (which holds the bearing) can slide in either direction along the X axis. Using a plumb bob, the bearing holder is positioned by the builder until the 5/16" Z axis threaded rod is plumb. Once plumb is attained, the bearing holder is permanently affixed to the track via small screws.

## Step 8: Bowden / Direct Drive Extruder

![alt_text](http://cdn.instructables.com/FLW/XKC4/HIW896EM/FLWXKC4HIW896EM.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FKV/5JMX/HIW896ES/FKV5JMXHIW896ES.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FW6/4U63/HIW896EX/FW64U63HIW896EX.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FVD/P54I/HIW896EY/FVDP54IHIW896EY.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FWY/I8B3/HIW896EZ/FWYI8B3HIW896EZ.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FT8/O8JU/HIW896FC/FT8O8JUHIW896FC.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FZK/6EGA/HIW896FF/FZK6EGAHIW896FF.MEDIUM.jpg "Image Title")
![alt_text](http://cdn.instructables.com/FHL/498H/HIW896GE/FHL498HHIW896GE.MEDIUM.jpg "Image Title")

I chose to use a Bowden tube extruder with a direct drive feed system as this spoke to my desire for simplicity. Neither of these pieces are ground breaking on their own and many versions of these devices can be found on the web. I chose to use a Mk-2 J-head hot end because it is the same one that came with my Maker Farm Prusa and it has worked without flaw. The PTFE Bowden tube is held in place via a simple holder and sharp set screws that pierce the PTFE Bowden tube but do not penetrate all the way through (drywall screws work well but are a bit big, or you can sharpen a small #2 wood screw). The extruder is my own design. I had read some opinions that a NEMA 17 does not have enough torque to direct drive 3mm filament so I figured I would hedge my design by using two NEMA 17's rotating in opposite directions (each with a MK-7 drive gear). 

## Step 9: Thats It !!

![alt_text](http://cdn.instructables.com/FRO/4NHL/HIW896B6/FRO4NHLHIW896B6.MEDIUM.jpg "Image Title")

Milk Raps really are easy to build, especially compared to a Prusa V2. I see that the Prusa i3 addresses many of the issues I had with the Prusa V2, and although I have not seen an i3 up close, it doesn't appear to have the durability or portability of a Milk Rap and it still has a crossing member that will ultimately define the Z axis max height. Really though, at the end of the day I just had to make my own machine. Makers gotta make and hackers gotta hack (the good kind). 

