> [NOTE]
> Anyone willing to help with fixing bugs and updating this plugin is more than welcome to reach out

<div align="center">
<h1>Action Progress Plugin</h1>

Displays an indicator showing how much progress you've made on your current action, and how long until it will finish.

<img alt="img.png" src="demo.gif" style="align: center;"/>
</div>

## Supported features
- Cooking
	- Cutting fruits
	- Mixing pastry & wine
	- Topping pizza
- Smithing
	- Cannonballs
	- Smelting
	- Smithing comming soon
- Crafting
	- Battlestaves
	- Casting gold & silver
	- Molten glass
	- Cutting gems
	- Glassblowing
	- Leather-wroking
	- Crafting leather shields
	- Stringing jewellery
	- Weaving
- Fletching
	- Arrows & bolts
	- Creating bows, crossbows & shields
- Herblore
	- Herb cleaning
	- Mixing potions
	- Mixing tar
- Magic
	- Charge orb
	- Creating tablets
	- Enchant bolt/jewellery
	- Creating planks
- Tempoross
- Miscellaneous
	- Collecting sand
	- Grinding items

## Changes
- `1.11`
	- Add support for ultracompost
	- Fix javelin timing
	- Fix plank make detection
- `1.10`
	- Fix progress bar not showing when smithing
- `1.09`
	- Add support for javelins
	- Add support to show ticks instead of seconds
	- Add support for make-x darts
- `1.08`
	- Add vertical mode when resizing
	- Add support for Plank make (Needs to be tested by someone with the proper magic level)
- `1.07`
	- Add support for fletching/crafting shields.
	- Add support for fletching crossbows.
	- Fixed issue preventing the progress bar from being displayed when mixing stamina & antivenoms.
	- Fixed issue preventing the progress bar from being displayed when cutting gems.
	- Fixed issue preventing enchanting from displaying progress bar.
- `1.06`
	- Add support for weaving.
	- Ability to resize overlay.
	- Detect when chemistry amulet breaks.
- `1.05`
	- Add double ammo mould support.
	- Add settings for customizable colors for progress bar.
	- Updated for RuneLite version 1.9.13.3.
- `1.04`
    - Added interruption when hit.
    - Added interruption when pest control portals drop.
  	- Updated for RuneLite version 1.8.30.
- `1.03.1`
	- Fixed various issues with 1.03.
	- IDQuery API moved to testing and replaced with constant ID arrays.
		- This API had unforeseen issues due to database classes not existing in release environments.
		- Tests have been put in place to ensure that these constants are kept up-to-date.
	- Fixed TemporossDetector.
	- Fixed ItemClickDetector.
- `1.03`
	- Rewritten a lot of core components.
	- Many actions added.
	- Many ingredient checks added, giving more accurate estimations of how many actions can be performed.
	- Many customizations added, all actions can be enabled or disabled.
	- Option to show skill icons instead of product icons (For example, Herblore icon instead of the potion being made).
- `1.02`
	- Track Tempoross activities (Cooking and filling crates).
	- Interrupt action when wearing or removing equipment.
- `1.01`
	- Respects the user-defined infobox background colour.
	- The "Ignore single action" property was mislabeled, it was inverted.
