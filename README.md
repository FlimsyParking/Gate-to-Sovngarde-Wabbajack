Gate-to-Sovngarde-Wabbajack

Repository for my Wabbajack conversions of the Skyrim SE collection "Gate to Sovngarde" by JaySerpa.

GATE TO SOVNGARDE

A Skyrim SE Mod Collection by JaySerpa

converted to Wabbajack by Flimsy

Version 0.115.0.0 = V115 of the Collection

HOMEPAGES
--------------------------------------------

JaySerpa's Gate to Sovngarde:

https://www.nexusmods.com/games/skyrimspecialedition/collections/qdurkx

My Modding Projects:

https://ko-fi.com/flimsymods

GtS Wabbajack Edition on Nexus:

https://www.nexusmods.com/skyrimspecialedition/mods/172373

Github Repository of my Conversion:

https://github.com/FlimsyParking/Gate-to-Sovngarde-Wabbajack

CHANGELOG
--------------------------------------------

https://docs.google.com/document/d/1PZMxn1GjCr3GBEoSKxsexAaHKq1L1_Z-dQo79-D9XTo/edit?tab=t.0#heading=h.x4qqacrnyjb

DISCORD
--------------------------------------------

https://discord.gg/jayserpa

For a description of the collection, infos on important features and mods, etc., please refer to the GtS Homepage.

DONATIONS
--------------------------------------------

NEW: If you want to, you can tip me a coffee under ko-fi.com/flimsymods. I'd be very happy if you do, it would really mean a lot to me! But please consider that this is still 90% the work of JaySerpa and many more fantastic mod authors. So please consider donating them first, or as well! Thank you :-)

HELPFUL LINKS
--------------------------------------------

https://wiki.wabbajack.org/user_documentation/Troubleshooting%20FAQ.html



--------------------------------------------
IMPORTANT: This Readme is a work in progress and may be subject to changes. If you find errors in this Readme or have suggestions for improvement, please say so in the Wabbajack Conversion Thread on the GtS Discord.
--------------------------------------------



REQUIREMENTS
--------------------------------------------

Skyrim SE 1.6.1170

IMPORTANT: This modlist comes in 2 stand-alone Versions: "Anniversary Edition Version" and "Non-AE Version". 

Be sure to download the right one!

