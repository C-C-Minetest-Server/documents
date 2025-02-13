# Welcome to 1F616EMO Survival Server!

* Telegram group: https://t.me/emo_minetest
* Discord server: https://discord.gg/bFhZuwQxDX
* Wiki: https://wiki-twi.1f616emo.xyz/
* Interactive map: https://map-twi.1f616emo.xyz/
* Monitoring dashboard: https://monitoring.1f616emo.xyz/goto/ukDqa9BSg?orgId=1

## Asking for building naming ideas!

I am building an apartment building at Spawn South. Suggest names by typing `/report` in the chatroom and select "Admin" as the receiver.

## Client compatibility policy

We support:

* Latest stable version of Minetest
* Latest development version of Minetest
* Latest stable version of MultiCraft on iOS
    * Android/Desktop users are expected to use official Minetest.

Other clients are not supported.

---

## Updates 2024-12-31

* Properly remove percent translation shortcuts containing Lua pattern characters (C-C-Minetest-Server/babelfish\_redo@e217b43)
* Add LCD-themed sign font (https://codeberg.org/Nazalassa/font\_lcd)
* Add LuaATC Textline Display (https://codeberg.org/Nazalassa/luaatc\_textline)
* Allow helpers to set other's preferred language (C-C-Minetest-Server/twi\_mods@4763315)
* Show language code in `/bblang` and `/bbset` (C-C-Minetest-Server/babelfish\_redo@782c6a5)
* Split `/bbset` into `/bbset` and `/bbget` (C-C-Minetest-Server/babelfish\_redo@0bd9834)
* Improve `/bmsg` feedbacks (C-C-Minetest-Server/babelfish\_redo@210bb95)
* Yet another attempt to fix background music stacking up when pressing the day button too fast (C-C-Minetest-Server/background\_music@47a5bd2)
* Allow translating chat messages into multiple languages by comma-seperating targets (C-C-Minetest-Server/babelfish\_redo@750e81f)
* Translate incoming mail to player's preferred language (C-C-Minetest-Server/babelfish\_mail)
* Fix opened platform screen door node box (C-C-Minetest-Server/advtrains\_doors@a796b50)
* Allow displaying different contents on two sides of hanging displays (https://codeberg.org/Nazalassa/luaatc\_textline/pulls/1)
* Fix LuaATC Textline orientation on MultiCraft clients (C-C-Minetest-Server/twi\_mods@ae2b468)

## Updates 2024-12-30

* Switch to Lingva translate, and a whole new translation mod (C-C-Minetest-Server/babelfish\_redo)

## Updates 2024-12-28

* Fix train gravel sounds (C-C-Minetest-Server/train\_gravels@5ae7726)
* Allow translating messages in-game by the following methods: (C-C-Minetest-Server/babelfish)
    * By adding `%<target code>` to messages;
    * By setting preferred language with `/bblang <code>` and translate a player's last message with `/babel` (main channel only)
    * Note that LibreTranslate gives poor detection results for CJK.

## Updates 2024-12-27

* Allow boarding wagons with irregular width from the platform (https://lists.sr.ht/~gpcf/advtrains-devel/patches/56618)
* Prevent falling nodes from destroying digtrons (C-C-Minetest-Server/twi\_mods@28fe8fb)
* Apply attach offset patch to boats and buses (C-C-Minetest-Server/linetrack@de5ecd4)
* Stop forever-looping boat sounds (C-C-Minetest-Server/linetrack@de5ecd4)
* Improve linetrack signal and TCB selection boxes (C-C-Minetest-Server/linetrack@6c96840)
* Add Gravel on (Split) Stone Tile (C-C-Minetest-Server/train\_gravels@1676093)
* Allow moderators to set up for sale signs for other players (C-C-Minetest-Server/um\_area\_forsale@969b4b0)
* Add half-height cottage fences (C-C-Minetest-Server/cottages@057b88e)
* Allow using Cod and Cichlid to feed cats (ElCeejo/animalia#73)
* Allow cutting down Ethereal bamboo with chainsaw (mt-mods/technic#389)
* Gazette issue 2024-12-26-02 (Gazette Delivery Service) will be sent to every new players (C-C-Minetest-Server/twi\_mods@625ab9e)

## Updates 2024-12-24

* Fixed door entry point of boats (C-C-Minetest-Server/linetrack@1bb9792)
* Open doors on platforms for non-standard width (e.g. boats) (C-C-Minetest-Server/advtrains\_doors@aab0aea)

## Updates 2024-12-23

* Added rubber wood banisters (C-C-Minetest-Server/twi\_mods@73fe561)
* Rotated banisters textures of some ethereal wood types (C-C-Minetest-Server/banisters@0b275cd)
* Added left- and right-fixed platform screens and doors (C-C-Minetest-Server/advtrains\_doors@7780436)
* Added concrete platform screens and doors (C-C-Minetest-Server/advtrains\_doors@fdeab12)
* Added platform doors that opens downwards (C-C-Minetest-Server/advtrains\_doors@8f2d433)
* Added Advtrains-based boats (C-C-Minetest-Server/linetrack)
* Added bakedclay and terracotta platform doors (C-C-Minetest-Server/advtrains\_doors@5b84d2c)

## Updates 2024-12-20

* Fix sending a copy to the sender themselves when using moderators and admin mailing list (C-C-Minetest-Server/admin\_mail@c36d994)
* Allow sending mail to all helpers (incl. admin and moderators) via `additional\_role:helper` (C-C-Minetest-Server/twi\_mods@357562b)
* Allow moderators to send mail to everyone using `$everyone` (C-C-Minetest-Server/mail\_everyone)

## Updates 2024-12-15

* Added Christmas decorators and gifts (C-C-Minetest-Server/simple\_christmas)

## Updates 2024-12-07

* Allow opening platform doors from inside (and from outside for track builders) (C-C-Minetest-Server/advtrains\_doors@9a97735)
* Merged Technic CNC slopes and moreblocks slopes (C-C-Minetest-Server/twi\_mods@90b4ae9)

## Updates 2024-11-30

* Replaced "Are you new?" signs at Spawn with "Want to build?"

## Updates 2024-11-17

* Allowing stacking bricks on another (C-C-Minetest-Server/stackbricks)

## Updates 2024-11-16

* Advtrains: Increased max speed of Night Line Seat Wagon to 30 m/s (C-C-Minetest-Server/twi\_mods@79e97ef)

## Updates 2024-11-14

* Banned the N-word and the F-word on new player usernames (C-C-Minetest-Server/twi\_mods@fdd344a)

## Updates 2024-11-07

* Phonograph updates:
    * Added Black Bass Blues by Elm Shadow (Elementalcraft) (C-C-Minetest-Server/phonograph_album_elm_shadow)
    * Added LoFi, Ride and Neon Lights by Helena Bolan (HelenasaurusRex) (C-C-Minetest-Server/phonograph_album_helena)
* Fixes falling node not turning into nodes (minetest/minetest#15378)

## Updates 2024-11-05

* Spawn Line trains now stop at Yantian Road again

## Updates 2024-11-03

* Apply protection on datacard diskdrives (C-C-Minetest-Server/datacard@770e2e1)
* Added tree log spikes (codeberg.org/SilverSandstone/logspikes)
* Plants and grass are now floodable (AFCMS/farming\_flood)
* Added height-extended platform gates (C-C-Minetest-Server/advtrains\_doors@13283b3)

## Updates 2024-10-31

* Railway Updates:
    * Spawn Line is now a loop line.
    * E2 no longer serves North Luciopoli as the Spawn Line serves its role.

## Updates 2024-10-30

* Reduced the Islands Line to Spawn Island, and added Mountain Foot and Lianyi Road to the Spawn Line

## Updates 2024-10-27

* IDs of deleted areas are no longer reused (minetest-mods/areas#83)
    * They are reused only if the server restarts.
* Removed the problemic recipe of Vertical wooden roof (C-C-Minetest-Server/cottages@7abadb9)

## Updates 2024-10-25

* Tutorial guiding newcomers to the Public Mine (C-C-Minetest-Server/twi\_mods@8038bb2)
* Added gravel on more stone bricks (C-C-Minetest-Server/train\_gravels@d8843c9)
* Fixed background music often malfunctioning when using the day button (C-C-Minetest-Server/background\_music@7ad5831)
* Moderators: added `/day` command which handles everything (C-C-Minetest-Server/twi\_mods@97494b2)
* Allow digging pipeworks filter-injectors without clearing its filter (mt-mods/pipeworks#141)
* Revert "Allow using `getstate()` on Ks Main and Shunting signals" (C-C-Minetest-Server/advtrains@914387b)
* Cottage updates: (C-C-Minetest-Server/cottages)
    * Added inner and outer corner cottage roofs (@99c7250)
    * Added verical roofs (@11fa08b)
    * Allowed using circular saw on Clay Block and Loam (@35572b2)
* Advtrains updates:
    * Added the Vacuum Wagon (https://notabug.org/Maverick2797/advtrains-vactrain/)
    * Increased speed limit of the following train wagons to 30 m/s: (C-C-Minetest-Server/twi\_mods@213537d)
        * DLX Diesel Locomotives
        * Moretrains Night Line Couchette and Seat Wagon
        * Moretrains Railroad Car
        * Moretrains Industrial wood wagons
        * Moretrains Industrial tank wagons
        * Moretrains Gondola wagons
* Optimize mapblock sending for fast-moving clients (Emojigit/minetest@7658de8c8)
* Show helpers in /list\_mods (C-C-Minetest-Server/twi\_mods@a2457a1)

## Updates 2024-10-21

* Wiki: Changed default skin to Citizen

## Updates 2024-10-17

* `[REVERTED]` Advtrains: Allow using `getstate()` on Ks Main and Shunting signals (https://lists.sr.ht/~gpcf/advtrains-devel/patches/55484)

## Updates 2024-10-15

* Enabled Email on the Wiki

## Updates 2024-10-11

* Added Saber plushie from Fate/stay night (C-C-Minetest-Server/fumoplushies@6c682d3)
* Web panel for resetting password (C-C-Minetest-Server/webpanel)

## Updates 2024-10-06

* The post office is open!
* Advtrains: Added speed signs for speeds >= 20 m/s (https://lists.sr.ht/~gpcf/advtrains-devel/patches/55351)

## Updates 2024-10-04

* Allow enabling volumetric lighting (rollerozxa/volumetric-lighting)
* Remove dirts obtainable via crystal shovels from digtron builder substitution table (C-C-Minetest-Server/twi\_mods@60ba926)
* Send tips when newcomers send "spawn", "escape" or "stuck" (C-C-Minetest-Server/twi\_mods@48865e6)
* Increased top speed of Advtrains E231 series to 30 m/s (C-C-Minetest-Server/twi\_mods@27dedc1)

## Updates 2024-09-30

* Advtrains: Allow creating new routes from existing ones (https://lists.sr.ht/~gpcf/advtrains-devel/patches/55253)

## Updates 2024-09-27

* Send background musics dynamically (C-C-Minetest-Server/twi\_mods@8194039)
* Added Stepping Pebbles (No Drums) by Matthew Pablo to Spawn day BGM (C-C-Minetest-Server/twi\_mods@9dfb1ad)
* Added Path to Lake Land by Alexandr Zhelanov to Spawn night BGM (C-C-Minetest-Server/twi\_mods@9520735)
* Attempt to fix newcomers missing basic privileges except `public\_farm` (C-C-Minetest-Server/twi\_mods@95061bc)
* Added admin shop for LuaATC Components, avaliable only to LuaATC operators (C-C-Minetest-Server/twi\_mods@b24185f)

## Updates 2024-09-21

* Changes on John Oestmann's Phonograph albums: (C-C-Minetest-Server/phonograph\_album\_john\_oestmann)
    * Added _Soundworlds Racing: Cruises I_ (@23d0108)
    * Added _Soundworlds Datapedia: Sigmir Ambient_ (@5743c6d)
    * Altered short title of existing albums (@8da2075)

## Updates 2024-09-15

* Fixed area boundary display on punching protector blocks (C-C-Minetest-Server/protect\_block\_area@b1ff54b)

## Updates 2024-09-14

* Lifted large-scale protection at SmushyVille

## Updates 2024-09-08

* Advtrains improvements
    * Allow manually sorting of signal routes (https://lists.sr.ht/~gpcf/advtrains-devel/patches/54927)
    * Update influence point markers, and allow right-clicking them (https://lists.sr.ht/~gpcf/advtrains-devel/patches/54931)
    * Allow operate `on\_rightclick` nodes with track placers and wagon placers (https://lists.sr.ht/~gpcf/advtrains-devel/patches/54932)

## Updates 2024-09-06

* Applied low-pass filter to sonic screwdriver sound (mt-mods/technic#377)
* Use the first line of outside text as display text of 01700 series (SamMatzko/minetest-subways#13)

## Updates 2024-09-04

* Phonograph GUI improvements: (C-C-Minetest-Server/phonograph)
    * Show a message about downloading songs (@0e76cd4)
    * Update formspec when the phonograph is modified by others (@0e76cd4)
    * Add Teacher tutorial link (@1c72e69)
* Fix advtrains sometimes crashing when using formspec on no-longer-exist wagons (https://lists.sr.ht/~gpcf/advtrains-devel/patches/54867)
* Fix positional stereo sounds of sonic screwdrivers (mt-mods/technic#376)

## Updates 2024-09-03

* Fixed recipe of Industrial tank wagon and Industrial wood wagon (https://lists.sr.ht/~gpcf/advtrains-devel/patches/54799)
* Attempt to fix 5.9 network regression (minetest/minetest#15087)

## Updates 2024-09-01

* Added Vegan Butter (codeberg.org/tenplus1/farming@0addf04)
* Fixed the following recipes:
    * Vertical Slate (C-C-Minetest-Server/cottages@384e1ba)
    * Gelatin Powder (codeberg.org/tenplus1/bonemeal@2a4ddd9)
    * Garlic Butter Shrimp (codeberg.org/tenplus1/farming@0addf04)
    * Teriyaki Chicken and Paella (C-C-Minetest-Server/twi\_mods@fa2542c)
* Added direct recipe for every orientation of Advtrains wallmounted signals (https://lists.sr.ht/~gpcf/advtrains-devel/patches/54800)
* Hide Advtrains demo signals from the craftguide (C-C-Minetest-Server/twi\_mods@4db0de0)
* Fixed coliision box and selection box of Ks Shunting Signals (https://lists.sr.ht/~gpcf/advtrains-devel/patches/54619)
* Fixed digging papyrus or bamboo with node digger or digtron crashing the server (minetest/minetest\_game#3133)
* Added Sh2 signals (C-C-Minetest-Server/advtrains\_ks\_sh2)

## Updates 2024-08-30

* Changed Ethereal and Farming Redo textures from 32px to 16px
* Added "public_farm" privilege to decide whether a player is permitted to use public farms (C-C-Minetest-Server/twi\_mods@ce47994)
    * This privilege is granted by default, and is taken away only if players refuse to replant.
* Fixed right-clicking nodes with protector blocks placing down the protector (C-C-Minetest-Server/protect\_block\_area@9217587)
* Allow walking into 01700 Series and LRV Type 9 train wagons (SamMatzko/minetest-subways#11)
* Opening platform gates / screen doors base on door position (C-C-Minetest-Server/advtrains\_doors@attempt-doors)
* Fixed Chinese translation of "Subway" (C-C-Minetest-Server/trainblocks@c5345b2)
* Non-CJK Ehlphabets: Switch back to Serif font (C-C-Minetest-Server/ehlphabet@c44a74f)

## Updates 2024-08-28

* Added the following albums by John Oestmann to Phonograph:
    * _Soundworlds Datapedia: Volume II_ (C-C-Minetest-Server/phonograph\_album\_john\_oestmann@78e4d88)
    * _Soundworlds Racing: Sands of Ouros (Season XVI)_  (C-C-Minetest-Server/phonograph\_album\_john\_oestmann@078e641)
* Added "if you need help in non-English languages" in nearly every supported languages (C-C-Minetest-Server/twi\_mods@b27c078)
* Added Ehlphabet Stickers, sticker-like node with white text and transparent background, made in the letter machine with glass panes (C-C-Minetest-Server/ehlphabet@67cbb99)
* Removed black border of the apartment tile from apartment setup screen (C-C-Minetest-Server/apartment@ba28ea3)
* Fixed "Failed to generate [sheet:4x4:3,4" errors (ElCeejo/animalia#93)

## Updates 2024-08-27

* Moved Spawn Public Farm to somewhere further away
* Rules change: "Respect other players" -> "Be a good part of the community"

## Updates 2024-08-24

* Apply area protection on Digtron builder, automatic controller, and duplicator (minetest-mods/digtron#108)
* Fix digtron owner moving twice when standing in front of their digtron (minetest-mods/digtron#110)
* Fixed Ks signal collision boxes (https://lists.sr.ht/~gpcf/advtrains-devel/patches/54619)
* Various Ehlphabet improvements (mainly C-C-Minetest-Server/ehlphabet@4c4fd8e)
    * Renamed stickers to "Ehlphabet Sticker 'character'"
    * Fixed ehlphabet block and sticker sounds
    * Allow creating uppercase blocks/stickers from lowercase input
    * Allow creating empty sticker with an empty string as the input
    * Allow moving materieals in and products out by shift-clicking
    * Disallow items other than matereials to go inside letter machines
    * Allow crafting Chinese character stickers from alphabet stickers
    * Added ehlphabet blocks and stickers of "非", "常", "可", "爱", "愛", "的" (@986c7fc)
    * Fixed pressing enter closing the interface (@df76e8b)
* Railway blocks improvements
    * Line signs are no longer upside down on the back (C-C-Minetest-Server/trainblocks@f736a7d)
    * Added recipies for the following nodes: (C-C-Minetest-Server/trainblocks@f79bdc9)
        * Modern Station Signs (Directional), and hence Station Signs
        * Mountain Railway Block
        * No Pedestrians Sign (Normal and German)
* Change wordings in lag recover restart message (will -> may) (C-C-Minetest-Server/lag\_recover@0f9105d)
* Allow moving tools onto and out of an anvil by shift-clicking (only works on new anvil) (C-C-Minetest-Server/cottages@061b91d)
* Fixed sounds of baskets (C-C-Minetest-Server/basket@8831966)
* Show CC0 license notice of John Oestmann's musics (C-C-Minetest-Server/phonograph\_album\_john\_oestmann@f53a3f8)

## Updates 2024-08-20

* Fixed side texture of empty rubber tree trunk (C-C-Minetest-Server/twi\_mods@4615b59)
* Server now restarts itself under extreme lag (C-C-Minetest-Server/lag\_recover)
* Reject new usernames containing "admin" or "moderator" (C-C-Minetest-Server/twi\_mods@94ddffb)

## Updates 2024-08-18

* Temporary removed max light limit on rhubarb (C-C-Minetest-Server/twi\_mods@5a464c4)
* Stop pineapples from overriding growing pineapples (C-C-Minetest-Server/twi\_mods@c15cc4f)
* Fixed recipe of all-faced ethereal trees (C-C-Minetest-Server/ethereal\_all\_faces@be2e0a0)

## Updates 2024-08-15

* Fixed infotext not updating when placing down empty baskets (C-C-Minetest-Server/basket@c325667)
* Fixed Mesecons on errata doors and trapdoors (C-C-Minetest-Server/minetest\_errata@e53ebe1)
* Fixed selection box of rubber tree saplings (C-C-Minetest-Server/twi\_mods@91058b4)
* Added "Helper" role (C-C-Minetest-Server/twi\_mods@0cc95d8)
* Added Yuri, the Travelling Shoppe by John Oestmann to Spawn BGMs (C-C-Minetest-Server/twi\_mods@474b5b0)
* Fixed Discord server link in random messages (C-C-Minetest-Server/twi\_mods@9213814)

## Updates 2024-08-14

* Rubber tree features: (C-C-Minetest-Server/twi\_mods@e462a17)
    * Added: Rubber Tree Planks, All-faces Rubber Tree Trunk, Rubber Tree Fence
    * Allow cutting rubber-related nodes with circular saw
    * Allow chopping rubber tree with choppy
* Appointed HelenasaurusRex as moderator

## Updates 2024-08-13

* Added all-faces tree nodes for ethereal trees (C-C-Minetest-Server/ethereal\_all\_faces)
* Fixed inserting items into baskets via tubes not updating infotext (C-C-Minetest-Server/basket@952c1d3)
* Added Phonograph album of HelenasaurusRex's musics (C-C-Minetest-Server/phonograph_album_helena)
* Allow crafting oil extract from bushes, mushroom pores, and mushroom caps (C-C-Minetest-Server/twi\_mods@ca26f86)

## Updates 2024-08-12

* Rules update: Added "No begging"

## Updates 2024-08-10

* Media loading time optimization
    * Dynamic media support for Phonographs (C-C-Minetest-Server/phonograph@dd7b615 and others)
    * JPG lossy compression for Teacher tutorial screenshots
    * Media loading time should be reduced by around 62%
* Added cover photo for John Oestmann's Phonograph albums (C-C-Minetest-Server/phonograph_album_john_oestmann@342550d)
* Added address field to mapserver POIs (minetest-mapserver/mapserver_mod#37)

## Updates 2024-08-06

* Optimized performance of the inbox (mt-mods/mail#151)
* Visualize protection area on punching or placing protector blocks (C-C-Minetest-Server/protect_block_area@a9a5489)
* Added fancy travelnets (C-C-Minetest-Server/travelnet_redo_fancy)

## Updates 2024-08-05

* Fix train horn being heared all over the server (C-C-Minetest-Server/basic\_trains@e4ffae9)
* Added command alias: `/pt` -> `/protect` (C-C-Minetest-Server/twi_mods@1d5a5ca)
* Changed "Mod" highlight in chat to something lighter (C-C-Minetest-Server/beerchat\_roles@d9d08c5)
* Fixed sign failing to wrap lines if pasted from Windows
    * Road signs, street signs, banners, labels: mt-mods/display_modpack#19
    * Other signs: mt-mods/signs_lib#32
* Make signs glow in the dark by punching with a torch (C-C-Minetest-Server/twi\_mods@cf2bf82)

## Updates 2024-08-03

* Fix server crashing when editing travelnets with sorting key (C-C-Minetest-Server/travelnet\_redo@e384fe6)
* Remind that digging is the way to remove travelnets (C-C-Minetest-Server/travelnet\_redo@30008b5)

## Updates 2024-08-02

* Fix chat role displaying breaking whispering and `/me` (C-C-Minetest-Server/beerchat\_roles@70df5f3)
* Basket improvements:
    * Count occupied inventory slots (C-C-Minetest-Server/basket@bb80e99)
    * Added tutorial for baskets (C-C-Minetest-Server/basket@9604683)
* Added chatcommand shortcuts (C-C-Minetest-Server/twi\_mods@5e35a59)
    * `/h` -> `/help`
    * `/?` -> `/tutorial`

## Updates 2024-07-31

* Travelnet enhancements
    * Fixed new dialog not showing after pressing buttons (C-C-Minetest-Server/travelnet\_redo@b09c791)
    * Added tutorial button to Travelnet UIs (C-C-Minetest-Server/travelnet\_redo@d7f59cb)
    * Added hints about the protection flag (P) (C-C-Minetest-Server/travelnet\_redo@5688ff0)
* Play a sound before showing unlocked tutorials (C-C-Minetest-Server/teacher@69c48af)
* Added dirt digging sound on creating paths (Atlante1952/atl_path#2)
* Allowing planting pineapples with whole pineapple, returning rings (C-C-Minetest-Server/twi\_mods@a75f296)
* Removed corrency bundles (C-C-Minetest-Server/twi\_mods@4414fc2)
    * Existing bundles can be crafted into notes worth 9 MG.
* Removed crafting recipes with unknown items (C-C-Minetest-Server/clean_unknown_recipe)
* Fix shovel can't right-click nodes with custom on\_rightclick (Atlante1952/atl\_path#4)
* Added tutorial button to For Sale Sign UI (C-C-Minetest-Server/um\_area\_forsale@0146ac5)

## Updates 2024-07-29

* Limited furnace sound volume on catch-up smelting (minetest/minetest\_game#3144)
* Added tips for chests and storages (C-C-Minetest-Server/twi\_mods@4469ba8)
* Fixed light level of upper travelnet box (C-C-Minetest-Server/travelnet\_redo@a539ab6)
* Simplified tutorial unlock messages (C-C-Minetest-Server/teacher@180e8ff)
* Added dirt paths, created by right-clicking / tapping the top of dirt with shovels (C-C-Minetest-Server/atl\_path)

## Updates 2024-07-25

* Make song bird nest floodable and replacable (C-C-Minetest-Server/twi\_mods@2c2e1e0)

## Updates 2024-07-19

* Gray out role information for the sender themself (C-C-Minetest-Server/beerchat\_roles@6e6098d,39265e8)
* Fix bakedclay alloying wrongly giving 8 outputs (C-C-Minetest-Server/technic\_recipes@1158afdd)
* Removed the "RTC" text on the bottom of RTC nodes (minetest-mods/digilines#86)
* Added Telemosaic-like Travelnets (C-C-Minetest-Server/travelnet\_redo\_beacons)
* Applied area protections on digtron storage nodes (minetest-mods/digtron#108)
* Allowed moving fuel items in combined storage by shift-clicking (minetest-mods/digtron#109)
    * Note that existing storages (both in-world and in-crate) are not updated. Please dig and place them again.
* Print list of online moderators on player join and `/list_mods` (C-C-Minetest-Server/twi\_mods@1a7224b)
* Reduced selection box height of fern (C-C-Minetest-Server/twi\_mods@00c64e6,15b84ab)
* Pipeworks support on mailboxes (C-C-Minetest-Server/mailbox@214affa)
* Added visualization of vacuum tube range (mt-mods/pipeworks#128)

## Updates 2024-07-18

* Fixed screwdriver altering nodes it shouldn't (mt-mods/technic#368)
* Fixed the sonic bomb of the Sonic-BOMB Screwdriver (mt-mods/technic#369)
* Show player role (Admin, Mod) in chat messages (C-C-Minetest-Server/beerchat\_roles)
* Removed duplicated technic recipies (C-C-Minetest-Server/technic\_recipes@1bc2967)
    * Breaking change: Now one clay consumes one dye when alloyed into bakedclay
* Allow re-dying travelnets by punching with dye (C-C-Minetest-Server/travelnet\_redo@5260971)

## Updates 2024-07-13

* Logging node placers into node metadata (C-C-Minetest-Server/node\_placer)
* Added ropes and extendable ladders (C-C-Minetest-Server/ropes)
* LuaATC OOP API: Added methods `ars_check_rule_match` and `has_rc`
* Log inventory actions on battery holders (minetest-mods/digtron#106)
* Do logging on all cottage storage nodes (C-C-Minetest-Server/cottages@06a510a)
* Added more functions to the inventory UI (mt-mods/unified\_inventory\_plus)
* Log furnace inventory actions (minetest/minetest\_game#3141)

## Updates 2024-07-12

* Fixed player making noises when standing above travelnets (C-C-Minetest-Server/travelnet\_redo@c4038db)
* Travelnets now teleport players to the bottom of the box (C-C-Minetest-Server/travelnet\_redo@69cb498)
* Added tutorial teaching how to use a travelnet (C-C-Minetest-Server/travelnet\_redo@dc55c19)
* Added tutorial for elevators (C-C-Minetest-Server/teacher\_tutorial\_elevator)
* The server is now running in verbose mode. Expect lags up to a second.

## Updates 2024-07-08

* Added tutorial on protection violation (C-C-Minetest-Server/twi\_mods@9937002)
* Added the following chatcommand alias: (C-C-Minetest-Server/twi\_mods@f753d20)
    * `/p1` -> `/area_pos1`
    * `/p2` -> `/area_pos2`
    * `/t` -> `/tutorial`
* Two wood planks of any type can be crafted into two apple wood planks (C-C-Minetest-Server/twi\_mods@68f925f)
    * Place the planks verically - the horizontal recipe collides with pressure plate

## Updates 2024-07-06

* **[EXPERIMENTAL]** Added object-oriented train interaction code into LuaATC
    * https://github.com/C-C-Minetest-Server/advtrains/tree/fork-20240706-luaatc-oop-api
    * Documentation: https://github.com/C-C-Minetest-Server/advtrains/blob/fork-20240706-luaatc-oop-api/advtrains_luaautomation/oop_api.md
* Fix well taking more than one bucket (C-C-Minetest-Server/cottages@8d0aa2d)

## Updates 2024-07-04

* New routes named exactly `*`, `C`, or `c` are set to be the default route (C-C-Minetest-Server/advtrains@ca3c0b8)

## Updates 2024-07-03

* Added protected travelnets back into the list (C-C-Minetest-Server/travelnet\_redo@7284222)
* Temporary removed background music in SmushyVille (C-C-Minetest-Server/twi\_mods@123d78a)
* Allowed relative coordinates in `/area_pos1` and `/area_pos2` (minetest-mods/areas#77)

## Updates 2024-07-02

* Travelnets with same leading integers now sorts alphabetically (C-C-Minetest-Server/travelnet\_redo@ab3e250)
* Teleport player to spawn if shouted spawn two times in 30 seconds (C-C-Minetest-Server/twi\_mods@c150bba)
* Travelnet owners can teleport to protected networks regardless of protection state (C-C-Minetest-Server/travelnet\_redo@4b9c584)
* Added background musics for Spawn Island and SmushyVille (C-C-Minetest-Server/background\_music; C-C-Minetest-Server/twi\_mods:twi\_bgm)

## Updates 2024-07-01

* Travelnets with name prefix `(I)` are now entry-only (C-C-Minetest-Server/travelnet\_redo@11ddc22)

## Updates 2024-06-30

* Fixed TCB marker leaving behind after TCB removal (https://lists.sr.ht/~gpcf/advtrains-devel/patches/53601)
* Fixed positional stereo sound of animals (ElCeejo/animalia#98)
* Increased radius of track-searching in Advanced Trains tutorial triggering (C-C-Minetest-Server/teacher\_tutorial\_advtrains@5446d52)

## Updates 2024-06-29

* Added wooden buckets for water (C-C-Minetest-Server/wooden\_bucket)
* Added the following fonts to signs/banners:
    * OldWizard (pyrollo/font_oldwizard)
    * Botic (pyrollo/font_botic)
* Fixed node sounds of cottage nodes (C-C-Minetest-Server/cottages@9eb2fee)
* Tweaked rate of grass dropping seeds (codeberg.org:tenplus1/farming@37ea21fdaf~e33dd0e275)

## Updates 2024-06-28

* Improvements of cottage ropes: (C-C-Minetest-Server/cottages@44947c6)
    * Allowed ropes to be dug without supportings
    * Modified the selection box so it matches the texture
* Added alloying recipe of crystal ingots (C-C-Minetest-Server/twi\_mods@081ce58)

## Updates 2024-06-26

* Allowed dry dirt with dry grass to spread (C-C-Minetest-Server/twi\_mods@4825e85)
* Fix travelnet disappearing after editing w/o moving network (C-C-Minetest-Server/travelnet\_redo@24fc096)

## Updates 2024-06-25

* Added tutorials unlocked upon buying plot (C-C-Minetest-Server/twi\_mods:teacher\_tutorial\_post\_buying\_plot)

## Updates 2024-06-23

* Travelnets now sorts case-insensitively (C-C-Minetest-Server/travelnet\_redo@6ebdf2b)
* Added license notice page into travelnet UIs (C-C-Minetest-Server/travelnet\_redo@5cd8acd)

## Updates 2024-06-22

* Allowed editing existing travelnets (C-C-Minetest-Server/travelnet\_redo@ca1dd9a)
* Added sort keys for travelnets (C-C-Minetest-Server/travelnet\_redo@6cbc65c~e9de28c)
* Added crafting recipe of cyan travelnets (mt-mods/xcompat#31)
* Added hiking signs (C-C-Minetest-Server/hiking)
    * Unlike upstream, hiking signs can be placed by anyone.

## Updates 2024-06-21

* Added tutorial and HUD for new players to know how to use the chatroom (C-C-Minetest-Server/twi\_mods:chatroom\_tutorial)
    * The previously proposed "no chat no interact" is replaced by this one.
* Added travelnet (but not elevators) (C-C-Minetest-Server/travelnet_redo)

## Updates 2024-06-20

* Simplified the rules, and hosted it on the Wiki (https://wiki-twi.1f616emo.xyz/wiki/Project:Rules)
* Slightly tweaked Phonograph playing rules (C-C-Minetest-Server/phonograph@2f67f6a)
* Added instructions to ATM GUI (C-C-Minetest-Server/um_atm@1eb2cfe)

## Updates 2024-06-17

* Reduced lag when emerging new chunks (C-C-Minetest-Server/fix\_floating@569c5cb)
    * Emerging block is still slow, but it no longer block other activities
* Digtron controller now shows the name of missing building materieal (minetest-mods/digtron#103)

## Updates 2024-06-16

* Added Fumo Plush: Cirno (WhatsApp variant), Hatsune Miku
    * C-C-Minetest-Server/fumoplushies@7f20823, upstream: upsidedownsweetfood/FumoPlushiesMT@52f1722

## Updates 2024-06-15

* Fix thin texture on flat wooden bar side (C-C-Minetest-Server/minetest\_errata@6487929)
* Fix node digging grouops and sounds of facade nodes (TumeniNodes/facade#20)
* Added maple trees

## Updates 2024-06-14

* Introduced Advtrains train type: JR E231, Classic Coaches
    * Added JR E231 Series to the Admin Shop

## Updates 2024-06-15 *[sic]*

* Fixed positional stereo sound of Ander's Cross
    * https://lists.sr.ht/~gpcf/advtrains-devel/patches/53262

## Updates 2024-06-12

* Fixed conducted one way tube crafting recipe
* Updated phonograph UI

## Updates 2024-06-09

* Made 8 plots available for sale at Spawn South. The teleport pad at Spawn now points there.

## Updates 2024-06-06

* Added tutorial for Advanced Trains (showing up when visiting stations)

## Updates 2024-06-05

* Added ATMs (disabled by default) and For Sale Signs to the interactive map

## Updates 2024-06-04

* 
* Added more pipeworks tubes: (only listing the craftable ones)
    * Decelerating Pneumatic Tube Segment
    * Low Priority Tube Segment
    * Straight Only Tube (with Mesecons, Digilines, and Mesecons Digilines variants)
    * One Way Tube (Mesecons, Digilines, and Mesecons Digilines variants)

## Updates 2024-06-03

* The online interactive map is now online.
* Protection violations when placing down and catching bugs are now properly handled. (minetest/minetest\_game#3125)
* Fixed data of the track Farmer by Exhale & Tim Unwin in VoxelLibre Ambiences
* Added short descriptions for VoxelLibre Ambiences

## Updates 2024-06-16

* Added Fumo Plush: Cirno (WhatsApp variant), Hatsune Miku
    * C-C-Minetest-Server/fumoplushies@7f20823, upstream: upsidedownsweetfood/FumoPlushiesMT@52f1722

## Updates 2024-06-15

* Fix thin texture on flat wooden bar side (C-C-Minetest-Server/minetest_errata@6487929)
* Fix node digging grouops and sounds of facade nodes (TumeniNodes/facade#20)
* Added maple trees

## Updates 2024-06-14

* Introduced Advtrains train type: JR E231, Classic Coaches
    * Added JR E231 Series to the Admin Shop

## Updates 2024-06-15

* Fixed positional stereo sound of Ander's Cross
    * https://lists.sr.ht/~gpcf/advtrains-devel/patches/53262

## Updates 2024-06-12

* Fixed conducted one way tube crafting recipe
* Updated phonograph UI

## Updates 2024-06-09

* Made 8 plots available for sale at Spawn South. The teleport pad at Spawn now points there.

## Updates 2024-06-06

* Added tutorial for Advanced Trains (showing up when visiting stations)

## Updates 2024-06-05

* Added ATMs (disabled by default) and For Sale Signs to the interactive map

## Updates 2024-06-04

* 
* Added more pipeworks tubes: (only listing the craftable ones)
    * Decelerating Pneumatic Tube Segment
    * Low Priority Tube Segment
    * Straight Only Tube (with Mesecons, Digilines, and Mesecons Digilines variants)
    * One Way Tube (Mesecons, Digilines, and Mesecons Digilines variants)

## Updates 2024-06-03

* The online interactive map is now online.
* Protection violations when placing down and catching bugs are now properly handled. (minetest/minetest_game#3125)
* Fixed data of the track Farmer by Exhale & Tim Unwin in VoxelLibre Ambiences
* Added short descriptions for VoxelLibre Ambiences

## Updates 2024-05-31

* Added musics composed by Diarmuid and John Oestmann into Phonographs
* Minor visual tweaks on Phonograph GUI
* Removed some moderators-only buttons from the inventory
* Added button to the inventory to access the tutorials

## Updates 2024-05-30

* Added mosses for bamboo dirt, and allowed all mosses to be cut
* Added brown mushroom trees. They can't be bonemealed yet.

## Updates 2024-05-27

* Extended S1 to North Liciopoli

## Updates 2024-05-24

Back from days of illness... *sigh*

* Added textlines
* Railway line S1 now branches out to Spawn Island from Spawn South. 1 out of 3 trains will go there.

## Updates 2024-05-16

* Re-added `/tp` -> `/teleport`
* Changes on the Teacher mod:
    * Tutorials now list from the latest unlocked to the earliest.
    * Added command alias: `/tutorial` -> `/tutorials`

## Updates 2024-05-15

* Introduced the Teacher tutorial system (`/tutorials`) and the following tutorials:
    * The Teacher System
    * For Sale Sign
    * Phongraph
    * ATMs

## Updates 2024-05-11

* Reverted changes dones on 2024-05-09 to avoid conflicts with beerchat
* Added rPlace Server into the relayed chatroom

## Updates 2024-05-09 (Reverted)

* Added user join/leave messages to relayed chatrooms
* Introduced MC-style chat commands (e.g. `/tp`)
    * As a side effect, `/teleport` or `/tp` no longer works on offline players.

## Updates 2024-05-06

* Introduced beerchat
    * Added Discord server as relay target
    * You can now use `@USERNAME message` to send private messages
    * All messages are now in the channel `#mt_main`

## Updates 2024-05-01

* (MultiCraft) Fixed texture and facing problem of nodes

## Updates 2024-04-28

* Fixed repeating crash when placing down nodes (Rating: Critical)

## Updates 2024-04-27
* Introduced various colors of large banners

## Updates 2024-04-26

* Fixed Phonograph crash
* Added item description of unnamed baskets
* Fixed client-side texture error: `Failed to generate "[sheet:4x4:3,4"`

## Updates 2024-04-24

* Introduced VoxelLibre (MineClone2) ambiences into phonographs

## Updates 2024-04-21

* Introduced the `/news` system
* Fixed a regression on Towercranes where players leaving the game while on a crane would not be able to turn off the crane again
