---
publish: true
created: 2026-07-21T14:41:06.194+02:00
modified: 2026-07-22T01:05:26.160+02:00
---

- 1&2: Neve preamp (tge british)
- 3&4: Api 312 (the american)
- 5&6: the polish preamps

Mic & instrument level need preamp -> to line level. everything plugged in becomes line level to ensure uniformity in signal levels.

Balanced / unbalanced:

- TRS is unbalanced
- XLR is balanced

Use Patch bay to connect/route everything in the console. Inputs, outputs, compressors, saturators.

Di box: instrument level to line level. Unbalanced to balanced. I.e. guitar/bass ⟶ into Di box ⟶ into preamp

Reamp box: changes balanced high impedance to unbalanced. Balanced to unbalanced. So if you have a dry signal recorded and want to send it through a amp for example to record that use a Reamping box.

Protools:
Use aux channels like sends in ableton
In pro tools it's all about the routing via  I / O. sending to other channels via busses etc.

when mixing:

# Miking / recording

## Drums

- **Drums 3 mic setup (glyn johns setup)**
  One kick mic. 2 overhead. Main overhead three sticks above the snare. Then one diagonally down at the biggest tom. Both OH always same distance from the snare. can us moongel on each drum to make them ring less. thin kitchen towel on snare i like. Using a glynn johns setup is better if other instruments are also in the room (less bleed)

- **4 mic setup**
  same as with 3 but with an extra mic like the sm57 3 fingers above the snare rim. Go down for more snap, go up for less. you might need to invert the polarity. If theres a drastic drop of low end, theres a polarity issue, just invert the track

- **Sausage mic**
  using a sausage mic if you dont have many mics is good cuz it captures a lot. if you have enough mics you can compress/saturate/distort the living shit out of the sausage mic to mix in some more flavor into the overall sound. it doesnt pick up much from the cymbals so its great for coloring snare, toms & kick.

- XY pencil mic setup above the snare as overheads also possible, gives more snare presence but at that point could also just add a bottom snare mic

- use a gate to eliminate bleed on drums
  on snare mic for example to just get snare and no reverb/other sound. For like and 80s snare put a reverb on it then a gate on that

- Use a drum trigger plugin like drumxchanger or something. with this you can layer drum samples on top of your prerecorded drums. you could also manually place every sample throughout the song but if the drums arent a consistent loop it gets very time consuming

**Drum Mics we used**
kick - an egg mic (d112) apparently re20 sounds good on kicks too (its also good for bass amps)
OH - mic like akg c414, we’ve also used tbone RB 500 ribbon mics, coles 4038
Snare - sm57 for top and bottom
Sausage mic - beyerdynamic m160, a sm57 will work for this if pointed towards the middle of snare with more or less same distance from snare head, tom heads and kick beater

All plugins are designed to work with audio that peaks at -6 db

## Piano

Coldplay uses 2 sm57
Open up the piano (make it naked)
2 sm57 at the top pointing down into the piano / can also be little diagonally pointed 
Put them kinda close.
Mics can not be pointed towards each other cuz of phasing issues.
Closer = brighter, further away = more room + darker. If you want even darker use ribbon mics

Can also point them little above hammers facing towards the piano wall kinda horizontally (not coldplay style). 

When writing songs it's all about octave separation. If the guitar and piano are staying in the same octave all the time shit gets muddy. Use a frequency chart. 

## Acoustic guitar

The 12th fret is where guitar is most resonant
Option1: put a sm57 or pencil mic pointing at the 12th fret of the guitar like 2 feet away 
Option2: 2 Small Condenser Mic's in XY position a little further away than in option 1. then pan one left and right to taste.

## Bass

When using an amp:
Mic pointing circa 45° angle towards the glue between dust cap and cone on the bass amp using a high spl mic like re20

its good to have a dry signal and a wet signal ⟶ use Di box, one straight to preamp, one to amp which is recorded with mic which is sent separate channel

If you don't have a bass amp nothing wrong with a amp emulator to do the same

## cello

It lies in the same frequency area where the human voice is so vocal mics could sound good (u87, akg 414, or a ribbon mic)

