# Ubuntu installation from a mac

Complete guide locate here: http://www.udoo.org/getting-started/

+ grab an SD card at least 8G big (the image is 6.5G big)
+ download the image from udoo site (http://www.udoo.org/downloads/)
+ use 7z to unzip it into a img file (unzip can''t process it for some reason)
+ once the sd card is unmounted (with diskutil), use dd to transfer the img file to the card
    + dd bs=1m if=the_img_file of=/dev/your_appropriate_rdisk

That should be it.

Now plug the sd in the udoo, and start it (power it).
If it''s plugged on an ethernet network it will automatically acquire an IP and be recognized with the name *udoobuntu*.
The root password is *ubuntu*.

-- Nicolas
