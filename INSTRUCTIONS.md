## Assembly

1. Decide where to mount the mounting plate on your sled. The mounting plate has a snap-off "bullseye" that you should position at center, right where you want the router bit to land. Use that to position the foot where desired, and mark / drill the mounting holes. (The plate is designed to be held down by the screws that hold the various feet. To mark / drill the holes, I recommend clamping the mounting plate down temporarily.) Some additional notes:
    1. You can also just use the mounting plate as a drill template and not have it permanently attached to your sled. Other than correctly positioning the three feet, it has no real functional purpose, though it will raise the rails / router up by 1mm. Personally I like having it mounted so I know the feet (and therefore the rails) are in the correct positions.
    2. If you leave it mounted, you should snap off the bullseye after you have the template mounted. Carefully use a knife or scissors to remove the arms where they attach to the mounting plate.
    3. ![Mounting Plate](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/master/mounting_plate.jpg)
2. Now mount the two rail support blocks (left and right sides) and the pillow block (center) in the mounting plate. Note the rail support blocks have a slot that is supposed to make it easier to tighten the lock screw (but honestly it ought to work both ways). Tighten them down fully.
2. Mount the lead screw in the pillow block (in center). It uses two set screws to hold the lead screw fast.  (Note: on mine, the lead screw has a little wobble even when properly secured. It'll all firm up when it's fully assembled.)
3. Mount the linear rails in the rail support blocks.
4. Prepare the router clamp by installing the two 8UU bearings in the bearing holders, and tightening down the lead-screw trapezoidal nut. Use 3-4 25mm M3 screws to secure the trapezoidal nut, and two 10mm (or 12mm) M3 screws-with-nuts to lock the bearings into the bearing holders.
5. (CAREFULLY) slide the bearings and lead-screw onto the smooth rods and the lead screw you've just mounted on your sled. Be careful not to come in at an angle, as that can push ball bearings out of the 8UU bearing unit. Also note, you may have to line your lead screw up with the nut, and you will have to give it a couple of turns to get the collar fully mounted on the rails. Using the lead screw, move the collar about 1/2 way down the rails.
6. Prepare the axis cap for mounting:
    1. Slide two square nuts into the square holes in the middle of the square protrusion. Push them all the way down in the slot so they align with the holes on the face of the block.
    2. ![Placing square nuts](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/master/placing_nuts.jpg)
    3. Pre-position two 10mm (or 12mm) M3 screws with *square* nuts on the two smooth-rod holders. (The square nuts should let you tighten the screws without holding needle-nose pliers on the nut.) Make sure to leave these loose for now; you only want to tighten them after the rods are inserted.
    4. Mount the motor (the one from the stock kit) on top of the black bracket (also from the stock kit). Use 4-6 8mm M3 screws.
    5. IMPORTANT NOTE: make sure the shaft of the motor is towards the open side of the U-shaped opening. If you don't, the shaft coupler won't line up properly.
    6. ![Axis cap underside](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/master/mounting_motor2.jpg)
    7. **IMPORTANT**. Hook the motor up to your Arduino and fire up ground control. Since you can't hand-position the orientation of the motor, you need to use GC to orient the shaft of the motor correctly.
      1. First use GC to position the motor with the flat part of the shaft facing outwards (from the u-shaped slot in the axis cap).
      2. Slide on the 6mm end of the shaft coupler and tighten. Make sure the coupler clears the M3 screws holding the motor.
      3. Using 2 10mm (or 12mm) M3 screws, secure the black bracket to the axis cap (these go in the slots on the front of the bracket, and into the square nuts you installed earlier in this step). Do not fully tighten these yet.
      4. ![Mounting the bracket](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/master/mounting_bracket2.jpg)
7. Mount the axis cap:
    1. Carefully slide the axis cap onto the smooth rods and the lead screw. The coupler goes on the lead screw, and the smooth rods go into the rod holders.
    2. ![Placing the axis cap](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/master/placing_axis_cap.jpg)
    3. Tighten the rod holders using the two 3mm M3 screws you pre-positioned earlier.
    4. Tighten the shaft coupler on the lead screw. You probably will have to use GC to re-orient the shaft so you can reach the set screw.
    5. ![Axis cap placed](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/master/placing_axis_cap2.jpg)
    6. The shaft coupler also has two circumfrence screws that need to be tightened. Again, use GC to rotate these screws so you can reach them and tighten.
    7. ![Securing coupler](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/master/securing_coupler.jpg)
8. Mount the bottom section of the black z-bracket (from the stock kit) to the sled and secure to the upper section with 4 M3 screws/nuts (these came with the stock kit).
5. Attach the router clamp (the two-piece circular collar) to the router itself. Some notes on that:
    1. This is a tricky step, at least if you have to work vertically as I did. If you can flip your sled 90 degrees or so so the router is laying down instead of being vertical, it may make things easier.
    2. If you had previously greased your router body, as is recommended for the stock kit, clean that grease off. We don't need it slipping inside the collar.
    3. Make sure you orient the *side* of the Ridgid router against the side where the rails and lead screw live. At certain heights the front-side or back-side will interfere with the rails or axis-cap, but there is just enough clearance if you orient it with one of the two sides against those moving parts (e.g. it's facing leftward or rightward).
    4. You should install the clamp fairly low so it has a good range of motion. I put mine right above where the "nib" is on the router itself (the protrusion on the body that slides up and down a groove in the router's collar to keep it locked in orientation).
    5. Tighten evenly, working one side then the other until fully tightened. Mine holds the router securely with no gap between the parts of the collar when fully tightened.
9. Before attempting any moves in GC, be sure to modify your GC configuration. Find the setting for Z-axis pitch, and put the appropriate setting for your lead screw. If you bought the kit I linked earlier, that value should be 8mm.
    1. NOTE that this kit does not have an end-stop, so you can tell GC to crash the nut into the coupler or the pillow-block at bottom. Be cautious in your moves, and be ready to hit the "Stop!" button in GC if you've mistakenly told GC to lower / raise beyond the limits.
9. Test your kit by moving your new z axis up and down (in small increments at first).
10. Prior to actually doing any cutting, be sure to define "zero" on your newly-installed Z axis kit.

![Fully Assembled](https://raw.githubusercontent.com/MaslowCommunityGarden/Yet-Another-Z-Axis-Mod/master/beauty_shot.jpg)
