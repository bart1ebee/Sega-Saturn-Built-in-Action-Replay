
# Sega-Saturn-Built-in-Action-Replay

This will allow you to take an action replay for a Sega Saturn and solder it to the under side of the cart connector to bypass a bad slot.

This currently is setup to work with VA 0 and .5 motherboards I believe it will work with VA1 but do not have a system to test with. In the future I'd like to make the same board or possibly a few boards for all revisions.


## Features

- Enable / Disable with a switch
- Swap between Action Replay and [Pseudo Saturn Kai](https://ppcenter.webou.net/pskai/)
- If PAL equations can be extracted this could be buildable without buying an action replay 

## Parts Needed

- PCB
- Action Replay containing the following
    - 2x HM5117800J
    - 2x sst29ee020-120-4c-nh
    - 2x 74157
    - PAL16L8 
    - PAL24
- Soldering skills
- Optional: the STL folder has a fake cart slot with catches to hold the Action Replay Cart that I added switches to.

## Building

1. Order Boards from a PCB supplier
2. Disassemble an Action replay and assemble on new board
3. SW1 is a SPDT On-On switch and SW2 is a SPST switch On-Off
4. Solder to underside of card slot

## Help Wanted

 Anyone that can extract the logic equations from the PAL Chips.
