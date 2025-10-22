# satellite_imagery
Some satellite imagery that I got from my own atennas! (Currently only from the Meteor M2-3 and Meteor M2-4 sattelites)

Using a RTL-SDR USB with SatDump software!

Here are the antennas I made:

First one is a V - Dipole antenna, it's a bit wonky, but I did get images with it!
<img width="3264" height="1836" alt="image" src="https://github.com/user-attachments/assets/c902f5cb-a1c9-4fd5-a13d-394c46034491" />
Made in an afternoon, it's a PVC pipe structure, with a 3D printed part to hold the pipes at the corrent angles. One arm is connected to the shield of a coax cable, and the other arm to the center of the coax cable. This is plugged in directly into the RTL-SDR USB. It is directional, and doesn't work that well for a long continous signal. But it's good enough to get images out of it, and there is no noise since the Meteor satellites are digital with error correction build in!

My second antenna is a QFH (quadrifilar helix antenna)
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/529e6c81-7660-4abb-a0a0-d0f5817b97e2" />
This one took a while to make, the actual building took an afternoon and evening, but it was a bit hard to find *any* instructions. I eventually found a site that could generate to correct lengths for the frequency I needed to receive, but I was only like 50% sure I was building it right.
And it worked great! It's still a bit directional, but it seems to be way less sensitive to rotation and movement than the V - Dipole.
I posted a few questions on Reddit, and [this person gave me a lot of information in this comment chain!](https://www.reddit.com/r/RTLSDR/comments/1oc9im1/comment/nkl2krq). So if you want to make you own, this might be a good start!
