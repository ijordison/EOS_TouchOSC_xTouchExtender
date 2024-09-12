# EOS_TouchOSC_xTouchExtender
A TouchOSC patch to use an X-Touch Extender to control ETC EOS family lighting consoles.
The xtouch must be in CtrlRel mode, connected over USB. Boot it while holding down ch1 select to change the mode.
The TouchOSC session must have bi-directional MIDI connections to the X-Touch-Ext, and OSC UDP connection EOS. 
EOS must have, under Show Control, OSC Rx and Tx enabled, with the same ports as TouchOSC. It must also have the OSC UDP TX IP Address set to the TouchOSC's IP.

Start the console, start the TouchOSC file, turn on the X-Touch Extender, then touch any fader to initalize.
