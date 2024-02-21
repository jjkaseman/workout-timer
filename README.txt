Countdown timer that loops continuously.

All sounds should be around 2 seconds long, and must be one of the following filenames:
    endSound.mp3 - the sound to play at the end of a loops
    warningSound.mp3 - the sound to play when there are 10 seconds left
    halfSound.mp3 - the sound to play halfway through a loop
If the timer is set to 20 seconds, the warningSound will play instead of the halfSound.

Checking the 'Start with +20s' checkbox will add 20 seconds prior to starting the first loop.  
The endSound and warningSound will play prior to the first loop officially begins.
Once the timer is started, the checkbox will be disabled and it won't be enabled until the timer has been fully reset.

The 'Start' button can be clicked to start the timer, and to continue after pausing.
If no time has been added to the timer then 'NaN' (not a number) will display to remind the user to add time.

The 'Pause' button will stop the timer during the current loop.  The 'Start' button will need to be used to re-start the timer.

The 'Reset' button has 2 functions.  
If the button is clicked while the timer is ticking down, it will revert to the start of the loop.  
    The 'Total' time display will not reflect the time elapsed up to when the 'Reset' button was clicked.
Clicking the 'Reset' button prior to starting, or clicking twice once the timer has started, will reset the timer to 0 and clear the 'Total' time.

Time can be added to the timer using the buttons below Start/Pause/Reset.  The buttons work during a loop as well.
    +10s will add 10 seconds to the current timer
    +1m will add 1 minute to the current timer
    +10m will add 10 minutes to the current timer
    +1h will add 1 hour to the current timer