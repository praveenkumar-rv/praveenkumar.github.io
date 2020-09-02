[Index page](../)

## Optimization - Aosp

##### By : [AtomicX](https://t.me/AtomicXZ)

1. Download [BBS](https://forum.xda-developers.com/attachment.php?attachmentid=3993890&d=1483785763) and install it. 

2. Open BBS app, give all the necessary permissions and then let it run. (This app takes approximately 1% every 18hrs or so, so don't worry about it taking much battery.)

3. Use the phone for an entire cycle.

4. See whatever app/component is taking battery in the background. ( I suggest checking 'Sensors' and 'Partial Wakelocks' for idle drain and 'Process' for active drain)

5. Now that you have figured out what is using battery disable it.

~ Check 'Block Sensors' setting for apps listed in 'Sensors' taking excessive battery. <br/>
~ Check 'Block Wakelocks' setting for apps listed in 'Partial Wakelocks' taking excessive battery. <br/>
~ Force close any apps listed in 'Process' taking excessive battery.

Note - This requires root.
