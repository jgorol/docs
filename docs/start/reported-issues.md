# Reported Known Issues

!!! info "Always Try This First"

    Please try and remove all other mods/liveries from the community folder and test our mod again. This will help rule out mod conflicts.

    <sub>Report back the result of this test on our Discord.

!!! warning "After Microsoft Flight Simulator Updates"

    Make sure you do a full reinstall A32NX. Delete either of the folders below from your community folder: 

    * A32NX
    * flybywire-aircraft-a320-neo 
    
    Do this before reporting bugs. 

FBW Installer - [Download Here](https://api.flybywiresim.com/installer) / *Sim Version: 1.15.7.0*

*Last Update: {{git_revision_date_localized}}*

---

### ^^Latest Issues^^

!!! warning "Liveries incompatible due to Hard Fork"

    **Will only affect new versions of the development and experimental branches for now (a 0.6.0 stable release with the fork will come within the week).**

    Liveries made for the default A320neo will no longer function in the new FlyByWire package. Liveries will need to be converted by their respective authors. 

    While this might represent an inconvenience for a short amount of time, we are sure that 3rd party content authors will be quick to provide you with updated liveries and programs. *If you wish to avoid this, we advise that you remain on your currently installed development/experimental versions for now.*

    **Workaround:** See our guide to [convert liveries](convert-liveries.md) 

* Package separation or "fork" issues (*Development or Experimental*):
    -  Default aircraft showing
        - Solution: Select the *FlyByWire Simulations A320neo (LEAP)* in the aircraft selector instead of the Asobo one. 
    - Invisible plane / Sounds not working / Installation issues
        - Workaround: Reinstall A32NX, delete any old version from your Community Folder. Ensure you are on Installer v1.1.4.
* Installer Memory Leak
    - Commonly happens when our installer updates. Currently being investigated.
        - Workaround: Exit out of the FlyByWire Installer. Open `Task Manager` and find FlyByWire Installer. End Task.
* Wipers don't function correctly on FSX Liveries

#### MSFS WU4 Known Issues

* Instruments may break if you let the pre-flight cinematic with the "FLY" button play all the way through
* Most addons which use standalone modules like YourControls, MobiFlight or FSUIPC will cause CTDs

***

### ^^Common Issues^^

* AP not following the flight plan (leaking input values affect, but doesn't disconnect the AP)
    - Workaround: Set dead-zones for your input device higher
        - Go to your settings
        - Controls and select your yoke/joystick/controller.
            - After that click the sensitivity button on the top left which should take you to the menu where you can adjust your deadzones. Start with 20% deadzone, if the problem persists keep increasing it. If it's fine with 20% you can then slowly decrease it too.

* Autopilot goes direct to RWY on APP (same with the default A320)
    - Workaround: Use DIR to a waypoint or selected heading

* CTD when pressing **FLY** on world menu
    - Check your content manager for missing packages

* Plane is invisible
    - Check your content manager for missing packages
    - Livery/Mod Conflict

* Rudder keybindings not working
    * You have to set your keybinding to rudder axis right and left

* Wing dips on landing (due to bad transition to direct law in flare, same with the default A320)
    * Workaround use minimal aileron input on landing

* Black screens / unable to start
    * Conflict with another mod/livery or incorrect installation of the A32NX mod
    * Use our [installer](https://api.flybywiresim.com/installer)

* Upper ECAM displays wrong THR levers position / N1 rating

* ASOBO *Aviator/Beta Club* A320 liveries are incompatible with the A32NX mod

***

### ^^Fixed Issues^^

* Installer v1.1.1 potential issues: *(fixed)*
    - Getting default version or black screens after using installer on v1.1.0
        - Workaround: Delete the `flybywire-aircraft-a320-neo folder`, then install it again.
    - Installer not showing your existing installation:
        - This is due to the new modular system which requires a new full installation.
        - Workaround: Install the mod again via the installer.

* VOR/ADF indicators not showing on the ND *(fixed)*
  
* Unable to climb / flaps 1 issue *(fixed)*
  
* EFB not clickable *(fixed in development version)*
  
* V/S mode stuck at 1500 fpm or inoperable *(fixed)*
    
* ILS not showing on approach / does not auto populate in RADNAV *(fixed)*
    - Workarounds (may apply to 3rd party sceneries):
        - Manually input your ILS frequency into RADNAV. Type in the frequency found on your chart and press the key next to LS/Freq. Sample: 111.30

* Left PFD lagging / freezing *(fixed)*
    - The team is aware of the issue and is working hard to resolve it, potential fixes are being tested

* PFD artificial horizon freezes *(fixed)*
    - Workaround:
        - Turn off PFD, wait >10 seconds and turn PFD back on.
    
---

If you are here from our social media please visit our discord for support.

[:fontawesome-brands-discord:{: .discord } - **Discord Link**](https://discord.gg/flybywire)