audio_HDAEnabler2
============
OS X Realtek ALC885 through ALC898 Onboard Audio

HDAEnabler2.kext installed with a Patched AppleHDA.kext enables OS X Realtek ALC onboard audio on Intel based motherboards with a bootable clean install of OS X. HDAEnabler2.kext injects Audio_ID = 2 for non-DSDT systems.

In ML, The audio_HDAEnabler1.kext supports 
1. Audio_ID: 2 for 3 port (5.1) Realtek ALC onboard audio
2. Realtek audio codecs: ALC885, ALC887, ALC888, ALC889, ALC892, ALC898

Download
1. https://github.com/toleda/audio_HDAEnabler2
2. Select: Download ZIP

Installation
Install HDAEnabler2.kext with Terminal, DPCIManager, Kext Wizard, etc.

Troubleshooting
1. ML-Patched ALC AppleHDA Capabilities.pdf https://github.com/toleda/audio_ALCInjection
2. Post to http://www.insanelymac.com
3. Post to http://www.tonymacx86.com/audio/76309-mountain-lion-multibeast-no-audio-solutions-problem-reporting.html

Credit
Kabyl

toleda
https://github.com/toleda/audio_HDAEnabler2
HDAEnabler2.kext.zip
README.txt