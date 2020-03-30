Version 1.1.1.8 Alpha 2 by Jockesoftware 2017
Made by Jocke155, owner at Mineworlds.eu
Thanks for all the help provided from Mineworlds Developers; Datdenkikniet and Oskar3123
Virustotal: https://www.virustotal.com/sv/file/303a58c035529a7c88db5370ba60774fae78c3bd3af79303254492ae12235137/analysis/1483907443/
Using the YamlDotNet Library, made by Antoine Aubry http://aaubry.net/pages/yamldotnet.html
Software not Signed, therefor Windows SmartScreen might appear.

-----------------------------------------------------------------------------------------
How to use MythicCreator:

Creating a Mob

1. Click "Create" to Create a new mob.
2. Edit the values you want to edit, leave empty if you don't want a certain value.

In the options editor, doubleclick an item to remove it from the optionslist.
Select an item in the list to edit it's value, and click "Add option" to either insert, or to Add the option.

Editing a Mob

1. Click "Edit" and Open a mob that you already have saved.
2. Edit the values you want to edit, leave empty if you don't want a certain value.

In the options editor, doubleclick an item to remove it from the optionslist.
Select an item in the list to edit it's value, and click "Add option"

Exporting a Mob

You can export the saved Mob to your clipboard, or to an existing Mob file.
A Mob File with multiple Mobs cannot be imported/edited.

Need help?

Click the lables above the Options/Values, and a Message box with information about
that option will appear.


-----------------------------------------------------------------------------------------
ChangeLog:

V 1.1.1.8

* Updated YAML Library and other dependencies
* Added a few new targeters in the skill section
* Added new new mob option "PassthroughDamage"


* Fixed "Search for Option" that could get stuck
* Improved Options Editor UI for easier usage, by adding Tabs.
* Code and Resource-cleanup, preparing for version 1.2.0.0
* Added missing help-text for HealthBars

* Added PARROT Mob type
* Added ILLUSIONER Mob type
* Added @Passenger targeter

* Added Support for HealthBars
* The Mob options editor is a bit smaller, making it easier to use on smaller screens.
* Buttons in the Mob skill line editor is now resized

* Fixed some issues where single quotes were not loaded or added.

* Skill Editor now added to Mob options Editor. (Testing in progress)
* Value and Skill editor groups are now disabled until you select something to edit

* Removed "Save all changes", it will now ask you on exit instead
* Fixed some issues where saving wasn't possible
* Added a new button for saving the list you are editing
* Changed how saving works, and how users get notified on unsaved changes
* Fixed Saving error
* All Options sections got information about them if you click the "Select option section to edit:" label.
* Better error handling
* Improved Editor design
* Fixed a bug where saving didn't work correctly
* New border and font for the list in the Options editor
* Fixed an issue where the Options Editor couldn't open
* Fixed a bug where the editor thought you did changes after opening a Mob file
* Exporting Mobs to an existing YML now works, but you can't import a multiple mob yml yet.
* Fixed a bug where the editor could be opened even thought it was already opened
* Removed unused code and variables
* Fixed a bug when creating a new mob
* Removed "Save As -> .yml" in menu, 
   Replaced with "Save File" that saves the file you are currently editing or creating.
* Removed Raw Editor, Might be added again in later, if needed.
* Editor now longer asks the user to save the YML if creation is canceled

* Fixed Serious bug with AIGoalSelectors and AITargetSelectors
* Added New Mob Option: Interactable
* Added new 1.11 Mob Types
* Fixed an issue where Mount doesn't save correctly
* Save Mobs to Clipboard (Buggy)
* Load Mobs from Clipboard (Buggy)
* New functions in the code
* You can now longer enter incorrect values in the basic value textboxes
* Fixed a bug in Raw editor, that always seemed to think you did changes after opening it
* Now warns user if they haven't saved changes to options, or haven't saved on exit
* Added missing pictures to the icons
* Changed the way icons are displayed for better quality
* Added Search textbox for selector dropbox
* Added "Pose" to editor
* Replaced link labels with buttons for opening the editor.
* Added Icons for Type selection.
* Removed seperate Options editor. You now edit all options in the same editor.
* Fixed serious issue that caused the values to not load at all
* Fixed an issue where the RawEditor crash on exit after creating a new mob
* Mow now requires Internal Name to save
* Mob now saves correctly when leaving a few values empty
* RawEditor now works after creating a new mob
* KillMessages now loads with ' ', and loads correctly when clicked
* DamageModifiers now loads correctly when clicked
* "Load edited" now implemented. Save Current, and then "Load edited" to get the list you saved.
* Drops and DropsPerLevel now load the values when you click an item in the ListBox.
* Editors now starts up on the center of the screen
* Fixed an issue when the editor starts up behind the Menu Form
* Fixed an issue that made the Valuetextbox in the universal editor loaded the whole
  Listbox item, instead of removing the "  - "
* Fixed inccorect values in the TestBoss.yml
* Fixed an issue were LeveModifiers loaded and saved as a "List"
* All Mob specific options are now in the Options editor
* No longer requires the external YamlDotNet.dll
* Changed SwordIcon
* Code-cleanup, Resized menu
* Fixed an issue where killmessages didn't have ' ' when saved [Still Broken]
* Bug-testing in progress in this version.
* Added saving method
* Added universal editor
* Removed an unused image from the Resources
* Added Help for all Global options, click the label for info about the selected option.
* Added a Green or Red color on the Options Label. Green = Global Option
* Added a InfoBox function for display of help when clicking the labels.
* Fixed Linebreaks that appears in files
* Removed .mcf extension, only .YML supported now
* Creation and editing now works, only with the supported values
* Fixed issue with data being sent from 2 forms

** Known Issues ** (Read before Using) **

* None at the moment.


-----------------------------------------------------------------------------------------

MAKE BACKUPS OF YOUR FILES IF YOU TRY THIS ALPHA VERSION!

------------------------------------------------------------------------------------------
