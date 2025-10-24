# Summary
### How it Works
- We can only hit the Baldur when it's open, but if we just walk up to it it'll close before we can reach it with our nail
Clip of normal walking up
- It can only close if it's fully open, so if we re-enter its range while it's still in the opening animation it'll delay its close. This still doesn't quite give us enough time to reach it
Clip of wiggle with no damage
- BUT, damage knockback moves us faster than normal walking, and that extra speed plus the delayed close gets us there just in time to land a hit. We can even fit a second hit in since the first hit causes the Baldur to recoil
Clip of successful rotation

### So, our setup will need:
- A cue for when the Shade is close enough to hit us at the right time
- What we'll call a "wiggle" to time the Baldur's opening and closing
- A cue for where to stand when we get hit so we enter the Baldur's range correctly
- A well timed nail slash

This trick is generally more lenient at higher FPS. 300+ is ideal, but you shouldn't see much difference in the 200-300 FPS range, so cap to whatever you can stay at consistently.

We'll also be talking about health/soul management and healing setups since most categories will use Fury of the Fallen, but of course you can disregard those parts if you're not. On that note, you can enter with less health and soul than I'll be showing, and you can greed the heals more if you like, but I'll be showing what I consider to be the most reliable health management that allows for a few failed rotations and doesn't risk getting hit with a spit while you're healing. Keep an eye on current, active runners for the most up-to-date strats.

And, as a final note, we'll be using [Staxis's practice mod](https://github.com/staxissr/ibaldurPractice/releases) to understand and diagnose our attempts later. I'll also link [this](https://www.youtube.com/watch?v=cg7sH7FyAK0&list=PLH-aXtMsmPYq8ZvwV9G7s3uIz_6AlIygz&index=1) guide on how to downpatch and set up mods if you need it.

# How to do It
### Setting Up
- Enter the room with 4 health and at least 5 hits of soul. This will allow for a max of 2 missed rotations
- Walk into the room and do a full jump as you pass this point on the sign. You should land on the right edge of this platform and be able to walk under the shade
- For the rest of the trick, we'll be referencing these 3 marks on the ground by their color
- Walk all the way between the red and green marks. When you pass the green mark, the Baldur should close, giving us a safe place to wait for the Shade

### Damage Rotation
- Wait for the Shade to hover close enough to you so that this pole in the back is between its horns
- Once it is, perform the wiggle
    - Walk right until you reach the blue mark, then turn around. The shade should make the aggro sound and start attacking
    - Walk left until you pass the green mark, then turn around somewhere between the red and green marks
    - Walk right back to blue mark and wait to get hit
- At this point, the Shade should hit you. During the freeze from the damage, start holding left
- Time a nail slash to just barely hit the Baldur from as far as you can. Buffer a second slash to hit it during its recoil

### Luring the Shade Away
- After the second slash, turn back around
    - If you're above 2 health, run back into the right side of the Shade to damage tank down to 2 health
    - Otherwise, do a small hop over the Shade. This will prevent it from swinging at you early which will speed up the lure
- If you're on exactly 2 health, walk until you reach the corner and wait for the Shade to attack. You can jump to avoid spits if they're going to hit you
- If you're on 1 health, do a small jump over the ledge and heal around the middle of the platform. To optimize this, you can start holding the heal button as you pass this marked pole, and the heal delay will end right as you get into position
- Once the Shade begins to attack, simply jump over and head back toward the Baldur. If you had to jump to avoid a spit, you can also go under the Shade

From there, just repeat for 3 more pairs of hits on the Baldur. After the last hit, if you need the geo, you can either take a slight step back to collect some of it, or jump as it appears to catch it.

# Understanding the Practice Mod
If you've installed Staxis's mod, you'll see a bunch of numbers show up in the top right after each attempt. Let's discuss them a bit. This whole section will be pulled directly from [this](https://discord.com/channels/772964112908156938/1328843639983571055/1356770491813068891) post from Staxis.

### Terminology
NOTE: "physics frames" refers to the game's internal framerate rather than your graphics framerate, which is locked to 50 FPS.
- **Left Range**: how many physics frames between when you left the Baldur's range and when the Shade started to attack
- **Hit Pos**: your position when you took damage from the Shade
- **Slash Delay**: how many physics frames between when you took damage and when you attacked
- **Wiggle Duration**: how many physics frames between when you left and when you reentered the Baldur's range
- **Earliest Possible Re-entry**: how many physics frames earlier you could have reentered the baldur's range after being hit. A negative number means you could have entered earlier, while a positive number means the baldur won't reopen at all and you needed to go that many frames later. This number is offset by 1, however; 0 means you needed to enter 1 frame later for the baldur to reopen, while -1 means you entered the first possible frame
- **RNG Late Attack**: whether the Shade's RNG attack delay caused a late attack
- **Y-Pos Late Attack**: whether the Shade's vertical bobbing caused a late attack

### What Values to Aim For
NOTE: these values will vary slightly depending on FPS and how other parts of the setup were executed. The ones provided here are expected to work at 250+ FPS.
- **Left Range**: 4 to 6
- **Hit Pos**: 82.5 to 83
- **Slash Delay**: 13 to 15
- **Wiggle Duration**: 7 to 13
- **Earliest Possible Re-entry**: -3 to -1
- **RNG Late Attack**: No
- **Y-Pos Late Attack**: No

### Using These Values
- If your Left Range is much more than 5, allow the Shade to get closer before starting your wiggle. If it's much less, start the wiggle sooner
- If your Hit Pos is much less than 82.5, move further to the right before getting hit. If it's much more than 83, stop further left
- If your Slash Delay is less than 13, slash later after the Shade hits you. If it's more than 15, slash sooner
- If you got an RNG Late Attack, you likely greeded the Shade lure more than what was described here
- If you got a Y-Pos Late Attack, get owned. At this time we don't have a way to reliably avoid this
