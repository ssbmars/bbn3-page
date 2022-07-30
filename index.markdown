---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

[![Tango link](bbn3gettango.png)](https://tangobattle.com/){:target="_blank"}

BBN3 is a balance patch for Megaman Battle Network 3 Blue. There are changes at every level, from individual chips to universal engine mechanics. Its goal is to make pvp accessible, fun, and interactive.

Download the Tango client to play BBN3 today! Tango provides rollback netcode for all Battle Network games, and patches such as BBN3 come bundled with Tango by default. Just import a valid BN3 Blue ROM and SAVE, then choose BBN3 from the "Patch" dropdown.


<iframe width="480" height="320" src="https://www.youtube.com/embed/uHcGD015Gqw" title="YouTube Video" frameborder="0" allow="encrypted-media;"></iframe>


## How to Play Online
Install Tango to play online with rollback netcode! 
Patches are downloaded and managed automatically by Tango. Simply load BN3 Blue and then select BBBN3 from the "Patch" dropdown menu before starting the netbattle. No manual patching is required.
https://tangobattle.com

## Download for Singleplayer and Other PvP Methods
[![Download link](bbn3downloadimage.png)](https://github.com/ssbmars/BBN3/releases/download/Latest/BBN3.Latest.zip)

## FAQ
Q: Can I play through the singleplayer story with this patch?  
A: You need to use the singleplayer version of this patch in order to play through the story. The singleplayer patch is included with the main download. Note: the singleplayer patch is intended only for playing through the story. It is not balanced for pvp and will not provide a good pvp experience.

Q: I'm playing through the singleplayer version and collected a RegUp, but my Reg Memory has not increased at all. Is it stuck at 2MB?  
A: Your Regular Memory is calculated differently. It begins at 2MB and caps at 5MB. Each RegUp you collect brings you closer to your next RegMem increase, but each increase requires multiple RegUp pieces before you see any effect. The Reg+ NCPs will increase your RegMem by +1 each, up to a max of 8MB.
 
Q: Is there still a ruleset for pvp matches?  
A: Anything the game allows you to do is legal in pvp.
For things outside of the game: 
- Do not use cheat codes.
- Do not use autofire controller inputs.
- Do not purposely disconnect or attempt to cause desyncs mid-match.

Q: Are we really allowed to use the minibomb folder in pvp matches?  
A: Not only is it allowed, it's encouraged.

## How to Manually Apply Patch 
1. Download and unzip the BBN3 folder. [It can be manually downloaded here.](https://github.com/ssbmars/BBN3/releases/download/Latest/BBN3.Latest.zip)  
2. Launch the included flips.exe program. Choose the "Apply Patch" button. Select BBN3.bps, then locate and select your vanilla BN3 Blue ROM. When prompted, save the new rom file as "BBN3.gba". 
3. BBN3.gba is now ready to be played in an emulator. A pvp-ready save file will be generated when you choose NEW GAME.  

NOTE:  
Make sure you legally aquired your ROM by dumping a clean copy of the English US version of BN3 Blue. Downloading a copy from the internet is illegal and insecure. The majority of rom sites today primarily distribute malware instead of actual roms. 
The included patching software will verify whether your BN3 Blue rom is clean before it applies the patch.  
The correct MD5 hash for an unmodified US BN3 Blue ROM is:  
```6fe31df0144759b34ad666badaacc442```  
You can check the hash of your ROM file by using this online tool:  
[https://emn178.github.io/online-tools/md5_checksum.html](https://emn178.github.io/online-tools/md5_checksum.html)

## Acknowledgements
### The following people contributed to the project in a notable way:
Prof. 9 - Provided TextPet, a very nice text replacement tool.  He also explained plenty of ASM concepts and introduced me to the ARMIPS compiler. In addition, a modified version of the source code from Prof. 9's BN3Plus patch is included in BBN3.
[https://github.com/Prof9/TextPet](https://github.com/Prof9/TextPet) 

X Kirby and NMarkro - They created the Open Mode patch for BN3, the code for which is also used in BBN3 to achieve the pvp-ready gamestate without a save file. This is a huge feature that wouldn't have been possible without their work.
BN3 Randomizer by X Kirby
TeamBN Discord

Mgamerz - He published the documentation from his research into BN3 and was releasing intriguing patches long before BBN3 was conceived of. Notably, he was the first to discover the panel ownership data and create the modified version of Grab Revenge that returns stolen panels. The Grab Revenge code in BBN3 is sourced directly from his patch. As if that wasn't enough, he also wrote the beginner's guide to ASM Modding for Battle Network. To this day I recommend this same tutorial to anyone who asks me how to get started. It teaches you what ASM modding truly looks like, and most importantly it teaches you how to learn on your own. I can't overstate how helpful this tutorial is. 
GrabRevenge Showcase Video
Mgamerz's patch pastebin

The Spanish translated version of BBN3 exists thanks to the hard work of the MNTWFL Translations group, who created and released a full Spanish translation of BN3. Additional info about this group can be found at: [https://www.romhacking.net/community/4853](https://www.romhacking.net/community/4853)
Additional Spanish translations are provided by the community members in the NetSaviors Discord server.
