**DetectMove**
example of how the code detect move
<img width="294" alt="image" src="https://user-images.githubusercontent.com/108711023/183978424-dd6a16f0-1c19-4ddc-8893-37b6391bc0d3.png">

**Using DvrScan to seperate moving video**
- Create a directory called temp in c:\
- Beginning with the first file (chronologically) of the 24 hr day, rename them 1.avi through 10.avi or 11.avi, depending on how many there are
  Type cmd in the command box
- Copy and paste the program below, substituting the date of the 24 hr collection in place of 8_18 below

cd c:/temp
dvr-scan -i 1.AVI -i 2.AVI -i 3.AVI -i 4.AVI -i 5.AVI -i 6.AVI -i 7.AVI -i 8.AVI -i 9.AVI -i 10.AVI -i 11.avi -i 12.avi -o 9_1-motion.avi -roi_

When the process is done, the videos would be seperated. 

Below is the abstract of our paper