Single cardioid mic pointing at the f-holes 3-4ft away. Move it a little down so we don't get too much muddyness? also try setting the LDC to omni for more natural sound if thats the only instrument in the room.

For finding good mic placement especially for acoustic stuff:
Moving your head around while the instrument plays and listening to the sound of the instrument from different positions with one ear to decide on where the best tone is to position the mic. Looks silly, but hella effective apparently

## Vocals

Tube mic for female vocal
MJ used sm7b
taylor swift the Avantone Pro CV-12 (clone of AKG C 12)

Use hand to make elephant from noseto place mic properly. Angle more towards chest for more bass, more up for more high end (but also gets mouth sounds). Always use a pop filter.

## Stuff like trumpets / horns

Figure 8 mic
Ribbon mics good since trumpets can be bright & harsh

## For percussion, shakers, etc

Omni mic 

## Guitar

Guitar amps: we used beyerdynamic ribbon mic + sm57.
really just a well placed sm57 is all you need

Blue sky pedal (has cool effects for everything guitar, drums, etc)

Tube screamer is a must on guitar so it doesnt dissapear when all other instruments are playing (can use multiple. get them cheap they all sound the same)

Digital chorus sucks compared to analog (at least on guitar apparently) so use pedal / amp with builtin chorus

Use an e-bow for cool effect they're all identical get them cheap

## When recording

1st take just listen to the song

2nd take mess around find what you want to play

3rd take play & record

Shift + option + 3 to consolidate clips (protools)

Set drop-down of track to playlist and then record. 
To record new take click new playlist and record the 2nd take. Rinse and repeat. USE GROUPS so that this is done on all the tracks/mics. Also use groups to arm multiple tracks at the same time for recording (e.g. arm all drum tracks for recording)

# Compression

optical tube compressors like LA-2A tube compressor are slow, unlike FET compressors, so not good for quick punchy stuff like drums but they add tone and have a glue like quality for stuff like vocals, bass. opto compressors are good for smoothing/rounding.

VCA and FET are both fast but VCA is more transparent while FET adds more color. Because they are fast anything with transients works better with these types than tube compressors.

On 1176 compressor you can press all ratio buttons so it begins to work as distortion (use it as a parallel send)

Limiter is just a compressor with very high ratio

Slow attacks fast release makes it it more snap since it doesn't do anything to the first transients

essentially compressors set a upper threshold for how loud the signal (the transients) can be. if it goes over the threshold it becomes compressed by given ratio. the ratio determines the amount of compression/ or how much is let through after threshold is exceeded
![[attachments/Pasted image 20260721173148.png|366]]
The attack on a compressor is how quickly the compressor will react to the signal crossing the threshold. e.g. if you compress drums you want attack to be slower so the first transients of the drums isnt compressed, which would make it sound less punchy.
The release is then how fast the compressor reacts to the signal dipping below the threshold again.

Doing this essentially squishes the sound together. the dynamic range is lessened. Thats why theres a ‘gain/makeup gain/output’ knob that makes the hole signal louder again after the compression. so now the whole dynamic range of what is being compressed is lower so if you match the output gain to the input gain. it will feel louder/more present despite teh actual Dbs being the same

# In the Box after recording

Aim for ~ -10 db on the master before proper mixing / mastering

## Vocals

Always cut off all the noisy breath and lip smacks out of the vocal. If you keep them they'll become louder after the compression etc. if you want to keep some breaths reduce the gain on that part via automation 

keep vocals more or less in center cuz its typically what takes center stage (in most songs)

Normally compression ratio for vocal is like 2:1 or 3:1

To put vocals more in front use slow attack and short release

FET works well in vocals

You can use multiple compressors. Like on vocals first a FET to tame transients make consonants more present then put a opto/tube compressor which is slower = rounder sound

On vocal u can use a spreader by using a pitch shifter (soundtoys microshift) only works on stereo track

A de-esser is just a compressor with a fixed attack, fixed release and ratio, you just set the frequency and it lessens sibilance 

Can use a tape delay on vocals. Can also use mono spring reverb on vocals. Can also add little bit of flanger.

