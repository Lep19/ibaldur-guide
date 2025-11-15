# Intro
## How it Works
We can only hit the Baldur when it's open, but if we just walk up to it it'll close before we can reach it with our nail.

![nail slash only](https://github.com/user-attachments/assets/ff450522-78f6-44f6-afe5-1c0fbecf7640)

It can only close if it's fully open, so if we re-enter its range while it's still in the opening animation we can delay its close. This still doesn't quite give us enough time to reach it, though.

![nail slash with wiggle](https://github.com/user-attachments/assets/c24fa945-86f4-4eba-9d75-cf86f923cce2)

BUT, damage knockback moves us faster than normal walking, and that extra speed plus the delayed close gets us there just in time to land a hit. We can even fit a second hit in since the first hit causes the Baldur to recoil.

![slashes](https://github.com/user-attachments/assets/1a118038-a09a-44a5-a405-f410f391e879)

### So, our setup will need:
- A cue for when the Shade is close enough to hit us at the right time
- What we'll call a "wiggle" to time the Baldur's opening and closing
- A cue for where to stand when we get hit so we enter the Baldur's range correctly
- A well timed nail slash

This trick is generally more lenient at higher FPS. 300+ is ideal, but you shouldn't see much difference in the 200-300 FPS range, so cap to whatever you can stay at consistently.

We'll also be talking about health/soul management and healing setups since most categories will use Fury of the Fallen, but of course you can disregard those parts if you're not. On that note, you can enter with less health and soul than I'll be showing, and you can greed the heals more if you like, but I'll be showing what I consider to be the most reliable health management that allows for a few failed rotations and doesn't risk getting hit with a spit while you're healing. Keep an eye on current, active runners for the most up-to-date strats.

And, as a final note, we'll be using [Staxis's practice mod](https://github.com/staxissr/ibaldurPractice/releases) to understand and diagnose our attempts later. I'll also link [this](https://www.youtube.com/watch?v=cg7sH7FyAK0&list=PLH-aXtMsmPYq8ZvwV9G7s3uIz_6AlIygz&index=1) guide on how to downpatch and set up mods if you need it.

# Doing the Trick
## Setting Up
Enter the room with 4 health and at least 5 hits of soul to allow for a max of 2 missed rotations. You can enter with as little as 3 health and no soul or 2 health and 3 soul, but this isn't recommended until you're very confident in the trick/aren't willing to continue a run with missed rotations.

Walk into the room and do a full jump as you pass the marked point on this sign. You should land on the right edge of the little platform and be able to walk under the Shade.

![sign](https://github.com/user-attachments/assets/53303f74-e142-49f4-9719-e5a9018b73eb)


![jump under shade](https://github.com/user-attachments/assets/6108d1fb-2e39-4d08-b0c9-746bf8a16e70)

For the rest of this guide, we'll be referencing these 3 marks on the ground often. I've given them colors to make them easier to point out (for colorblind folks, they're red, green, and blue from left to right).

![rgb](https://github.com/user-attachments/assets/d1622247-abad-4218-a3b3-69795ee2b1fc)

Walk towards the Baldur and stop between the red and green marks. When you pass the green mark, the Baldur should close, giving you a safe place to wait for the Shade.

![first baldur close](https://github.com/user-attachments/assets/8d32685d-ed9d-4ca2-bca0-f3716f25c470)


## Damage Rotation
Wait for the Shade to hover close enough to you so that this pole in the back is between its horns/behind its head.

![pole](https://github.com/user-attachments/assets/f5872eb0-57af-4250-8d52-ff32f6d5e55b)

<img width="388" height="318" alt="shade in front of pole" src="https://github.com/user-attachments/assets/39fb1dde-3770-402f-8019-a2f271008d28" />

Once it is, perform the wiggle:
- Walk right until you reach the blue mark, then turn around. The shade should make the aggro sound and start attacking
- Walk left until you pass the green mark, then turn around somewhere between the red and green marks
- Walk right back to the blue mark and wait to get hit

![wiggle](https://github.com/user-attachments/assets/744312d1-d1b2-41bf-89c6-3117101963c1)

  
At this point, the Shade should hit you. During the freeze from the damage, start holding left and time a nail slash just as you turn around out of the damage. Buffer a second slash to hit it during its recoil.

![slashes](https://github.com/user-attachments/assets/e375f15c-4b3c-48ba-a962-c7cf2cb38cc9)


## Luring the Shade Away
After the second slash, turn back around. If you're above 2 health, run back into the right side of the Shade to damage tank down to 2 health.

![shade extra damage](https://github.com/user-attachments/assets/e779073f-ae37-4516-84d0-204c50104ab2)

Otherwise, do a small hop over the Shade. This will prevent it from swinging at you too early, which will speed up the lure.

![shade hop](https://github.com/user-attachments/assets/e3b9f9c3-faf9-482b-9404-af79282fb765)

If you're on exactly 2 health, walk until you reach the corner and wait for the Shade to attack, then jump over it and head back. You can jump to avoid spits if they're going to hit you, in which case you can go under the Shade.

![corner](https://github.com/user-attachments/assets/24341495-fc22-4c7f-84b9-04c966210b15)

If you're on 1 health, do a small jump over the ledge and heal around the middle of the platform. To optimize this, you can start holding the heal button as you pass this marked pole, and the heal delay will end right as you get into position. You'll then need to quickly jump over the Shade to avoid its attack.

![heal pole](https://github.com/user-attachments/assets/1b006e30-c26e-4a4f-a83c-15d7dc0580b3)

![corner](https://github.com/user-attachments/assets/7cd5ca47-cb28-4c26-a399-004595505d43)

From there, just repeat for 3 more pairs of hits on the Baldur. After the last hit, if you need the geo, you can either take a slight step back to collect some of it, or jump as it appears to catch it.

![baldur geo jump](https://github.com/user-attachments/assets/5b8b2751-9566-4d96-abcc-05fefaeb431c)

# Understanding the Practice Mod
If you've installed Staxis's mod, you'll see a bunch of numbers show up in the top right after each attempt. Let's discuss them a bit. This whole section will be pulled directly from [this](https://discord.com/channels/772964112908156938/1328843639983571055/1356770491813068891) post from Staxis.

## Terminology
NOTE: "physics frames" refer to the game's internal framerate rather than your graphics framerate, which is locked to 50 FPS.
- **Left Range**: how many physics frames between when you left the Baldur's range and when the Shade started to attack
- **Shade Attack**: used to mark when the Shade attack was relative to the other numbers
- **Hit Pos**: your position when you took damage from the Shade
- **Slash Delay**: how many physics frames between when you took damage and when you attacked
- **Wiggle Duration**: how many physics frames between when you left and when you reentered the Baldur's range
- **Earliest Possible Re-entry**: how many physics frames earlier you could have reentered the baldur's range after being hit. A negative number means you could have entered earlier, while a positive number means the baldur won't reopen at all and you needed to go that many frames later. This number is offset by 1, however; 0 means you needed to enter 1 frame later for the baldur to reopen, while -1 means you entered the first possible frame
- **RNG Late Attack**: whether the Shade's RNG attack delay caused a late attack
- **Y-Pos Late Attack**: whether the Shade's vertical bobbing caused a late attack

## What Values to Aim For
NOTE: these values will vary slightly depending on FPS and how other parts of the setup were executed. The ones provided here are expected to work most of the time at 250+ FPS. The value in parentheses represents the "ideal" value for diagnosing cases that seem like they should've worked.
- **Left Range**: 4 to 6 (5)
- **Shade Attack**: t-0
- **Hit Pos**: 82.5 to 83 (82.7ish)
- **Slash Delay**: 13 to 15 (13)
- **Wiggle Duration**: 7 to 13
- **Earliest Possible Re-entry**: -3 to -1 (-1)
- **RNG Late Attack**: No
- **Y-Pos Late Attack**: No

## Using These Values
- If your Left Range is much more than 5, allow the Shade to get closer before starting your wiggle. If it's much less, start the wiggle sooner
- If your Hit Pos is much less than 82.5, move further to the right before getting hit. If it's much more than 83, stop further left
- If your Slash Delay is less than 13, slash later after the Shade hits you. If it's more than 15, slash sooner
- If you got an RNG Late Attack, you likely greeded the Shade lure more than what was described here
- If you got a Y-Pos Late Attack, get owned. At this time we don't have a way to reliably avoid this

# Tips for Improvement
- When you're first starting out, you may need to work on turning around and stopping at precise spots. This is very important for the success of this trick and takes a fair bit of familiarity with playing the game to get used to, so it may be worth practicing the wiggle on its own without any enemies
- For practice with enemies, consider using Debug Mod's "infinite health" cheats for yourself and for the Baldur and Shade. This will let you do repeated attempts without having to reload a savestate or worry about health management
- When first attempting rotations, the practice mod is very efficient for diagnosing problems. Compare your numbers with the ones above, and you should have a pretty good idea of what most likely went wrong
- As you practice, try to hone in on the rhythms of the trick so you can guess what went wrong before you see the numbers. This will become an increasingly important skill as you start to attempt the trick in actual runs. [Here's](https://www.youtube.com/watch?v=OXQDG_dI8n0) a video of HypoCritical doing that type of diagnosing
