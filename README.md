mixxx_touchosc_mapping
======================

Mapping to use the TouchOSC Jog-On iPad template to control the Mixxx DJ software

Installation on OSX
-------------------

- Copy these files into `/Applications/Mixxx.app/Contents/Resources/controllers`
- Put your iPad and your laptop on the same wifi network
- Run TouchOSC Bridge on your laptop
- Start TouchOSC on your iPad
- On the iPad TouchOSC settings, choose Connections->MIDI Bridge
- Your laptop should appear in the MIDI Bridge settings under Found Hosts. Select it.
- Start Mixxx and open Preferences
- Under Controllers, TouchOSC Bridge should appear
- In the Load Preset, choose "TouchOSC iPad Jog-On" and you should be good to go.

Volume, crossfader, pitch control, play, cue, beatsync, playposition, and jog wheel are mapped so far.
I will add more controls when I have time.
