cinécal
=======

simple image gallery screensaver for mac
made with quartz composer


how to install;

1. you need to put the cincecal.qtz file in your 'screen savers' folder. OS X hides this folder, but you can get to it by opening Finder and clicking 
'Go' > 'Go to folder' 
then typing the file path `~/Library/Screen Savers`

2. set cinécal as your screensaver in 
'' > 'System Preferences' > 'Desktop & Screen Saver'
(cinécal will be at the bottom of the list)

3. set your own image directory and adjust how long each image displays in the 'Screen Saver Options'


the screen saver works by;

1. loading a folder of images (by default the current user's `/Pictures` folder)

2. using a random number generator to select two images

3. resizes the images if they are over a certain size (more than 100% the window height for the first image, more than 120% for the second image)

4. positions the first image in the bottom right of the window, the second image in the centre left

5. replaces each image at alternate intervals with a new random image (by default after 3 seconds)



-
mark hurrell
mhurrell.co.uk
@markhurrell
