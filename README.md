---------------------------------------

Kobold Camp ver 1.61
For DF 40.10
Most recent update: 08/28/2014

-----------TABLE OF CONTENTS----------- 

If more convenient, CTRL-F the code in parenthesis to find the respective section.

0. Changing the undiggable stone to diggable.
1. Description  (0010)
2. File Changes (0020)
3. Changelog (0030)
4. Guide to custom buildings and reactions (0040)
5. Contact (0050)
6. Credits (0060)
7. Old Kobold Camp Readme from Pathos' version. (0070)


-----------0. Changing kobold graphics pack     (0000)-----------

MINING-
By default, kobolds cannot mine through just about any stone. If you would prefer kobolds to be able to mine, then either go to \raw\objects and replace material_template_default and  inorganic_stone_mineral.txt with their vanilla files, OR to do it manually, remove the [UNDIGGABLE] tag that lies around the bottom of the [MATERIAL_TEMPLATE:STONE_TEMPLATE] section of material_template_default.txt.


-----------1A. Description         (0010)-----------

Kobold Camp is a mod so classic it almost feels like vanilla Dwarf Fortress to many. For those of you who have never experienced it, Kobold Camp has you buliding a "fortress" with Kobolds instead of Dwarves, little use of stone and metal, Human, Elf, and Dwarf sieges, and a higher probablilty of !FUN! per minute than a Dwarven aqueduct project.


-----------2. File Changes         (0020)-----------


-----------ADDITIONAL SEPERATE FILES-----------

If you find that your mod has been used and you dislike this, send me a note and I'll remove it.

	building_kobold.txt
	item_ammo_kobold.txt
	item_armor_kobold.txt
	item_tool_kobold.txt
	item_toy_kobold.txt
	item_trapcomp_kobold.txt
	item_weapon_kobold.txt
	material_template_kobold.txt
	reaction_kobold.txt
	entity_itemthief.txt
	
	

	
-----------EDITED VANILLA FILES-----------

The following vanilla files have been changed
(to be updated shortly]


-----------3. Changelog        (0030)-----------

---ver 1.61---
-Changed the readme to be the format that git/github like (README.md) and cleaned up the readme also
-added some leather armor reactions, moved the fur bed reaction, to Bushcraft Workshop
-added bone cages and statues to Bushcraft workshop
-continuing to tweak on entity_itemthief (aka Kobold Trading partners) [still needs work and testing]
-added the ability to extract blood and brew it into alcohol (idea from Masterwork DF by Meph)
-made weapon stones more effective (thanks, AJC!)
-made vermin edible and added wickerworking (thanks to milo christiansen, creator of Rubble)




---ver 1.6---
-Ported to 40.09
-Uploaded to Github to make mod development more community oriented
-Reworked mod to return Kobold life to a more primitive state, including:
	-Removed metal use
	-Reworked and simplified weapons significatnly
	-Removed the minecart analogue
	-Condensced and simplified workshops
	-Added the use of chert, obsidian, and quartzite back in
	-Disallowed many jobs (masonry, smithing, etc)
	-Made Kobolds [ITEM_THIEF] (trade wtih Goblins, sieges from Humans, Elves, Dwarves)
	-Gave Kobolds new trading partners (Troglodytes, Frogmen, and more!)



---ver 1.51---
-Armors added
-Changed native ore to appear in the soil layers and be diggable, while all other rock is undiggable.
-Weapons reworked
-Kobolds are now able to break down metals to make crude goods
-Wheelbarrows/minecarts are specific to kobolds at half the capacity

---ver 1.5---

-Long overdue port to 34.11
-Fixing/updating kobold graphics
-Errorlog fixing
-Various other typos and whatnot fine tuning
-Kobolds can now make shoes
-Wheelbarrows/minecarts are included

---ver 1.4---
- Ported to 34.01

---ver 1.3---

-No more mining of any stone, not even through copper/silver/gold. Gems and adamantium are mineable, but you would have to settle on top of a cave in order to get to such valuables. Kobold caravans carry valuables though, assumably through theft.
-Wood Stalk farming is fixed. Seeds are returned, and even work.
-Default graphics are now set to Haggle's kobolds.
-Training reactions have been fixed.
-All jobs are enabled, and all traps and mechanics are employed.
-Reactions and buildings have been cut back/changed. Many were redundant either already, or made redundant by the inclusion of all jobs.
-Altar reactions removed until working properly.

---ver 1.253---
- Added tags for tools for clay/bee stuff that dwarves already had.