You can duplicate the tracks. One clean one with compression then mix them together

## Drums

First check that everything is in phase. you can invert phase with any eq plugin. shift the OH tracks etc over so they match with the snare hit. if using top & bot snare mic they props be in opposite phase

Route all drums to a aux track. roughly mix and match the volumes with the track gain, dont use the faders yet, use them later when making small adjustments later down the road.

Ensure that kick and snare stay in the centre. this also means you cant just crank the OHs to each side since they also pick up some of the kick and snare

glue all the drum tracks together with something like vca compressor (the ableton glue compressor is a vca comp Ssl bus compressor is also just vca type compressor). only after all drums have been glued together should you touch individual drum tracks with eq or compression etc.

On snare u can use a fet compressor (1176)

You can send kick and snare to a parallel track and add saturation using decapacitator (soundtoys). Makes it sound more fat

## Bass

First check phase (if using Di & Amp)
Use the di signal for the subbass use a eq to only get that lower end and put a limiter on it. if you want use a subharmonic plugin to get the subwoofers going

The bass amp track use the opposite, use this to get the high end, so basically the opposite eq to that of the di signal. U can saturate/distort this to taste. This way only the highs are distorted and the subbass stay clean. then send both to a aux track and put compression/whatever on the aux track

tube compression (La2a) is good for bass cuz it's slower so bass sounds rounder/fuller

bass always in the center/ mono

## Guitar

kinda just do what sounds good idk. compression eq and tape delay? Plate verb works well for guitar?

# Mixing

## Preparation

Organize & color code everything before mixing. Do not mix after 4pm. Mix when you get up early, when your ears are fresh and work quickly. Most pro mixing engineers will finish a track in 4-5h. Soloing is the enemy. The only thing that matters is how it sounds in context. Every morning you wake up your ears will be different so you can listen to something that sounds good to calibrate them. Don't mix loud. Mix quiet. It's gotta punch at low volume, it'll always punch at high volume anyway. Always mix at the same level. Always record at the same level. You mix only with busses and groups you don't touch the individual channels. Only after you've mixed you should tweak the individual tracks (snare, kick, etc). 

## Mixing

Bass in center kick in center snare in center all else pan around it. Then if vocal is main thing center that also 

Aim for -15 / -18 db. Especially for everything in the midrange. Drums are very dynamic and should be louder like more towards 0 cuz they're essentially very short transients that need to stick out in the mix

Use gate to isolat other noise.

Everything below 80hz that isn't bass/kick/intentional low end stuff get rid of it. Everything inhabits it's own frequency so every eq is just a piano. Use cheapo piano to find what notes (I.e. what frequencies) are clashing so you know what to eq out.
always eq with smaller dips.

Important frequencies for snare: 200hz, 4k hz, 700 ~ 1k hz

Snare and vocals often clash at around 200hz. when low mids are muddy start dipping the elements at those frequency ranges. if you dont dip vocals in the low mids you dip the guitar in the low mids. one has to dictate, both cant at teh same time. A good song will not have this issue as much. its an arrangement issue at its core. Write better songs

<iframe src="https://www.theabsolutesound.com/freqchart/main_display.htm" style="width: auto; height: 700px; aspect-ratio: 8 / 7; transform-origin: top left; scale: 0.7; margin-bottom: -200px;"></iframe>

> [!NOTE]- Frequency Charts
> ![[attachments/Freq-Chart.jpg]]
> ![[attachments/Pasted image 20260721232329.png]]

Eq before compressor to tame aggressive frequencies, eq after compressor tunes more of the overall tone

Tape saturation to roll off the piercing sounds an instrument

Try using transient shaper on the OH in parallele

You can boost the snap of the kick to match the snap of the  fingers on the bass 

When you have stuff with high frequencies (stuff like percussion) going through verb it can sound artificial. Add low pass filter before the verb. Stuff like percussion can inhabit similar frequencies as rides etc, so pan it to wherever there is less stuff going on

You can create a send for everything that isn't main vox, bass, kick or other low end and conpress them glue them together with parallel compression 