Anniversary Edition ("AE") refers to the "Anniversary Edition Upgrade" DLC (https://store.steampowered.com/app/1746860/The_Elder_Scrolls_V_Skyrim_Anniversary_Upgrade/). 
Choose one version or the other depending if you have this DLC or not.

For minimum PC specs, please refer to the GtS Homepage.

It is recommended that you install GtS on a solid-state drive for performance reasons.



PRE-INSTALLATION *** IMPORTANT ***
--------------------------------------------

A clean install of Skyrim is required / HIGHLY RECOMMENDED to correctly install GtS Wabbajack Version. No support for installations without a clean install.

Don't know how to do a clean install? See ADHDecent's 2024 Modding Guide Part1: 
https://www.youtube.com/watch?v=ChdM7eE6zns&list=PLhvuRv3vONb5Uwb6rAy6y1r_1WB4Pe151&index=1
First part of the video, you don't necessarily need to follow everything that comes after "Prevent Game Updates".
Please also refer to the first pinned comment under the video. 

IMPORTANT: Make sure to make BACKUPS of files you want to keep (i.e. savegames)!

Run the Skyrim Special Edition launcher through Steam and let it detect your settings, then launch the game. If you have not installed Anniversary Edition content yet, you will be prompted to do so now. 

PLEASE BE PATIENT AND DO NOT TAB OUT OF SKYRIM DURING THE DOWNLOAD PROCESS. Doing so can lead to unfinished downloads which will break things.

If you haven't purchased AE content, still launch the game at least once to make sure it's all working. After that, you can close the game and exit to your desktop.

Double check that you have the latest Skyrim version on Steam (1.6.1170).

Install the latest Microsoft Visual C++ version on your PC: This is quite recent (July 2024). https://aka.ms/vs/17/release/vc_redist.x64.exe

Your game needs to be set to English. Playing in another language will break things. 

Start a new game: You cannot use an old save with the collection.

Check if you have enough space: Download size is roughly 73GB, but you will need around 116 GB on top of that to install the list (68 and 111 GB for non-AE). Once installed, you may delete the downloads folder, however this will lead to all of the files being downloaded again if you install an updated version of the list.

You need to have Nexus Premium (highly recommended!): All collections/modlists require premium for automatic installation, otherwise you have to manually install each mod and it'll take you forever. Support for manual installations (without Nexus Premium) is NOT OFFERED. There are simply too many things that can go wrong during manual installations.



INSTALLATION
--------------------------------------------

Download Wabbajack: https://www.wabbajack.org/

Create a new folder called “Wabbajack” in a location outside of the Program Files and outside other "System" directories such as Windows, Desktop, Downloads etc. Move Wabbajack.exe into this folder and run it. It will check for updates and install them, if there are any.

Link your Nexus account in Wabbajack (again: a Premium Membership is highly recommended). Hint: If you activate the premium membership after beginning a Wabbajack install, you can restart Wabbajack to enable automated downloads.

Create a new folder called “GtS-WJ” (or similar, but you NEED to keep it short to prevent issues with file path length) in a location outside of the Program Files and outside other "System" directories such as Windows, Desktop, Downloads etc.

If you're on a high resolution monitor (5k, 4k) but intend to play Skyrim at a lower resolution: for me it has proven good practice to lower your Windows resolution to that resolution before you install GtS with Wabbajack.

Open Wabbajack and click on "Browse lists" then either

- check "Non-featured" and navigate to the GtS version (AE or Non-AE, see above) you want and install it. (You may also want to narrow down the search to "Skyrim Special Edition" so that lists for other games aren't displayed.)

- or, if you downloaded from Nexus, Github or JaySerpa's Discord, click on "Install from disk" (top right corner) and choose the Gate to Sovngarde.wabbajack file you downloaded. You may also doubleclick the Gate to Sovngarde.wabbajack file in Windows Explorer, but for me that doesn't work reliably with the current WJ Version. You can also try to drag&drop the file on wabbajack.exe.

Once the installation window opens, ensure that the “Installation Location” matches the GtS folder you just created. The download location should populate automatically. You can change the download location, e.g. to a standard HDD, to save space on your SSD.

When you’re ready, press the start button.

After starting the installation, a window will pop up and ask for you to authorize Wabbajack to use your Nexus account, if you aren't logged in already. Log in and authorize Wabbajack on Nexus, and the installation will proceed. Wabbajack will now install the modlist; this will take a while, so be patient. When Wabbajack is finished, it should say “Installation Complete”.


PERFORMANCE & GRAPHIC CONFIGURATION
--------------------------------------------

Please note: this part is taken directly from JaySerpa's GtS Changelogs.

By default, GTS is capped at 120 FPS, uses FSR upscaling and has Frame Generation disabled. These options have been selected because they work for everybody, without you having to do anything. However, you can configure a few things for your specific case:

Upscaling Method: If you have an NVIDIA GPU, I recommend changing the upscaling method from FSR to DLSS. The image is a lot more stable and shows fewer artifacts.
This can be done by opening the Community Shaders menu (by default it’s under the END key) and going into the Upscaling Tab.

Frame Generation: FG is DISABLED by default. Mostly because there's a bug with Skyrim Souls causing certain items to show up semi-transparent in the inventory view and because not everyone can make use of it. If you already have 60 or more FPS, you have a monitor that supports it, and you want more frames, you can enable Frame Generation.
This option is also enabled in the Upscaling tab of CS. To access the menu, press the END key once inside the game.

Light Sources: Additional light sources from the mod  "CS Light" have been enabled. This will make the game look better, but might have an impact on performance. You can reinstall this mod and unselect the “Common Lights” sources to get the same configuration we had in previous versions.

Faster HDT-SMP: This uses the AVX instruction, to make it compatible with more CPUs. If you have a somewhat recent PC (made in the last 10 years…) chances are your CPU supports AVX2. If that’s the case, you can reinstall this mod and select AVX2 for better performance.


RESOLUTION ISSUES
--------------------------------------------

Please note: this is OLD Info, GtS now uses Auto Resolution, so most users shouldn't experience any issues with wrong resolutions.
I'm leaving this here for the time being, in case users run into any issues with resolution, they can try the following.

With the changes in 0.83.0.2, chances are high that the frequent resolution issues are a thing of the past. 

The following is a workaround to prevent RESOLUTION ISSUES, but it's best you do it anyway, even if you don't have such issues.

- Navigate back to your GtS installation folder and run ModOrganizer.exe.
- In Mod Organizer 2, go to the built-in INI editor: Menu "Tools" - "Tool Plugins" - "INI Editor".
- Select skyrimprefs.ini.
- Check if your resolution settings are right. These are the "iSize H" and "iSize W" values.
- Correct them if they are wrong.
- HIT "SAVE" AT THE BOTTOM OF THE EDITOR - REGARDLESS IF YOU CHANGED ANYTHING OR NOT. ALWAYS HIT SAVE.

This should fix the issue for most if not all users. 

If still have issues after that step, then they may be related to your Windows scaling settings. 
See this Reddit thread:
https://www.reddit.com/r/skyrimmods/comments/xi2yza/skyrim_using_windows_dpi_scaling_how_to_fix/

If you're on a high resolution monitor (5k, 4k) but intend to play Skyrim at a lower resolution: to deal with that lower your Windows Resolution accordingly before starting Skyrim. It's a minor inconvience, but the the best solution that I found until now. GtS includes tweaking to make SSE Display Settings and Frame Generation work together. However, this leads to the INI setting Fullscreen=1, which you may be used to, to become nonfunctional. This setting is not compatible with Frame Generation.

If you're on a wide or ultra-wide monitor, you'll have to install some additional fixes. See here: https://gatetosovngarde.wiki.gg/wiki/Wide_and_Ultrawide


STARTING Gate to Sovngarde
--------------------------------------------

Now that GtS WJ has been installed, you will need to launch Skyrim in a slightly different way.

Start Steam.

Navigate back to your GtS installation folder and run ModOrganizer.exe.

The MO2 screen displays all of your installed mods on the left and all of your plugin files on the right.

You will now have to launch Skyrim by selecting “Gate to Sovngarde” from the drop-down menu directly above the right plugins pane and pressing “Run”. 
Beneath the Run button, there is a way to add a Gate to Sovngarde shortcut to your desktop for added convenience.

Whenever you launch Skyrim from Mod Organizer, this message will pop up:

"The application must run to completion because its output is required."

THIS IS NOT AN ERROR, DO NOT PRESS “UNLOCK”. Simply wait a bit, and Skyrim will open.

DO NOT USE THE SORT BUTTON ON TOP OF THE PLUGINS LIST. It will not work. I took measures to prevent accidentally using it.
DO NOT DRAG & DROP MODS OR PLUGINS TO OTHER POSITIONS. IT WILL BREAK THE LIST.


Mod Configuration
--------------------------------------------

All of the Mod Configuration Menus have been pre-configured to the recommended settings. The only thing you need to do when you start a new game is play.

About updating mods: Several mods have older versions installed while a newer version might be available on Nexus. THIS IS INTENDED! THERE IS NO NEED TO UPDATE THESE MODS! Doing so will break the list.

Updating
--------------------------------------------

If GtS receives an update, please check the changelog before doing anything. Always backup your saves or start a new game after updating. Updating is like installing. You only have to make sure that you select the same path and tick the “Overwrite Existing Modlist” button.

IMPORTANT - regarding savegame compatibility: Always keep in mind that updates for the Wabbajack version of GtS will most often include several updates of the Vortex Version (i.e. from V89 straight to V96). Always check the original GtS Changelog for all included updates (i.e. for V90, V91 and so on up to V96) if you want to know if you can keep your savegames or not.

Modification / Customizing GtS
--------------------------------------------

Support for modified installations of Gate to Sovngarde Wabbajack Version WILL NOT be provided. However, if you’d like to make your own changes, there are a few important points to keep in mind.

If you attempt to update a modified installation of GtS, Wabbajack will delete all files that are not part of GtS during the update process.

This means that any additional mods you have installed on top of GtS will be deleted. To prevent this, you can add the prefix [NoDelete] to the names of the mods you want to keep and Wabbajack will ensure they are ignored during updates.

DO NOT USE THE SORT BUTTON ON TOP OF THE PLUGINS LIST. It will not work. I took measures to prevent accidentally using it. It uses a deprecated version of LOOT anyway. 

In general, modlists like GtS are just too big and complex to work with LOOT. It would need around 5 or 6 pages of custom rules too make sure that sorting doesn't break GtS. So if you add mods, you need to manually place them in the Loadorder after checking for conflicts with SSEdit. If you absolutely have to have LOOT, there's some great guides out there how to install it, e.g. from ADHDecent. But: you have been warned...
 
DO NOT DRAG & DROP MODS OR PLUGINS TO OTHER POSITIONS (unless you know what you are doing).

If you messed something up - I've included backups of the original modlist.txt and loadorder.txt. To restore them, press the "Restore Backup" button on top of the modlist or the plugins list. Remember that these backups will eventually get overwritten if you make backups yourself. Also don't change mod or plugin names, the backups are plain text files, they won't recognize changed names and restoring backups will (partly) fail if you change names.

This Modlist only supports the latest Steam Release of Skyrim, however there's a guide how to make it work with the GOG Version here: https://gatetosovngarde.wiki.gg/wiki/GOG_Compatibility#Mod_Organizer_2-0

This Wabbajack version of GtS uses the Stock Game Feature. That means it has a second, separate copy of your Skyrim Installation and will not touch your Steam Skyrim Installation. To learn more about the Stock Game feature I found the following link very helpful:
https://github.com/LivelyDismay/Learn-To-Mod/blob/main/lessons/Setting%20up%20Stock%20Game%20for%20Skyrim%20SE.md

This Wabbajack version of GtS uses the Rootbuilder plugin. To learn more about Rootbuilder it's best to watch the tutorial video on the mod's Nexus page:
https://www.nexusmods.com/skyrimspecialedition/mods/31720

Mod Notes
--------------------------------------------

Most of the mods in Gate to Sovngarde Wabbajack Version have notes attached to them. If the note icon appears next to a mod, hover over it to read the notes. Some of these notes may give you some additional context about how the mod has been configured. For the main part, however, these notes are needed for my conversion process from Vortex to MO2. Most of them may say nothing to you and have no important informations for you. Best is to simply ignore them. I will not delete these notes, that would be way to much work.

Very few mod notes you may need to read may be tagged with *** IMPORTANT ***. You can filter for these mods with MO2's search function, see bottom right of the mod pane. 

If there are no search results with notes tagged "*** IMPORTANT ***", then they are no such mods in this GtS Version!

Permissions
--------------------------------------------

If you want to fork this modlist: be sure to get JaySerpa's permission first!

Concerning me, permissions are open according to what Wabbajack says under https://wiki.wabbajack.org/policies_and_license/Policies%20and%20License.html and https://wiki.wabbajack.org/wabbajack_cdn_and_gallery_access/Criteria%20for%20'Featured%20Mod%20List'%20status.html.

This means that you are allowed to:

- Fork this modlist
- Modify it for personal or public use
- Recompile and redistribute your own version

under the following conditions:

- Your fork must use a different name and must not imply my or JaySerpa's endorsement, both unless given explicit permission to do so.
- Please ensure that any published fork represents an genuinely distinct project with meaningful changes. Minor or cosmetic changes alone (e.g., a few configuration edits; or only two mods on top) are not sufficient to present the list as a new work.
- Mere republishing without changes is not permitted. Uploading my original files anywhere is not allowed.
- You are responsible for maintaining and supporting your own version.
- All original mod authors’ permissions and distribution rights must be respected.
- These permissions apply to the modlist only - not to the third-party mods included.

Please do credit me and keep it very clear that I can't give any support to users of modlists that use mine as a base. If you have any questions about my conversion, how I did things etc., feel free to ask, I'm happy to answer them. But please understand that I sometimes may need time to answer, especially when I'm focused on other things like a GtS update etc.


Credits
--------------------------------------------

HUGE THANKS to all donators! It really means a lot to me. You're awesome!!!

All authors of the included mods for their fantastic work. IMPORTANT: With this MO2 Installation, it's very easy to ENDORSE all the mods and their creators on Nexus, please do so! 

JaySerpa for terrific mods and for creating Gate to Sovngarde. This is just a humble conversion. It's still 90% JaySerpa's work.

All the users on JaySerpa's Discord that helped betatesting this conversion. You provided great feedback and helped me to find solutions for the issues this modlist had in the beginning.