---ver 1.252---
- Aztec weaponry REACTION names changed to more conventional terms.

---ver 1.251---
- Aztec weaponry names changed to more conventional terms.

---ver 1.25---
- Ported to DF version 31.25

---ver 1.19---
- Embark now should have wood stalk seeds.
- Graphics update (Now uses Ironhand)
- Sound is fixed
- Changed Kobold's lifespan, they now die between the ages of 10 to 20.
- Kobold's adulthood is reached faster, in 2 years from baby to adult. However, they don't reach full size until age 4.
- Soil no longer has has precious metals. As far as I can tell, even on the lowest setting it got ridiculous.

---ver 1.14---

-Implemented the Sawmill Mod, so growing wood is now possible through farms.
-Kobold entity tokens added to allow the wood_processer workshop and its reactions.
-Copper, Gold and Platinum's occurence in soil has been changed from VEIN to CLUSTER_SMALL. Silver has been added to this, also in small clusters.

---ver 1.13---

-Ported to 31.18
-Kobolds now settle in cities, this is primarily for kobold adventurer's sake. There are no forts or keeps that I've ever seen, so kobold civ's are basically a collection of hamlets and one town for shopping needs.
-Added METAL_PREF to kobold entity, to reflect the addition in the defaults.
-[BANDITRY:10][WILL_ACCEPT_TRIBUTE][VARIABLE_POSITIONS:ALL] also added to kobold's entity.
-Stone has been made more valuable. (Minimum set at 5 multiplier, embark cost is 15p per stone instead of 3 by default, now.)
-Copper/Silver/Gold veins in soil.

---ver 1.121---

-Fixed the processing wood reaction. No longer can kobolds turn stone into wood.
-Skill rate set at 80%

---ver 1.12---

-Ported to 31.17
-Added [UTTERANCES] tag back for kobolds, effectively removing language. Simply remove it if language is preferred.
-Added another custom workshop, Wood Processor. This changes wood into blocks for more efficient (and consistent) building material.


---ver 1.11---

-Ported to 31.16
-Removed the entire family tree of ARMORER, BLACKSMITH, WEAPONSMITH, FURNACE_OPERATOR and METALCRAFTER. Since armorer was already removed and DF removes the entire family if one (in this case armorer) skill is missing, this was done more for RAW cosmetics.
-There may have been changes made I've long since forgotten about made in inorganic_metal.txt. If so then not anymore, as the default has definitely remained this time.
-More cosmetics, lasher kobolds are no longer called 'slingbolds' as it is possible that a bold could use a whip, at least in adventurer mode.
-Changed the Chopper, Maquahuitl and its training variants' pommel attack from 1000 to 100 to match the corresponding weapons in the default weapon raws change from 1000 -> 100.
-World_Gen init file has been reverted to default, as apparently the need for double caves for kobolds hasn't been a problem in this versions testing.



---ver 1.1---

- Added various Aztec weaponry, though many previous weapons still remain (shovels and choppers are still used for utility, and throwing hammers and shell hammers are still in effect) See the readme section for aztec weaponry if the names confuse you.
- Training weapons are now able to be made.
- Ammo Workshop added, to make stone/metal based ammo. All other weaponry is still made in the Armory, with the exception of throwing gloves being in the Furrier.
- Kobold Language created - attempted to keep things similar to utterances, though patterns are more sporadic.

POST FINAL UNTIL 1.1
Ported to 31.13
	-Put back the .txt file used for Haggle's kobold graphics
Ported to 31.12
	-item_weapon_kobold primitive spear weapon values changed (reported to be uber, prior)
	-item_weapon.txt, item_trapcomp.txt, item_ammo.txt, forest entity reverted to 31.12 defaults.
Ported to 31.08
Ported to 31.05

	-Added littersize tag. It doesn't generate an error, but untested to whether or not it works.

---FINAL---

- Fixed the "body_rcp" that should be required at the top of body_rcp.txt.
- Most armor has the [BARRED] tag added, making properly-fitting armor possible in theory.
- Various edits, tweaks and typos.

---ver .92---

- Worldgen shows caves, now.
- Fixed a couple reactions.
- Given stone is easier to get (chooseable embark item), wood mechanism has been upped considerably so it's a viable option in the face of stone.
- Added masonry.
- Removed [SKULKING] entity token and added in various animal usage tokens and currency, so as a result,
- Trading is finally IN.

---ver 0.9---