Drums & vocals need to connect. both should be grooving & not clashing. People hear groove first, then melody, then the words. they should inhabit their own frequency ranges

U can use plugins in multi mono mode so effect is only on left or right side of signal. Like for a small slap delay or tape delay on only right channel of a guitar

# Mastering

**Mastering with ozone:**
When mastering only use the ozone stabilizer. U want a ceiling at -1 db. (To work with streaming services). Officially spotify wants -14 lufs but aiming for -8 or -9 lufs

**Mastering without ozone:**
**Work backwards through the mastering chain**:
\[the End of the mastering chain]

- Start with a limiter to set a threshold that the level will never go over. The limiter will be the last thing in the chain. ceiling of -1 dBTP (true peak) find the threshold where sounds best

- Use a glue compressor to bind everything together

- Use eq but set it to mid/side (m/s) so there's mono in the middle and the left and right sides. Bass, kick all those low frequencies stay only in middle. Remove those from the sides and boost the nice frequencies in the mid a little (like vox).

- Often the stuff in the low mids is stuffy eq that out in stereo so it's less in mid and side.

- Boost the verbs in the sides with a shelf (higher frequencies)

- Add some saturation/distortion (tape saturation is nice, ableton saturator set to soft clip is the exact same as oxford inflator and sounds nice)
  \[the beginning of the mastering chain]

To reduce clipping on master track you don't want to reduce individual tracks cuz that affects the compressors etc. so create a master track that uses a bus to L + R track which everything is sent to that can be turned down. In that L+ R you can put a comp & a pultec 1a to add more air.

After having mastered, Use a spectrum analyzer like tonal balance control. You can compare your master to other songs of the same genre do this when you're done mastering. To compare don't use it while in the process trust your ears first

In comparison to mixing pro mastering takes like ~30min

Every mix you make make a dolby atmos mix using logic cuz the streaming service boost that in their algorithms. All the other daws are shitty at it. For dolby atmos it targets -20 lufs. You can mix for atmos with stereo headphones 

# unnecessarily vulgar guide to micing a kick drum with an RE-20

1. **Tune that fucker** - A shitty kick is gonna sound like a shitty kick even with the most fantastic mic, so tune that kick till it's flawless.

2. **Get that mic up in this shit** - Grab your nearest short stand, and get that mic RIGHT up in there. Grab some earplugs and have the drummer play the kick, then get the mic as close as possible to the beater face without the mic actually getting hit. Oh, your reso head doesn't have a hole in it? Fuck you, grab a box cutter.

3. **Route that fucker** - get that signal somewhere you can do something with it. Nice pres preferred, but I've gotten good results with the pres in a Digi002R so you don't need _great_ preamps.

4. **EQ 4 DAYZ BRO** - Actually nah, just a gentle mid scoop so you can fit your vox and guitars and shit in there.

5. **Squuuuuueeeeze that mofo** - Fairly fast, fairly gentle compression seems to suit the RE-20 best, but use what suits your genre.

6. **Hit record** - Or don't, I don't own you.

Figure out:

 how to record using take lanes

Adding markers

Inverting phase -> the phase button in any eq

Changing bpm

Make L & R mono tracks into 1 stereo

Building ribbon mic: the microns of the aluminum foil is is antiproportional to output level. 1.2 microns -> 0.6 microns = +6db output level. Transient response is much more important which is a whole conundrum but I guess 1.2 microns is good enough since can't find 0.6 anywhere online. since neodymium magnets are much stronger thna the ones they had back in teh day when the 4038 was developed using like 1.2 - 1.8 microns is fine

Reverse, put reverb, then back forward

Winds of change podcast 

Physical chorus is extremely hard to get good digitally 

La-3A is a classic kick compressor

HEDD type 20 speakers

For creating a studio/room use diffusers over absorption. Bunch of foam will sound shit. Room has shit acoustics with bunch of foam, use diffusion.

There exists a golden ratio for rooms to have the best sound

You can get cheap used krk speakers for like 90 to build a system

Get a left and right pitch shifter

Morcheeba - big calm

Air - moon safari 

Riders on the storm - the door

Sunbather - deafheaven
