This is a public facing repository to provide a [Wiki](https://github.com/JamesCC/VMX-Serial-Remote/wiki) and [Release APKs](https://github.com/JamesCC/VMX-Serial-Remote/releases).

# CHANGE LOG

24 v1.17 (30th Sep 2025)
- Meet Google's Data Policy and various declarations to reinstate App on Google Play 
- Update to support Android 16 (API level 36)
- Remove QR scan and generate feature as the ZXing barcode scanner App is no longer available
- Added necessary padding to avoid menu bars overlaying clickable items

23 v1.16 (28th Oct 2019)
- Update to support Android 10 (API level 29)
- No functional change.

22 v1.15 (27th Jan 2019)
- Screen kept on whilst in app
- Option to disable fader lock (so faders can be always adjusted)

21 v1.14.2 (18th Mar 2018)
- Fix Scan QR code for default Aux Channel (remember to disable "Default to Main Output" setting)

20 v1.14.1 (19th Feb 2018)
- Fix "Bad Syntax" errors when adjusting AUX feeds on some V-Mixer consoles

19 v1.14 (4th Feb 2018):
- Paired AUX feeds pan settings are now preserved (not reset back to centre upon level change)

18 v1.13.2 (21st Jan 2018):
- Now remembers last output channel selected between connections (see settings).  This is saved in shared QR codes
- Description of configuration when disconnected
- Splash screens made more pleasant

17 v1.13.1 (18th Jan 2018):
- Support LCR mode on M400 where one AUX is allocated for Centre (avoids "Parameter out of range") - covered corner cases

16 v1.13 (14th Jan 2018):
- Support LCR mode on M400 where one AUX is allocated for Centre (avoids "Parameter out of range")

15 v1.12.1 (7th Jan 2018):
- Fix for Android Nougat, Oreo where the default styling theme is light rather than dark
- The above fix means the minimum Android version is now Lollipop (Android 5) upwards.  Please email me if support is still desired for these older devices.

14 v1.12 (6th Jan 2018):
- Allow user to filter the input list, by selecting listed channels
- Colour output selection Combo box (MAIN/AUX..) when selecting AUX
- Avoid excessive toast notifications when faders a locked

13 v1.11 (28th Jan 2016):
- Avoid crash upon returning with no QR code (when used in settings)
- Avoid Multiple instances on pre Lollipop phones when started from different launchers

12 v1.10 (10th Jan 2016):
- QR Code settings transfer
- Fix shutdown fault (resulted in multiple instances on some phones)

11 v1.9 (30th Aug 2015):
- fix update for stereo pair fader adjustment when adjusting AUX outputs
- add a message when attempt is made to adjust a locked fader

10 v1.8 (23rd Aug 2015):
- fix colour transparency for pre Android 5.0 devices

9 v1.7 (19th June 2015):
- 2 columns for tablets
- colour to indicate MUTE status

8 v1.6 (14th June 2015):
- Adjust faders from main screen (press and hold to "unlock fader adjustment", for Input Adjustment touch dB value)
- Multiple devices can access to the mixer simultaneously, through a new VMXProxy (vmxproxypy).

7 v1.5 (8th Mar 2014):
- Minor bug fixes to aid robustness
- Network Discovery reworked

NOTE:  When "Search for Server" is selected it uses Google's Service Discovery APIs.  Under Jelly Bean there have been reports that it can get into a state where the app constantly crashes (a fault outside of the app).  A reboot of your phone/tablet should resolve it.

---

Version 1.4: (29th Dec 2013)

Version 1.3: (2nd Dec 2013)

Version 1.2: (16th Jul 2013)

Version 1.1: (6th Jul 2013)

Version 1.0: (25th June 2013)
