I'm new to bitcoin and I'm here to fix it!

There are two types of people, those that know what they don't know and those that don't know what they don't know.

When I joined the bitcoin community, I was in the latter camp, and now I'm in the former camp.

So I've recently (past few months) became a bitcoin ossifcationist, 
because I don't think we should be making changes to the main chain without deep consideration of problems that can arise from making a small change.

Right now spam is a problem on bitcoin and it doesn't seem to be getting much attenion. This spam could have been avoided by more careful upgrades.

ALL future upgrades should probably be done on the 2nd layer, and let the main chain stay the way it is, except for critical bugs etc.

This is because bitcoin is not like regular software where we can roll back changes.

Upgrades that we make, will last forever. Imagine 1000 years from now the consequences of making a change that shouldn't have been done.

It will become more and more difficult the bigger it gets to do any kind of roll back.

The size of the database needs to be as small as possible to make sure as many full nodes exist as possible.

Bitcoin only needs to do one thing, and it needs to do it well.

It needs to be a secure way to store value, and nothing else. Keep the fancy upgrades to layer 2.

My 0.02.

----------------------
2025 Updates
----------------------

Check out Bitcoin Mechanic's latest video, I've been following him for years and what he says makes sense to me.

Bitcoin Core Actively Sabotaging Bitcoin:
https://www.youtube.com/watch?v=15biQH1H140&t=1s

More in depth video on the topic:
Roundtable_009 - If It’s Not Broken, Core Will Fix That
https://youtu.be/xc6aMxztle4?si=9dqzxb1eOVyJRV65

Latest video on the topic

Bitcoin Mechanic vs Peter Todd Debate | Bitcoin Core Node Changes
https://youtu.be/gbQvU-woY14?si=xvM76DRiNcvqR-cA

I'm with Mechanic on all this stuff, lets make Bitcoin money again, not a place to store jpgs.
Hopefully more poeple will realize this and make the switch to knots.

Best comment under the video:

Why is the one dude covering his face? 
Answer: He's is protecting his identity by using a physical filter. lol :D

Bitcoin Core Removes The Mask
https://www.youtube.com/watch?v=PaAjhhkFjU8

Btw, I need to make a distiction, when I was saying in my original post I was an ossifcationist except for crital bugs etc, I was talking about the bitcoin protocol, not the client side software which obviously needs updates!

As far as protocol stuff, perhaps there's a need for CTV but other than crital bugs after that I'm not seeing anything that's needed. I'm still not fully sold on CTV but if Mechanic is backing it I tend to side with him.

----------------------
Big Oppers (this could be the last major attack on bitcoin, an attack from the insde (core))
----------------------

Big oppers must be stopped! More info from Bitcoin Mechanic: https://www.youtube.com/watch?v=JLtmSzeLXOU

We aren't dealing with the big blockers in this attack, it's the big oppers this time, and it made it into the code! Hopefully people will come to their senses and revoke this change before it gets released. More info from Bitcoin University: https://youtu.be/JMpADC8YTB8?si=P8kadmP3Llz5nb8w

----------------------
Slowly winning the battle
----------------------

* Ocean's hash rate keeps going up around 15 Eh/s atm. 
* Jack Dorsey's minging rig is getting released soon or is already released (open source, open hardware) with swappable components.
* Bitcoin knots adoption is nearing 20%.

Future looks bright!

------
Ransom Insurance
------

I've heard that 1 or more copanies are looking ito providing ransom insurance for bitcoiners, I think this is a great idea!
If these companies can establish credibility, it would alleviate one of my main concerns with self custody.

The other main concern is my heirs barely being able to run a web browser which is something that's trickier to solve. But that's a unique problem for me not others.

In any event, I'm hoping the monetary maximalits (knots supporters) win, because Satoshi created 
a "peer to peer cash system", not a cloud storage database! I think Knots is around 23% now!

------
Everyone can choose to do what they wish, but I'm turning off my Knots node today before the Core V30 release and will not be running any node, due to legal and ethical reasons.
------


------
BIP 110 update and removing support for knots client
------

I find myself in a unique spot because I still don't support the op return uncapping that was done, but I also don't support BIP 110.

I feel like the damage was done in Core V30 and at this point there's no going back. Two options that I've considered...

1) Reducing the op return back to the original default 83 byte value in the Bitcoin reference client

