------------GIRL AND TRIANGLE GHOST TEMPLATE----------

If you've downloaded this ghost, you are interested in the art of ghost making! Or so I assume because this ghost has like no other dialogue otherwise. This ghost is set up to be a base for your ghost in the future! Much of the coding here will already be set up for you, all you will need to do is set up the images and write the dialogue for the most part. HOWEVER, this can still be complicated, so I recommend looking at the partner webpage I've set up as reference for this ghost!

http://www.ashido.com/ukagaka/

All the files in this ghost will have extensive commentary from me about how they work so hopefully you will not get lost, but the walkthrough page will have all the steps in order, as well as some that are not listed here for those who want to expand their ghosts or learn more about how they work. Be sure to keep it open or save a copy for reference! And make sure you read what I've written carefully!

I highly recommend using Notepad++ for editing your ghost files.



-----Update History-----

Ver 1.85 - Added clarification on balloon.directory in install.txt, added a line for balloon in descript.txt.
Ver 1.8 - Added some clarification about mikiretalk and also fixed the more specific time checks in OnMinuteChange in aitalk.dic.
Ver 1.7 - Added a thing about .pngs in etc.dic, removed some redundant functions related to timeslot in menu.dic, aitalk.dic, and bootend.dic.
Ver 1.6 - Rewrote and reorganized surfaces.txt and the read me for the shell, rewrote some directions and explanations in aitalk.dic, anchor.dic, bootend.dic, commu.dic, etc.dic, menu.dic, word.dic, added some links to string.dic, added a firstboot check for inputting your name and edited how it evaluates the input value in nameteach.dic.
Ver 1.5 - Rewrote commu.dic a bit more to break dialogue loops, fixed a passsec inconsistency, added a passhour check, redid mikiretalk so it activates faster, added a mouse click check for double clicking them, added a msglang english tag in their aya/yaya.txt so they'll work easier with the tama debugger, removed an unnecessary line in OnMouseMove, added an else and a check for installing calendar skins in OnInstallComplete, took out a redundant check in MenuRun, rewrote the section about how to do chains in aitalk, removed a redundant headline cancel function in menu.dic, removed OnSysResourcesLow since it doesn't work without a specific plug-in, changed the talkinterval length for five minutes, added a pronoun envelope for he's/she's/they're, changed OnUpdateReady so it displays the right number of new files, changed how setting the user's birthday works, added use_self_alpha to the shell and removed the pna files, added surfacetable.txt to the shell, fixed the incorrect name for OnVanishButtonHold. Big thanks to Zi for pointing out most of these things and redoing the birthday coding!
Ver 1.4 - Fixed the description for the alternate OnFirstBoot dialogue. Figured out what commu.dic does and rewrote the file accordingly.
Ver 1.3 - Moved surface.append to the end of surfaces.txt.
Ver 1.2 - Redid the description for OnUpdateFailure, added some details about desktop alignment in shell/descript.txt, rewrote a bit of surfaces.txt and added stuff about different cursors and tooltips, and shifted the template from AYA to YAYA (hopefully). If the YAYA version of the ghost doesn't work, I also cleaned up the mojibake in shiori3.dic in the AYA version.
Ver 1.1 - Minor typo fixes, caught a missing line of code in surfaces.txt.
Ver 1.0 - Template Release.


------How to Use this Ghost------


Right-click Girl to bring up the SSP right-click menu. 
Double-click Girl to bring up her own personal menu.
Double-click Triangle to bring up his menu.
You can pet Girl by stroking her head or face, and hit her by double-clicking her face. Likewise, you can pet Triangle by touching his face or point, and hit him by double clicking his face.

If you see underlined highlighted words, those are links to other conversations. More on that in the anchor.dic file.

You can force them to speak by hitting the "t" key, and you can reload them by going into the SSP menu, going to Utilities, then going to Reload Ghost. You can bring up the Developer Console by hitting Ctrl-Shift-D, although you may need to enable it first by going to Preferences, then checking "Enable Functions for Developers".
You can also force them to repeat what they just said by hitting the "r" key.


@> Much of the basic coding of this ghost was based on a ghost written by cindysuke, although they've since taken that ghost down or stored it, I'm not sure. Either way, I owe them a big debt because I would not have come this far in ghostmaking without studying their ghost! You can check out their stuff at cindysuke.deviantart.com.

@> My website in comparison is at http://www.ashido.com, and I'm also at zarla.livejournal.com or zarla.dreamwidth.org, and my tumblr is at zarla-s.tumblr.com. If you have questions or trouble, you can leave me comments on LJ or DW, or send me an email at Astronia@aol.com! I'll try to help if I can.


If you use my template, I'd appreciate a link back to my site or my lj or my tumblr or something. I'd love to see your ghost if you make one! I think these things are super cool and I'd love to see more of them.