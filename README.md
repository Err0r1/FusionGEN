Compatibility:

Default_Armory_v2 - Should support all the major emulators. Needs testing.

Tested emulators:

- CATA without item_template
- TrinityCore Legion


Installation:

 1. Extract the contents of the archive usually on the desktop.

 2. Copy the contents of the folder Content into the root folder of your copy of FusionGEN, merge and replace all.

 3. You must disable the FusionGen tooltip if you dont have item_template in you world database in order to the WoWHead tooltip to work properly.

	You can find it in the config/fusion.php
	--------------------------------------------------------------------------
	 Use FusionCMS tooltip system instead of WoWHead tooltips
	--------------------------------------------------------------------------
	
	 Put to false if you mainly have "blizzlike" items.

	$config['use_fcms_tooltip'] = false;

 5. Clear your template cache.
 
 6. Clear your browsers cache.

 7. You are done.

Changelog:

Default_Armory_v2

- Fetching all of the images from wowhead.
- Fetching tooltip from wowhead.
- Fetching item data from wowhead.
- Disabled fetching item_template for the items only if the emulator dosnt support item_template.
- Enabled caching for the mayor part.