The high op return default in the reference client is out in the wild in large numbers and at this point. Even if Bitcoin Core reverted the default back to the original 83 bytes, it would literally have zero effect at this point because of the staying power of older versions.

2) BIP 110

Adopting BIP 110 at this point isn't going to help  because spam/images etc can just be broken up into pieces bypassing the BIP 110 imposed limits. While it would increase the fees/headaches for spammers, but I don't think slight fee increase is worth doing a contentious soft fork.

In short at this point I don't think really anything can be done. Damage done is damage done and just have to live with it, no sense crying over spilled milk.

I think option 1 could still be done as a Bitcoin Core concession or admission that they screwed this up, but it wouldn't have any effect at this point.

I'm also removing my support for the knots client at this point because the BIP 110 and knots are one and the same at this point.


------
I'm glad I opposed Core V30, because I played a small role in stopping op return relay filter deprecation, but I also made a mistake
------

I'm glad I opposed the Core V30 release, because I played a small role in Bitcoin Core walking back their plan to deprecate the op return filter limit.

But I have to admit I made a mistake criticizing the rest of it because I changed my position on this and other than the deprecation, I can't offer any technical arguments why any of the other changes were a bad idea.

I can only say that the way that it was done could of been done differently to stop so many people from overblowing this. Perhaps better education videos or even making this change many many years ago, because the defaults were in place for so long it felt very reckless.

I want toThank Tone and Jonny for the last video because it filled in the some missing gaps for me and convincing me that this whole thing over the last 1-2 years is way overblown.

I think if Bitcoin Core could of done a better job with education or doing this release many many years ago to prevent so much backlash.

------
Final thoughts
------

I'm not even convinced at this point that the deprecation really matters.

When people say that they are trying to remove as many relay filters as possible it sounds really bad. It just sounds really bad.

But the consensus is the ultimate filter, it's really the only filter that matters. I think this could of been stressed more in the debates.

Relay filters don't matter I don't think, because there will always be work arounds. Except for perhaps relay filters for denial of service attacks etc.

My initial thought on all of this was that fees would eventually price out the spam, but I got sucked into the YouTube drama that convinced me to change my opinion, so I've changed my option back to my original one. Mistake made, lesson learned. Be careful of drama Youtube channels.

This stuff should of been known from the beginning. The way Bitcoin Core did this was backwards. Instead of adding relay filters that weren't needed then removing most of them, they should of never added them in the first place. Only adding the necessary ones. Keep it simple stupid. Just really bad engineering practice.

Over complicating the Bitcoin reference client lead a lot of this drama in the first place which could of been avoided. 

KISS

------
Biggest reason I got the call on op return relay limit filter removal wronng
------

I think the biggest reason why I got this call wrong was because I gave the earlier Bitcoin Core developers TOO much credit. 

If workarounds can always be done, breaking up spam into smaller pieces etc, why was there a data carrier size limit put in to begin with in 2014 when the OP RETURN code was standardized in the Bitcoin Core reference client?

I felt surely there there was a reason for it, but apparently not, which is just pure insanity. Clearly there has to be a reason for them to put it in , in the first place, apparently not. 😮

It's really a lesson that you can never rely on experts or past experts on anything, which is something that I already know, but just assumed that didn't apply it to Bitcoin because I was so sure these guys knew what they were doing. 

Lesson, always come to your own independent conclusion on everything, never relying on experts or past experts to formulate your opinion.


------
Firmly Against BIP 110, Feb 3, 2026
------

I'm firmly against BIP 110, because fragmented spam isn't any better than unfragmented spam 

------
I gave Bitcoin Core too much fucking credit
------

I was against the V30 release because I gave Bitcoin Core (early devs around 2014) enough fucking credit to not include a future (data carrier size), that's literally completely useless.

I didn't even look into that as a fucking possibility. 

And I got the call wrong because of it, but I'm not going to blame them, I still blame myself for overlooking this but damn, I'm still in shock about this. 😂

------
There's 3 irony's here
------

1) In 2014 the Core Devs add a useless feature to the Bitcoin Core client (data carrier size)

2) In 2025 there's a big rebellion because Bitcoin Core tries to remove this useless feature

3) The soft fork chain that is rebelling against the useless feature removal will end up being flooded with spam that this useless feature will not prevent

This Idocracy movie is too much sometimes. But one that that appears to be the most reliable is the most ironic outcome is usually the most likely
