# simple3dscanner
<b>What do you need for program testing?</b><br /> 
Raspberry pi 2, Raspberrypi camera, - it works in Python with Pygame module

What more do you need for scanner testing?
red line laser, voltage source 12V + step motor with driver - I am using NEMO and A4988
...point cloud to MeshLab

picture of hardware:
https://www.instagram.com/p/BEYQFLeR7QY/?taken-by=octopusengine

schematic:
http://www.octopusengine.eu/2016gal/scanner-schematic.gif


simple idea - how to create points cloud:

loop {

  > take a picture 

  > recognize red line

  > transform to xyz
  
  }

 example of processing
  https://www.instagram.com/p/BEYRg99R7TE/?taken-by=octopusengine


<h3>HISTORY:</h3> 

 2016/04/18 - 0.1 first experiment, it works! I was really surprised ;-)

 2016/04/21 - 0.2 my first "open source" pos on GitHub - simple starting on your Raspberry pi: sudo python scan.py

<h3>TODO:</h3>

 better user input / GUI
 
 light detection / daylight.. color of object..
 
 faster computing / C library or Cython testing
 
 digital filter - RAW data filtering
 
 converting to STL
 
  