- Editted the tanned fur template. If I know a thing about the temperature scale, that stuff was bursting into flame about around negative 1800 degrees celcius.
- Added in light fur to material_template_kobold, but implementing it for kobolds will wait. It must be done with hefty testing, lest things go awry.
- Shaman now tames exotic (essentially your dungeon master/religion/management combo now.)
- Finished necessaryish reactions. Stone/copper/adamantine weapons, copper/adamantine shields, valuable metal trinkets and the like. Armor is built too large to use, unfortunately.

---ver 0.84---

- Shovels and choppers can be selected on the embark menu, now.*
- Meat is cookable again.
- Changed a bit of the announcements so it doesn't pause when you try to dig through damp stone (but the designation is still canceled.)

*Doing this has changed more things than I had expected or hoped. Various metals and stones are available at embark, and with the recent addition of more available stones, fire-safe materials are effectively open. Reactions may be changed to reflect this in future versions.

---ver 0.82---

- Changed the throwing hammer firing weapon to throwing gloves, made in a furrier.
- Somehow my raw files got mixed up with the raws from 31.02. This has been remedied through what's listed in 31.03, so it shouldn't need to be re-compiled from scratch. I'll be careful porting the raws when 31.04 comes out.
- Made a few mineral deposits mineable. Copper, Silver, Gold, Cobaltite and, under the nil chance you find it, Adamantine. This did just open the road for a whole ton of reactions.*
- For example, throwing hammers can be made out of any stone you have, including the raw nuggets.*

*As kobolds will still not have smelting or metalsmithing or all of that, reactions will have wood requirements for smelting straight into the reaction product. Not charcoal or coal mind you, as kobolds don't use fire safe materials, so wood burning isn't an option.

---ver 0.81---

- Added a stoneworking building to build throwing hammers.
- Added throwing hammers

---ver 0.8---

- I added in Deon's healthcare mod. If your doctors got at all competent through experience, it would mean everyone's dead or dying.
- Coincidentally, added in large dagger to kobolds.
- Furthermore, due to the current military issues, and not wanting to add training weapons, I decided to add weapon training dummies. While these were made from scratch specifically for kobolds, the idea behind it is still Deon's.
- Added new hammer weapon made out of shell and its approprate reaction.
- Added reactions to critter workshop:
	- Use remains for ash
	- Use vermin for food and ash
- Upped mechanism success rate to 10%
- Removed accents from the language files

---ver 0.7---

- Integrated Arrkhal's weapon and material rebalance for better or Fun.
- Creating mechanisms now has a 6% success rate with wood now, so use your mechanisms wisely.
- Added a Scrimshawer Shop, for various bone reactions.
- Removed mechanism shop; kobolds make mechanisms in the trap shop now along with all of their trap components, bringing me to
- Added some kobold specific trap components, and tweaked existing ones. The new weapon raws are rather non-explanatory to how they work in detail, so admittedly the current weapon traps may or may not be balanced.
- Missing underscore in [ITEM_THIEF], to make the most unchanging entry in the changelog yet, what with the lack of trading.
- The error_log.txt is now error free.
- Graphics rehaul, now uses phoebus' graphics pack. The tileset, however, has been changed to MaydayMIX. The kobold graphics are now the original grey-furred kobolds. (directions to change are at the top of the readme)

---ver 0.2---

- For DF 31.03
- Added management task to Shaman position
- Changed Shaman a bit (less like druid more like manager, but still holds religion) and shaman in training was removed, in return, shaman now shows up on the nobles screen
- Kobolds are no longer godless heathens (added pantheon and a few religion spheres that just get spat back out at the errorlog)
- Custom buildings: Critter Kennels**, Trap Shops, and Mechanic Shop
- Able to create wooden mechanisms*
- Mechanism job family added*
- Kobolds use their own kinds of trap components. At the moment, only darts and spikes can be made.
- Kobolds aren't so distrustful now (removed the personality modifier that limited trustfulness from 0 to 50)
- Strength, Toughness, Agility and Recuperation have been lowered considerably overall (esp toughness), although the cap is increased for some genetically luckier kobolds to stand out
- To balance the above note, undisputably returning the game to the EXACT same difficulty, Disease Resistance and Empathy have been increased, and they can now make (bad) music
- But seriously, kobolds now gain attribute rates faster than their sentient counterparts, as well as the percent cap to which they can increase to has been increased. In theory though, they're generally weaker. Maybe.***
- Strength in numbers; kobolds now only take 2 years to go from birth to adulthood, though 4 years to reach their full height
- Misc tweaks and typos I wouldn't bore an elf with


