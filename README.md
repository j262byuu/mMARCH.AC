# mMARCH.AC

# Credit to Dr. Wei Guo From NIMH

I made a few small changes to bypass the Java requirement (xlsx::read.xlsx and rJava). Java on Linux, especially in a Docker environment, can be quite a hassle in our LSF system.

I also rewrote some functions using data.table, which sped things up significantly. Now, part 1 only takes about 1-3 minutes per file for a 9-day measurement.

Additionally, there was an issue with the multiple CSV header in module1c_data.transform.merge.sw. It's fixed now.
 
# Again, thank you Dr. Guo. Very nice package !!!
