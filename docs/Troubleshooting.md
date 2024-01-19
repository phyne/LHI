#### General troubleshooting fixes
- is it plugged in?
- is it turned on?
- is power on at the breaker/everywhere along the chain of power?
- check cables are seated properly - power, video/HDMI, ethernet, etc.
- make sure nobody else is currently messing with the thing you are trying to fix - is somebody remoting into the device to do something?
- cycle between IVG and IDA, or cycle between pre-show and show
- turn it off and back on again
- reboot director/audio iMac before rebooting other potentially sensitive equipment
#### Audio glitches (audio drops out momentarily)
- ensure multiple instances of the web panel are closed (check laptop sitting on top of datapaths in the server room)
- ensure multiple people aren't using the two iPads at the same time
#### Main audio isn't working
- if this happens during a show, immediately switch to backup audio by turning on its toggle on the audio page
- ensure toggle for main audio is ON and the volume is turned up
- check that audio is synced to timecode by right clicking the play button in Reaper, tick the checkbox if it isn't
- attempt to reboot the audio iMac by holding the power button, then power back on after 30 seconds
- check if 4 devices are showing up in Dante Controller on the audio iMac
	- if not, re-seat the ethernet cable running into the audio iMac, it may need a reboot as well
#### Backup audio isn't working
#### IDA floor is glitching
- reboot the Cocolabs control PC by going to the windows taskbar, right clicking the windows button, and hitting restart
	- this will take appx. 5 minutes, and the floor will be unresponsive during this time. You can optionally black out the floor projectors in the service page on the web panel. The audio will hitch and the whole gallery will flash briefly when the process is complete
#### A group of wall or floor projectors is showing no content
- does the group of projectors align with a single server on the projector/server/matrix diagram?
	- power off the offending Mac Pro server by holding the power button, then turn it back on after 30 seconds
	- it may take several minutes to come back online, and you may need to power cycle it more than once. If after 3 tries there is still no image being displayed, consult other possible fixes
- does the group of floor projectors align with a matrix on the projector/server/matrix diagram?
	- try other fixes first such as rebooting the director iMac, checking cable connections, rebooting servers, rebooting projectors, etc.
	- if all else fails and the matrix seems to be the culprit, then power cycle the matrix by pulling out the power cable, waiting 30 seconds, and plugging it back in
- does the group of floor projectors occupy 2 sections of floor server only during IDA?
	- power off the offending Cocolabs Thinkstation server by holding the power button, then turn it back on after 30 seconds

#### A single projector is showing no content
- try to press the Power button under projectors on the Service page of the web panel more than once
- power cycle the projector using the Barco Projector Toolset
	- open Projector Toolset on one of the laptops
	- find the projector number using the projector/server/matrix diagram, and click on the corresponding projector in Projector Toolset in the left pane
	- under the general tab in the right pane, click OFF to turn the projector off, and after a few moments, press ON to turn it back on
#### No timecode is showing on the iPad/web panel is unresponsive
- switch back and forth between IVG/IDA/preshow/show
- close the web panel by holding the back button on the iPad, and swiping away the application, then reopen the web panel
- if it still isn't working, reboot the director iMac by holding the power button, then power back on after 30 seconds
- if it still isn't working, reboot the medialon by pulling the power cable, then plug it back in after 30 seconds