*This uses the custom mechanic shop (hotkey b-w-T).
Originally I planned on wooden mechanisms requiring the carpentry skill. The ability to make mechanisms worked alright, however, building traps/levers/etc still required the mechanism skill. I don't think there's a way around this.
Therefore, I opted to include mechanisms, the downside is that it must also include the related jobs, siege engineer and (pump) operator. However, given that the kobold entity still cannot make ballistae ammo nor harvest stone for catapults, nor create enormous corkscrews, these 3 skills are effectively worthless.
As a result, even though the whole family is added, one can still look at it as only having mechanics.
A few kobolds simply like to call themselves siege engineers to be cool.

**Except it's completely useless at the moment, but it's there when I get to critter reactions.

***The flat values of str/tough/agi are tested and work as they should, but the growth rates/caps are a tad hard to test (in quick order, anyway), so it's on good faith that the tags work. Given that [SLOW_LEARNER] seems to make no difference, I'm dubious, but will give it a go nonetheless.


---ver 0.1---

- For DF 31.02
- Graphics included (uses Haggle's kobold sprites)
- Kobold's are now carnivores, and can consume bones.
- More jobs opened up, mostly due to job-families being shut down if a single job was missing. (i.e., if bow-making was disabled, carpentry and wood cutting would be inaccessable)
- Angler mod removed (incompatable with DF31.0x, this created many 'nothing's at embark screen)
- Kobold growth rate reduced from child to adult in 4 years.
- Added pets and booze at the embark screen.
- Replaced [BABYSNATCHER] with [ITEMTHIEF]. No one'll hold it against you if you remove this from entity_default.
- All [IS_STONE] entries are now unmineable with exception to obsidian and chert.
- Doubled the amount of caves in world gen, to help fulfill the playable civ requirement.


----4. Guide to the custom buildings and reactions.      (0040)----

Training Grounds - Used to train weapon skills.

Basketry - used to create mundange furniture items (bins, chests, chairs, cabinets, tables) from Wicker which is harvested from a variety of farmable crops (ropereed, longland grass, pig tails, cave wheat)

Bushcraft Workshop - various wood crafts/items, bone crafts (including weapons), and other primitive tools/items

Trap Shop - Used to make wooden mechanisms (if you've got stone, then the mechanic's shop makes stone mechanisms) and kobold specific trap comps.


-----------5. Contact         (0050)-----------

If you want to be a part of this mod's development, see either the forum thread or the github (or both):
http://www.bay12forums.com/smf/index.php?topic=142853.0
https://github.com/HelloLion/KoboldCamp


-----------6. Credits         (0060)-----------

Lagotrope - Creator of KC2012
Deon - For the healthcare training buildings.
Pathos - Creator of KC2010.
Lairian - Providing medical kobold sprites, and putting the kobold sheet/text files together.
Haggle - For kobold graphics and raw data pertaining to in-game description of kobolds proper.
Gobbo - Original creator of Kobold Camp and main kobold graphics.
Mephansteras - Creator of DF word generator, used for making kobold's languages.
VeldyEldy - For his Sawdust mod
BunnyMind - For help getting migrating the sawdust mod to KC
thatkid - Altar reactions and ideas
Hugo_The_Dwarf - Various reactions and all sorts of things
And the no small amount of assistance given by those at #dfmodding and the KC forum

If you're not on this list and you should be, just let me know.




-----------7. Old Kobold Camp Readme from Pathos' version.          (0070)-----------

Kobold Camp 2010
-----------------------
Problems with world gen:
If you keep getting the game stopping when you get to the civ placing stage, make more caves in world gen (LAGO'S NOTE: already doubled the caves in worldgen so this shouldn't be a problem, but still worth keeping in mind) - as that's where kobbs originally start out.
Problems with weapons:
You can't select weapons if they're not on the original embark screen. I'd suggest that you don't remove those weapons, either.
-----------------------
Contributors / Special Thanks:
Kaelem Gaen - Contributed land owning and military nobles.
Lofn - Made fur and fur beds for the new version! Good stuff! Also made the idea for silver / lead poisoning due to mining.
Deon - Allowed me to steal silver / lead poisoning from his mod. Download his amazing mods here: http://www.bay12games.com/forum/index.php?topic=52988.0
Chariot - Allowed me to integrate his amazing mods into this one. Download them here: http://df.magmawiki.com/index.php/User:Chariot
Warlord255 - Provided the numbers on how to make weapon-able stones.
