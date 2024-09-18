# mMARCH.AC

# Credit to Dr. Wei Guo From NIMH

# I made some small changes to bypass the Java (xlsx::read.xlsx and rJava) requirement. Using Java on Linux, especially in a Docker environment, can be a hassle in our LSF system. 

# I also rewrite some of the functions use data.table and edited some of the functions to align with the newest GGIR output. My workflow uses CSV files as input (GGIR::read.myacc.csv), so my output file names is slightly different from the traditional GGIR setup.

# Again, thank you Dr. Guo. Very nice package !!!
