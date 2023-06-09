# dirty_flasher
Fool proof flashing tool (hopefully).. we're testing, so I don't have much confidence yet.

I couldnt break it tho? That should say alot.

# instructions (flipper zero used for flash)
Flipper Zero:
* GPIO -> USB-UART Bridge -> Left navigation key
  * `Baudrate` is set to `Host`
  * `UART pins` set to `13,14`

End Game Module:
* Slide switch in middle position

Windows PC:
* Plug flipper zero into PC
* Right click `dirty_flasher.ps1`
  * Run with powershell
  * Follow on screen prompts
