//--------------------------------------------------------------------------------------------------------------------------------------------------------------//
// AUSSIEDROID'S ACKNOWLEDGEMENTS //																//
//--------------------------------------------------------------------------------------------------------------------------------------------------------------//
// Standing on the Shoulders of Giants! Creation of this TARGET Script would not have been possible without amazing ED Scripts I found online created by:	//
// Alexandr Zhevedenko, Michael Lehman (WraithMG11235), Darkcyde0 & Thomas Duployez (CMDR Touille).	You All Rock! Thank you!				//
// 																				//
//--------------------------------------------------------------------------------------------------------------------------------------------------------------//
// VERSION HISTORY //																		//	
//--------------------------------------------------------------------------------------------------------------------------------------------------------------//
// Version 2.4.0																		//
// Released September, 2016	(Updated Jun 17)														//	
// =============================================================================================================================================================//
// v2.4 - NEW: Auto Timer for Repeater Fire, Fast Menu Switch Macro, VR/TIR Headlook Swap U.Pref SWAP: S.Running/R.Correction Toggles. IMPROVED: Error Handling.//
// v2.3.3-COMBINED FAOFF+ALT FLT (SpeedBrake w/ Pinky Mod) NEW: Escape Macro now has Gear/Scoop Check + new timings. FIX: Chat Macros when Comms Panel is Open.	//
// v2.3.2-SWAPPED: Repeater Fire & Combo Fire Modifier buttons. ADD: CruiseOnThrottle check for China Hat, removes FSD as req. FIX: IDLEMaster Function error.  //
// v2.3.1-FIXED: 75% Trim T.Preset, + General Comments Cleanup NEW: Macros 2-Tier PIPs (Hold), Swap Joy/Throt Preset Toggles ADD: Chat Macro print layout map.	//
// v2.3 - COMMANDERS UPDATE: ADD New Multicrew, HoloME & Camera Suite Keybinds. NEW: Text Chat Macros (PIP Hatswitch+Pinky Trigger). NEW: ShowGameStats Macro.	//
// v2.3 - NEW: SC 100% Throttle/Repeater Fire/Signal Light Macros. ADD: 1&2-Tier PIP Alts,User Prefs,MFDs. MOVED: Hardpoints to T.Arm. FIXED: SRV Boost on Slew.//
// v2.2.7-NEW: Heatsink+SilentRunning Mod! FIXED: Dead Throttle on Run/Looping running in Script Editor/Improved FPS/Bandwidth Toggle/Galaxy Map chat conflict. //
// v2.2.6-Changed SRV Digital Steering Hat Switch, Swapped Weapon Fire Group. ADD Auto-Dock Short/Long press+Pinky. No Shadowplay ref. ADD Fighter Orders.	//
// v2.2.5-ADD: Charge ECM button & Fixed Incorrect ED Bindings file in download.										//
// v2.2.4-FIXED: Changed Combo Fire Modifier from Pinky to CMS Hat Switch (avoid conflict). Improved PIP timings/refined layout. Removed SRV Handbrake conflict.//
// v2.2 - GUARDIANS UPDATE: ADD Fighters Hotkeys to Trim Hat, Mapped Weapon/Engine Color change. Improved IDLE saftey features. NEW Macros. Public Release! 	//
// v2.1 - ADD External Keymappings for TrackIR, VoiceAttack & ShadowPlay. SWAP Landing Gear & Silent Running. Changed some delay times.				//
// v2.0 - Full script cleanup & formatting update. ADD alt. Macros for PIPs & Curves to test. ADD Reference table for DX Mappings & USB Key Definitions.	//
// v1.8 - ADD SetThrottle function & Handbrake to Throttle IDLE lock. Ship Lights now dim Throttle LED backlight :) Steam added & Hidden FPS/Ping keys mapped.	//
// v1.6 - Improved Toggle switch usage. ADD LED output & expanded script print output in Script Editor.								//
// v1.3 - ADD Auto-dock, PIPs Macros & also Joystick & Throttle Curve presets. Plus Subsystem Prev Jump to Powerplant shortcut when holding Prev Subsystem.	//
// v1.0 - ADD All Standard KeyMaps, Default Axis settings & Core script structure/defaults. ADD Trigger Combo code. Debug testing.				//	// =============================================================================================================================================================//
// Created by Aussiedroid (http://steamcommunity.com/id/aussiedroid)												//
// Full Guide Available here (http://steamcommunity.com/sharedfiles/filedetails/?id=769637037)									//
// Frontier Forums Discussion Thread here (https://forums.frontier.co.uk/showthread.php/293027-Aussiedroid-s-Enhanced-Thrustmaster-Warthog-Script)		//
//																				//
// Need help understanding this script?																//
// Target Script Editor Manual URL: http://ts.thrustmaster.com/download/accessories/pc/hotas/software/TARGET/TARGET_Script_Editor_Basics_v1.5_ENG.pdf		//
// 																				//
//							** RUNNING SCRIPT IN TARGET GUI IS RECOMMENDED **							//
//--------------------------------------------------------------------------------------------------------------------------------------------------------------//

Upgrading from a previous version?

Simply copy the new files to the appropriate locations below. Each version is numbered to ensure you don't override older settings.


Installation:
=============
Extract the zip file pack.

The Warthog Script can be run from any location. All files need to be in the same folder though. 

Open TARGET GUI & Run (Can also be run from TARGET Script Editor - if editing)

Most commands can be tested prior to starting the game using the Event Tester & Device Analyzer.

Copy the Elite Dangerous Profile to:
C:\Users\<User>\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings

Copy the TrackIR Profile to:
(64bit). C:\Program Files (x86)\NaturalPoint\TrackIR5\Profiles
(32bit). C:\Program Files\NaturalPoint\TrackIR5\Profiles

Note: If the profile does not show up in TrackIR after copying to the above location (and restart TrackIR software didnt help), try copying the profile to:

C:\Users\<User>\AppData\Roaming\NaturalPoint\TrackIR 5\Profiles

Set the hotkeys in TrackIR; Pause Key to PAUSE, and Center to END.

Also set NVidia Shadowplay Capture Last 20mins hotkey to ALT+F11 (as required).

Map any other 3rd Party Keys such as Voice Comms (as required).

Always make sure the script is running as well as any other 3rd party tools prior to starting Elite Dangerous.


"I am a leaf on the wind!"