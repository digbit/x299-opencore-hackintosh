# Hardware

- CPU                 i9-9980XE

- Memory              8x16G  G.Skill

- Motherboard         ASUS Prime X299-Deluxe II

- Graphics card       Sapphire x5700xt

- m.2                 Samsung 970 evo / 970 pro / HS-SSD-C2000Pro

# How to use

- update config.plist

using "OpenCore Configurator" generate SystemSerialNumber / SystemUUID

- update X299SATA.kext

remapping your usb ports if necessary

# Compatible with Monterey, Ventura and Sonoma

The BIOS version is 3801.

Things does not work properly:

- Sleep/Wake

# Bios setting

* AI Tweaker
    * AI Overclock Tuner - XMP
    * CPU SVID Support - Enabled
* Advanced
    * CPU Configuration
        * MSR Lock Control - Disabled
    * CPU Power Management Configuration
        * Enhanced Intel SpeedStep Technology - Enabled
        * Turbo Mode - Enabled
        * Autonomous Core C-State - Enabled
        * Enhanced Halt State (C1E) - Enabled
        * CPU C6 Report - Enabled
        * Package C State - C6(non Retention) state
        * Intel(R) Speed Shift Technology - Enabled
        * MFC Mode Override - OS Native Support
    * System Agent (SA) Configuration
        * Intel VT for Directed I/O (VT-d) - Enabled
    * PCI Subsystem Settings
        * Above 4G Decoding - Enabled
        * Re-Size BAR Support - Auto
    * PCH Storage Configuration
        * SATA Mode Selection - AHCI
* Boot
    * CSM (Compatability Support Module)
        * Launch CSM - Disabled
* Secure Boot
    * OS Type / Other OS



