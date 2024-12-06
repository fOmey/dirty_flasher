# dirty_flasher
Fool proof flashing tool (hopefully).. we're testing, so I don't have much confidence yet.

I couldnt break it tho? That should say alot.

# web browser flasher ~ esp web tool (recommended method!)
[fomey.github.io/dirty_flasher](https://fomey.github.io/dirty_flasher/)

# instructions (end game / game over module ~ flipper zero flash)
Flipper Zero:
* GPIO -> USB-UART Bridge -> Left navigation key
  * `Baudrate` is set to `115200`
  * `UART pins` set to `13,14`

End Game Module:
* Slide switch in middle position

Windows PC:
* Plug flipper zero into PC
* Right click `dirty_flasher.ps1`
  * Run with powershell
  * Follow on screen prompts

# instructions (t-display)

Windows PC:
* Plug T-Display S3 into PC using onboard USB-C port
* Right click `dirty_flasher.ps1`
  * Run with powershell
  * Follow on screen prompts

# notes
If powershell opens and closes immediately, this is probably caused by the script execution policy.

You can allow all scripts by launching `powershell` as `administrator` and running the following command: `Set-ExecutionPolicy Unrestricted`

For more information visit: [learn.microsoft.com](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.security/set-executionpolicy?view=powershell-7.3)

# game over - gps module pinout diagram

![Game Over](https://github.com/fOmey/dirty_flasher/blob/main/img/GameOverGPS.jpg?raw=true)

# end game - gps module pinout diagram

![End Game](https://github.com/fOmey/dirty_flasher/blob/main/img/EndGameGPS.jpg?raw=true)