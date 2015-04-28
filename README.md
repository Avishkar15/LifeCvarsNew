LifeCvars
=========

Stores the global config files for the Life GMod addon.


In the interest of keeping this part of the addon as "open" as possible, this repository is where we will keep the main configuration file that defines all of the console commands that we run in Life.

There are three reasons for this:
1. it means that the list of commands is not locked away inside the GMA and you can read it whenever you want, just to make sure we aren't doing anything bad.
2. it means that we can't change the list without a commit message being stored, and you can look through every revision of the file to know that we didn't do something bad.
3. it means that we don't have to update the workshop addon each time we want to tweak this list.

FAQ
=========

Q.: What happens if I am offline? Will Life still work?

A:Yes. As long as you are online the first time you start a game with Life installed, Life will cache a local copy of this file that it will fall back to if you don't have a network connection or if the GitHub repository becomes in-accessible for whatever reason. 

Q: My GMod is broken and it's your fault!

A: First off, you chose to use this feature even though we warned you, so that's your problem. However, 
Life Mod maintains a backup of your convars. Just go into the Life Mod panel and then press the red button that says "RESTORE" to restore the values back to the way they were when you installed Life. 

Q: How do we know what these commands do? Can they harm my computer?

A: You know as much as we do. Search the internet. The Valve Developer Wiki is where we looked for descriptions. If they harm your computer, it's your fault for ignoring our warnings. We did try to tell you that this might lag the heck out of your pc eitherways. 

Q: Is it Client-Side/Server-Side Addon?

A: "Client-side": Yes, it is a client-side addon but don't expect to run on any server you go 
if the server doeshn't have it.But it can be used if the server has sv_allowcslua set to 1 or else it won't work. 

"Server-Side": Yes,it does supports Server-Side.You can enable them by clicking on the gold boxes that are next to the specific modifications. The color/bloom/vignette/cinematic/masks stuff are implented already to work without to click a box for them. 

Q: What kind of PC do i need to run Life mod?

A: A Medium/High (2010+ year pc) end pc will work it out. Now if you have a toaster PC,use only the Basics tab or else the advanced options(that are the other tabs),may harm your pc.Use them with CAUTION if so!!. 

Q: On my game, everything is really bright with its modifiers, turn them down please?

A:Okay thats not my problem that is bright. To my game its not bright at all.The reason why its bright to you its because you have enabled your Monitors Gamma. Life Mod has this option on the "Others tab" which you can turn it off and on whenever you want. 
