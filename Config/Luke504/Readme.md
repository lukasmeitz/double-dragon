## Introduction

These configuration files work for my Double Dragon build that can be 
seen in the build-log at https://discord.com/channels/825469421346226226/1085616148336365738.

I made some changes to the original design, which are following.
Hardware:
- widened the frame to fit a 250mm wide Tri-Zero based bed
- boxed the whole thing drawing inspiration from Box-Zero (this affects the motor mounts A/B and the front idlers)
- went for the wider MGN9H carriages (instead of MGN9C) and swapped the carriages (T0 now is left)

borrowed from harry-boe (https://github.com/harry-boe/double-dragon/tree/main):
- incorporated a single-y drive
- added a servo-deployed klicky probe to the mini-afterburner toolhead

Software based on joseph-greiner's work (https://github.com/joseph-greiner/tridex_mods/tree/main/printer_configuration)
- the configuration incorporates the idex modes now supported natively by klipper
- printer.cfg fits the swapped toolhead, so back left motor drives the right carriage and vice versa
- configured dimensions of the build and the position of the klicky probe dock
- configured the print_start macro without nozle purge and wipe for now

