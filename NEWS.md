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
