The Heirs to Aquitania
A total conversion mod by Savs
Based on the HtA megacampaign

Features a new world with nearly 800 years of different history (mostly as determined by the computer in CK2 and EU3)
Development has been in fits and spurts since June 2014. The mod is based on /gsg/Vickymod v1.06, which was popular at that time. It is not based on PDM, nor on HPM/HFM.
If you want to contact me, find me on reddit as /u/Savolainen5 or on the Paradox forums as Savolainen5

Also check out http://www.reddit.com/r/savs, where history and other stuff are posted. However, please direct discussion about the mod to the thread as much as possible, in keeping with Paradox rules.
Forum thread for the mod: https://forum.paradoxplaza.com/forum/index.php?threads/the-heirs-to-aquit%C3%A0nia-altervicky-mod.895808/
Vic 2 Modding Discord Server: https://discord.gg/EbY7qaA (Hosts discussion and updates for a lot of mods)
HtA Discord server: https://discord.gg/beteEPF (not in active use, use the above Vic 2 Modding server instead)

There's an event numbers list at the bottom of this file

Feel free to use anything from this mod without asking me. Please do attribute it/credit me, though.

Thanks to:

- ChortlingGnome, who contributed A LOT (like seriously a lot) for Hispania, China, North and South Ameriga and other things
- /u/capitanloco6 / MajorMajor, who wrote events and decisions regarding French ambitions in the Holy Land and the dismantling of Persia, as well as giving some flags and fixing Catalan military/party names
- /u/Flapjack731 for ideas and content contribution
- /u/firenine09, /u/1tobedoneX, and /u/Sommern, for being a sounding board and giving many good ideas and flags
- /u/_Rosseau_, for the new Norway flags. Incorporated with permission
- /u/Rangerage, who did a lot of POP rebalancing in BYZ/ARM based off of my EU3 save
- Rylock and contributors to the excellent NNM, off of which so many mods are based
- Developers of /gsg/Vickymod (Hisuibro, Finnbro), on which my mod is mostly based - v1.06 (itself based on NNM) - Its changelog is included among the files here
- Developers of and contributors to the Improbable Nations Mod, Community Made Countries mod, ParadoxPlaza Mod, the Symbols Flagpack (Chandlerw1) for flags and code for decisions and events
- Attalus and other developers of Divergences of Darkness for ideas, code, flags
- Naselus and other PDM folks, from whose mod I took some decisions, events, ideas, and inspiration
- arkhometha for his Historical Project Mod, from which I have taken many pictures, ideas, a good bit of country information, and some events and decisions
- EGaffney for his Rectangular Flag Frames Mod
- RenatoDS for his RDS mapping project, which creates a more detailed world map (for terrain and rivers)
- simsulla for his help in sorting out adding canals and for (passively) showing me the crucial last step for adding new provinces - making the default.map file point to your mod's directory. See my copy for more details
	- Also for passively showing me how to make music in a mod work
- Hammonia for his work on the beautiful HFMmm map, which I used in 0.36 to update the map
- /u/rascalnag / Squidward Tortellini for significant support in making the map look more like what I want
- Shatterfury, Lukesky, Skyhascheese, Necro991, Rioting Soul, Spudgun, and Athemos for their ideas, flags, sounding board-ness, testing, and feedback 
- BobSagini for MANY flags, ideas, and hooking me up with Vic1 music
- dreamonceh for pointing out that you can set some AI behaviour in OOBs
- Ahearne for suggestions, improvements, and help with Eire
- Crushric for Roman POP rework and other contributions and ideas
- Over421 for Greek-language parties and flags
- Discux for parties for lots of New World countries
- Rennes for showing me how $ORDER$ works in war localization
- Jorde for testing help
- zake for pointing out many bugs and things to improve
- Lastly, the Vic2 Modding server on Discord

NB for the changelog - Anything with lots of # or * after it is something Savs is still working on or hasn't gotten fully/correctly implemented yet

**CHANGELOG**

Verison 0.37 - Poland and Italy

