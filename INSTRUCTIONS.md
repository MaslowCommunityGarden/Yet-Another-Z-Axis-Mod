## Assembly

1. Print one set of all 3D printed parts. Where you need multiples of any given part, the provided STL files include the correct number of parts already. Some notes:
    1. PETG, ABS, or PLA should all be fine. I used PETG for mine.
    2. Default infill should be 20-25% or so, EXCEPT for the router body clamps (v3_body_clamp_upper_half_pair.stl & v3_body_clamp_lower_half_braced_pair.stl). Print those with at least 50% infill for clamping strength.
    3. You should not require supports on any parts EXCEPT the dust shroud (v3_dust_shroud (use supports).stl). Supports will be necessary unless you have a very dialed-in printer.
    4. Some post-printing cleanup may be required, especially on:
        * The slots where M3 square nuts slide in
        * The alignment pegs at the bottom of the rods base (v3_rods_base.stl) and the dust shroud (v3_dust_shroud (use supports).stl)
1. Cut a sled blank. I cut mine on a table saw out of some scrap plywood; just find a way to cut a ~17" roughly-circular blank. 
0. ![Sled Blank](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/sled_blank.jpg)
2. Mark the center on your sled blank and cut a 2 - 2.5" hole as close to center as possible.
0. ![Sled Blank with Hole](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/sled_blank_w_hole.jpg)
1. Find the "rods base" (v3_rods_base.stl) in your 3D printed part set and position it so the snap-off "bullseye" is centered on the hole you just cut. 
0. ![Placing Rods Base](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/placing_rods_base.jpg)
0. (**NOTE:** You can proceed to mark all the holes at one time and then drill them in a following step, or you can mark-drill, mark-drill. The latter is probably more accurate, but I did all my marking in one step, so that's how I talk it through here.)
0. Dry-fit the dust shroud (v3_dust_shroud (use supports).stl) to the rods base using the alignment pegs at the base. (Note, make sure you've cleaned up the pegs of any printing artifacts so you get a nice snug fit; if the pegs don't slide in all the way clean them up some more.)
0. Assemble all parts of the motor brace assembly (v3_motor_brace_assembly_all.stl). It should be self-explanatory enough how to assemble, and the result should look like the following photos. Just remember that you'll need 6 M6 bolts (35mm long to 50mm long) and 6 M6 square nuts to attach the cross-members.
0. Dry-fit the motor brace assembly to the rods  base (there are two alignment pegs at the base to ensure alignment. Remember to clean the pegs & holes up for a snug fit if needed.)
0. Now that you have all the parts that mount directly to the sled dry-fit, confirm the placement of the bullseye and mark all of the holes for drilling. Note:
    2. There are six holes in the rods base
    1. There are four holes in the motor brace assembly
    0. There are two holes in the dust shroud
    0. If you don't have another way to countersink, you can turn your router back into a hand-held router temporarily and use it to router out the countersink holes you need.
0. ![Dry-fit / Hole Marking](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/dry_fit_hole_marking.jpg)
0. Drill and countersink (from below) all the holes you marked.
0. Once you've drilled all of your holes, you can remove the bullseye from the rods base. Just use an X-acto knife or similar to snip it off close to the base:
    0. ![Remove the Bullseye](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/remove_bullseye.jpg)

2. Now mount the two rail support blocks (left and right sides) and the pillow block (center) in the rods base and tighten them down fully. Some notes:
    0. Make sure to come up from below with your bolts.
    0. The pillow-block (center) uses M5 bolts. The rail support blocks take M6 bolts.
    0. The rail support blocks have a slot that is there to make it easier to tighten the lock screw. 
2. Mount the lead screw in the pillow block (in center). It uses two set screws to hold the lead screw fast.  (Note: on mine, the lead screw has a little wobble even when properly secured. It'll all firm up when it's fully assembled.)
3. Mount the linear rails in the rail support blocks and tighten the set screws.
0. ![Assemble Rods Base](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/assemble_rods_base.jpg)
0. Now add the motor brace assembly and bolt it down fully from below.
0. Ditto the dust shroud. It should look like this when partially assembled:
0. ![Partially Assembled](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/partially_assembled.jpg)
0. Now prepare the router clamp as follows:
    0. There are four parts to the router clamp, two per STL file (v3_body_clamp_upper_half_pair.stl & v3_body_clamp_lower_half_braced_pair.stl).
    0. The two parts of the "lower half" join together with the cylindrical pegs, one to the other. Join them together now. (They will probably never come apart once joined, but if you want to be extra safe, put some CA glue in the holes before you join them.) (Note: ignore that in the photo both halves have that smiley-face cutout; yours will only have that on the "bottom" piece.)
    0. ![Join Lower Half](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/join_lower_half.jpg)
    0. The two parts of the "upper" half don't physically join, but you will install them bearing-holder to bearing-holder.
    0. Insert the four 8UU bearings in the bearing holders in the "upper" halves and tighten down with M3x8mm screws and square nuts.
    0. Insert the lead-screw trapezoidal nut in the *bottom* piece of the "upper" half (the one with four additional M3 holes in it for bolting on the dust sleeve). This requires 4 M3x25mm screws and nuts.
    0. Use four M3x20mm screws and nuts to bolt the top half of the dust sleeve onto the bottom of the upper-half bottom:
    0. ![Upper Half Assembled (1)](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/upper_half_assembled_1.jpg)
    0. ![Upper Half Assembled (2)](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/upper_half_assembled_2.jpg)
    0. Finally, insert two M3 square nuts in the bottom piece of the lower-half and place two 8mm M3 screws in them. There are two slots on the ends of the bottom piece to accept the nuts. (Note they will not screw all the way in; they are designed to stick out about 2 mm or so for cleating the dust sleeve.)
    0. ![Install Cleating Screws](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/install_cleating_screws.jpg)
        0. It's best if you try to get the cleating screws at about the right depth now; to do that, fit the bottom half of the dust sleeve (v3_dust_sleeve.stl) on the bottom of the clamp piece, and screw the screw in snugly, then **back it off 1/2 turn**. Now remove the dust sleeve, it goes on only when operating the rig.
        0. ![Install Cleating Screws (2)](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/install_cleating_screws_2.jpg)
0. Install the upper half of the router clamp:
    0. Place the "bottom" piece (the one with the dust sleeve attached) on the rails. Some notes:
        0. Be gentle, if you come in at too much of an angle, you can force ball bearings out of your linear bearing.
        0. You might have to gently straighten out the tops of the linear rods to seat the bearings correctly.
        0. Once you have the bearings on, you will need to push down a little to get the trapezoidal nut to engage the lead screw.
        0. Once the lead screw is engaged, you can move the clamp up and down by turning the lead screw manually.
        0. ![Install Upper Half](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/install_upper_half.jpg)
        0. Now place the other top-half piece, making sure to flip it so the bearing holders are touching each other, as shown.
        0. ![Install Upper Half (2)](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/install_upper_half_2.jpg)
0. Assemble the Axis Cap:
    0. Find the 3D printed part for the Axis Cap (v3_axis_cap.stl)
    0. Insert two M3x8mm screws and *square nuts* in the rod holders. (If you don't use square nuts, you will have to hold the nuts with needlenose pliers when tightening them.) **Leave these loose / not fully tightened.**
    0. ![Rod Holders](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/secure_rod_holders.jpg)
    0. You do not need to install square nuts in the slots in the top of the axis cap; that's a remnant of a previous design iteration.
    0. ![Don't Install Square Nuts](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/dont_install_nuts_here.jpg)
    0. Now use 6 M3x6mm screws to mount the motor from your stock kit. Note the motor shaft should be towards the open side of the axis cap, as shown:
    0. ![Mount Motor in Axis Cap](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/mount_motor.jpg)
0. Mount the Axis Cap:
    0. Find your coupler (from the BOM, not from the stock kit) and slide it on the lead screw. Do not tighten yet.
    0. ![Place Coupler](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/place_coupler.jpg)
    0. Gently place the axis cap on top of the linear rails and slide the motor shaft into the coupler, as shown:
    0. ![Place Axis Cap](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/place_axis_cap.jpg)
    0. Now attach the coupler onto the motor shaft and lead screw using the set screws. Some notes on this:
        0. Slide the coupler up a bit to preserve your full range of motion. But not so high it will grind against the motor screws when in operation.
        0. The upper set screw tightens against the flat side of the motor shaft.
        0. You may need to connect your motor to GroundControl (GC) to get the shaft oriented so you can access the flat side. Use small moves to get the shaft in the correct position.
        0. Once you have the coupler fixed to the motor, use the lower set screw to clamp it to the lead screw.
        0. Following this, find the *other* two set screws and tighten them down as well; this will make sure everything is tight and secure. (Again, you may need to use GC to orient the shaft to permit you access.)
        0. Finally, tighten those M3 screws that secure the linear rods into the rod holders underneath the axis cap.
    0. ![Secure Axis Cap](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/secure_axis_cap.jpg)
0. Bolt the Axis Cap to the Motor Brace Assembly using two 8Mx35mm bolts and two M8 square nuts. You will need to hold the square nuts in place from underneath--the slots for them are on the bottom face of the Axis Cap.
    0. ![Bolt Axis Cap](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/bolt_axis_cap.jpg)
0. Place the Router
    0. Now it's time to place the router. Lay it into the groove created by the two top-half clamps with the front of the router facing towards the hose coupler.
    0. If you had previously greased your router body, as is recommended for the stock kit, clean that grease off before placing it. We don't need it slipping inside the clamp.
    0. Leave about 3/4" or so of the router body visible below the bottom-most part of the clamp. (You can fine-tune the placement later if you find you have too much or too little vertical range.)
    0. The braced-pair "lower" half of the router clamp needs to be mounted to hold it in place. Be sure you place the lower half correctly: with the "smiley" hole and the cleat-screws closer to the sled.
    0. Use 4 M8x35mm bolts and M8 square nuts to secure the lower half of the clamp. It can be a bit tricky to place the nuts, hold the router, and screw things together. It's a bit easier if you flip the whole rig on its back on a table.
    0. It's not horribly important that you have your router precisely facing the hose opening, but get it as close to that as possible. If you mount it wrong, the power cord and back part of the router can make contact with the axis cap and cause runtime issues.
    0. Don't tighten the M8 bolts right away, just make them snug at first. Then check the router's placement and orientation and tighten things down.
    0. When tightening, alternate between the left-side and right-side bolts, using small (e.g. 1/4 turn) turns. This makes sure you don't stress one side of the clamp too much.
    0. Here's where you find out if you printed the router clamp with enough infill. Less than 50% infill and it's liable to crack when you try to tighten it down fully.
    0. ![Secure Router](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/secure_router.jpg)
![Fully Assembled](file:///home/rwales/Pictures/z\ axis\ build\ photos/resized/fully_assembled.jpg)


### Pre-flight and Usage

0. Before attempting any moves in GC, be sure to modify your GC configuration. Find the setting for Z-axis pitch, and put the appropriate setting for your lead screw. If you bought the kit I linked in the BOM, that value should be 8mm.
    0. NOTE that this kit does not have an end-stop, so you can tell GC to crash the nut into the coupler or the pillow-block at bottom. Be cautious in your moves, and be ready to hit the "Stop!" button in GC if you've mistakenly told GC to lower / raise beyond the limits.
    0. Test your kit by moving your new z axis up and down (in small increments at first).
    0. Prior to actually doing any cutting, be sure to define "zero" on your newly-installed Z axis kit.
0. The dust sleeve is designed to go on and come off easily so you can access the collet and change bits. To place it initially:
    0. Slide the back into the cleating screws you placed in the bottom of the body clamp:
    0. ![Using the Dust Sleeve](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/dust_sleeve_1.jpg)
    0. Once the sleeve is fully engaged on the cleating screws, place a medium-size binder clip at the front clip-point (the smiley-shaped opening):
    0. ![Using the Dust Sleeve](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/Version-3/dust_sleeve_2.jpg)
0. To access your collet and change bits and zero your router:
    0. Remove the binder clip and remove the front part of the dust sleeve
    0. Raise your router to maximum height so it clears the dust shroud
    0. You should be able to access the collet lock from behind, and get a wrench into the opening where the dust sleeve had been.