Major
- Added decisions and events for Poland, the Padan Union and Naples
	- Added a new tag - Meridion (MER) - as an intermediate step between Naples and Italy
- Added a new government type, the Provisional Government (which comes in yes_election and no_election forms according to whether elections are allowed, obviously) which is used for PDN initially and can be used for other countries in the future
	- Also added events to switch between them based on the vote franchise
- Added an Install Monarchy CB for great/secondary powers against democracies
- Pan-nationalist rebels will not rise if their cultural union doesn't exist - THIS MAY NEED TO BE ADJUSTED SO THAT ONLY GERMAN ONES WON'T RISE (because I'm OK with French ones, for example)
- Added an event for SML to lose control of its Black Sea provinces if it's at peace and neither UKR nor DON are its vassals/owned by it (the check is based on four major provinces in different states close to the land)
- Added a decision for RUS to break the truce and just go capture the city of Smolensk if they have basically no military. It costs more infamy, but has the same end result as the other two ways to end the conflict
- Improvements to Aenglisc-Albannach (and also AEN-IRE) war interactions, how Alba's colonies are handed out (still work to be done here to make it more dynamic) and the AI's ability to conclude the wars
- Decision for AI countries not to interfere in the Russian wars if both RUS and SML are AI. They will take the decision to leave the war if they are called in and accept it.
- Incorporated a new system for releasing vassals, with thanks to the Vic2 Modding server on Discord
- A lot of stuff by ChortlingGnome in North and South Ameriga:
	- Shawnee internal conflict and defensive wars against post-colonial countries
	- Decisions for the aforementioned countries to get cores on native land in NA
	- Vestland has the possibility to get a union with New Holland
	- WIP stuff with slave trade for MRG (will get finished in 0.52)
	- Gidan gets some interaction with MRG over the slave trade and some expansion decisions into the Caribbean and south to the Jordrasc/Amazon river
	- Mexika begins as a confederation with several native countries under it (will work on POPs in the region in 0.54 unless someone beats me to it)
	- Mexika civil war (or averting it), possible union with CLF
	- Mexika interaction with Yucatla and pushing further south
	- Form Mellomamerika as a puppet if you're a New World GP

Minor
- Severely nerfed the OP Gold Rush modifier - now gives an immigrant attract of only 100% instead of ten times that. This needs testing to see if it should be buffed up a bit. Maybe 300%
- Reorganized African events files
- Some more starting generals - thanks to MajorMajor
- Many new flags - thanks to Athemos and Periares
- Netherlands' Integrate Wallonia decision now gives a core, too
- French decisions to accept Wallonians, Picards and Bretons will now cost 5% of their prestige instead of a piddly 1 or 2
- Forming the Scylfiga Woning now gives 30 prestige instead of 120% of what you had.
- Added the Prusai culture, Baltic-speaking remnants of the Old Prussians, to the Polish-Lithuanian border region, along with a country for it - Prusova (tag PRS)
- Added a tag for Istria (tag IST), a Cisalpine-run confederation of the various cities in the state of Istria, plus some drama for the owner (probably AUS) of it.
- Added Moravia (tag MRV) as a country. It's mostly there to prevent Czechs from assimilating after the Treaty of Szekesfehervar
- Added (army) unit files from HFM
- Changed some country colours: CYR, EGY, MGH, LUZ, LTS, CHI
- Changed some culture colours: Guaraní, Lutzan
- Also added related decisions and events for dealing with its cores and what happens if it becomes independent
- Used native names for the Nahua culture, thanks to Komodo
- Copied over a lot of stuff about cultural tech from HPM, mostly so that the choice modifiers are more complex and so that there isn't so much colonial migration from tech (+0.5 per level before, now ´+0.05)
- Made it so Brunswick doesn't have a core on Emden, meaning that they should be able to do the decision chain before Germany forms
- Added events to remove cores of minors for BRA, BRN, BAV and GER
- GER gets a core on SWI when taking the Helvetian Patrimony decision
- Brabant should no longer sell its islands in Oceania/Volturnia if it has colonized beyond them in the region (continent)
- Native nations in the New World can no longer take the decision called New Life in the New World
- Made gold rush events not fire until 1870 for uncives
- When Smolensk annexes Russia, they now have a decision to reduce POP MIL and CON by 4 to reduce rebels
- Improvements to how DON joins RUS against SML
- Gave Mali one military reform (two seemed a bit OP, but it's there still if you want to readd it yourself!)
- Fixed 99% of remaining mismatches between various map files. The Paracel Islands will continue not to exist as land for gameplay purposes (though if you look closely you can see their shadow)
- Also made a lot rivers fit province borders better - lots more to do still
- Split Pau off from the Basque province of Miarritze, added two flavour events about Our Lady of Lourdes to the owner
- Made requirements for taking the Intervene in Persia decision more clear to the player
- Increased Make Puppet CB to 10 max badboy (previously 7)
- Demand concession CB can now target colonial states/provinces of uncivs
- Made CBs normally available between RUS and SML when railroading is off
- Both German Hegemony CBs should fire the Our Cores Returned event normally
- Added a special event-only Liberate Country CB to allow the liberation of Syria correctly
- Increased starting experience in national values, so now they are actually kind of useful. This change is also reflected in the demonstration modifiers which you can see in the decision
- Changed some 1840s revolutions modifiers (global_liberal_agitation, among others) about liberalism to be more in line with HPM, not that I think it'll make much of a difference for the militancy problem
- Made the National Assimilation event impossible to fire until 1870
- Improved the event which signals the end of BRB cores, made it specifically for NET (more, kind of), and added one for BRB
- Tweaked the event announcing the German Hegemony wars so that more countries can do it in case there are some really overzealous conquerors in MP
- Added decisions for an independent Greece to claim the rest of the state of Thessalonikos and (if jingoist) to claim Crete
- Added an info decision for the Roman Empire and made the implications of some events/decisions slightly clearer
- Greek party tweaks
- Study Room Meetings should disappear from all BOH-owned provinces after they defeat the revolution
- Added a decision for a resurgent Bohemia to lease Zadar again
- Added a decision (which the AI will never take) to return a leased Zadar to Croatia or Yugoslavia (the latter should only be seen if some other country creates YUG, not the Zadar owner, please report to Savs if this is not the case)
- Tweaked the Yugoslavia creation decision to take into account a leased Zadar - if you still have the province, you will give it to Zadar automatically.
- Arbenon (Albania) must now no longer be a vassal or must be vassal of the country in question in order to be absorbed into Yugoslavia (whether that country is a vassal or no)
- Bulgaria gets cores on the Black Sea coastal provinces it should have cores on when the Bulgarian Insurrection event fires
- Added an event to make Ardeal release Banat and Syrmia and lose cores on them if it does not own land connected to that area (as often happens)
- Added a decision to regain the abovementioned lands as cores of Ardeal
- Added and modified some of the NaturalDisaster events from vanilla
- Tried to fix the Stilhav Naval Base decision for HOY, wasn't very successful.
- Brought in the HND country file from HPM with some tweaks and also changed its colour to a kind of bright pink
- Removed GNG from files and all references to it
- Tweaked a few LRs
- Made uncolonized South Amerigan provinces have colonial = 2 in their files so that they will be colonial when annexed by CHL and ARG
- Tweaked a few RGOs in Aengland
- Pumped up some starting prestige for important European countries
- Many localizations tweaks and fixes
- Lots of new event and decision pictures
- Added some info decisions
- Added some debug decisions/events
- Copied some code from HPM for some LiberalRevolutions events
- There should be a small pull for POPs to migrate to countries which have a similar culture/language (Hispanians and Portuguese to Latin America, Scandinavians to Margaria and other such countries, etc.)
- Lots of other small stuff not worth mentioning
- Added a blank province map (current to 0.36.27) for whatever you might want to use it for
- Moved most unused event/decision pictures into separate folders (mostly for keeping better track of things)

Bugfixes
- Navarra has a liberal party for the entire game
- The Mare Occidentis Nostrum decision now works properly
- Intervening in Persia now no longer gives more infamy than expected
- Fixes to a number of OOBs
- The New Zadar Lease-related decision can no longer be repeated if the owner of Zadar rejects it
- Bugfixes to the Califiana annexation chain and associated events
- Yugoslavia can no longer invite itself to join itself
- The Encourage Textile Industry NF no longer crashes the game when hovered over
- Fixed some broken event numbers in HtA_Africa
- Added some checks to HIS-POR interaction to make sure the countries still exist
- Fixed Macau event loop for GXI
- A Great Russian-culture country which isn't RUS or SML cannot spam the Dominate Kazakhs decision anymore
- Non-railroaded Russia can now use the Russian Hegemony CB on Smolensk
- The Extend to Arabia decision is no longer spammable
- The event which gives Calgary oil no longer renames the province to Calgary
- Middag no longer magically becomes Taiwan
- Readded missing events for the Treaty of Kanagawa
- Fixed a bunch of errors with names in cultures
- Fixed Liberation of Syria during the Persian Oriental crisis by adding a new CB that makes it actually possible to liberate the country fully
- Further the Revolution in Daufinat decision for AQT no longer spammable
- Should now be possible to take the Mare Nostrum Occidentis decision if SCL and/or NPL/ITA cores have been removed
- Can no longer unite Italy from without if you've taken the Mare Nostrum Occidentis decision
- Made it so that the event to choose a captial fires for Nanyue (GXI) before the event to form CHI
- Requirements for Bohemian Zadar decision made more specific and doable
- Fixed The Obervahl sovereignty event
- Removed accepted cultures from Mexika, since they're supposed to be added by event later
- Kaapland is no longer a releasable vassal. I don't THINK this will be a problem.

----------------------------------------------------------------------------------------------------------
See the OldChangelogs file for previous version changelogs. You can also see them on the subreddit's wiki.

To do:
- See the "To Do" text file

**Event numbers** - both currently used and planned
50000&50002 - AQT
50003-50023 - FRA
50024-50049 - ITA and DAU (This is about the time I started actually being smart and allocating numbers beforehand. All are used up, must allocate more IDs. Added 50099 here)
50050-50098 - Germany and surroundings
50100-50149 - British Isles
50150-50199 - West Africa (Mali and the like)
50200-50249 - AQT and PRE
50250-50299 - Low Countries
50300-50349 - Iberia
50350-50399 - Russia/Smolensk
50400-50499 - Poland, Silesia, Bohemia (Most of these numbers are taken in Bohemia)
50500-50599 - Nordic Countries (NOR, SWE, DEN, ICL, FIN)
50600-50699 - Roman Empire and related
50700-50799 - Armenia events
50800-50849 - Miscellaneous events (some in HtA_famines, some in HtA_Flavor)
50850-50999 -                      (unassigned)
51000-51199 - North Amerigan events (separate file for each country?)
51200-51399 - South Amerigan events
51400-51449 - More FRA
51450-51499 - Baltic countries
51500-51549 - Indonesia
51550-51599 - MORE Aquitania
51600-51649 - Misc European, spread across different files
51650-51699 - Mediterranean
51700-51750 - Caribbean
51751-51850 - The Near East (first half), Persia (second half)
51851-51899 - More Italy
51900-51999 - More European flex files
52000-52099 - South Africa
52100-52199 -                     (unassigned)
52200-52299 - North Africa
52300-52399 - Rest of Africa
52400-52499 -                     (unassigned)
52500-52799 - Southeast Asia (not including Indonesia, obviously)
52800-52999 -                     (unassigned)
53000-53199 - China, Korea, etc
53200-53299 - Balkans

59800-59949 - Misc. events
59950-59999 - Debugging events
97091-97098 - North American settlement events
97097 - Event/decision to enable railroading
97098 - Claiming Amerigan interior provinces
97099-97107 - Outremer-related events