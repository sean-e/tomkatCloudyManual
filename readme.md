<!--
<style type="text/css">
  @media print {
    * { font-family: sans-serif; font-size: smaller; }
  }
</style> -->
# TOMKAT PEDALS CLOUDY USER MANUAL

### CONTENTS
- [INTRODUCTION](#introduction)
- [POWER](#power)
- [LAYOUT](#general-layout)
  - [GENERAL](#general-layout)
  - [EXPRESSION JACK](#expression-jack)
- [MODES](#modes)
  - [GRANULAR PROCESSOR](#mode-granular-processor)
  - [PITCH SHIFTER/TIME STRETCHER](#mode-pitch-shiftertime-stretcher)
  - [LOOPING DELAY](#mode-looping-delay)
  - [SPECTRAL MADNESS](#mode-spectral-madness)
  - [EMMIVERB](#mode-emmiverb)
  - [RESONESTOR](#mode-resonestor)
- [PRESETS](#presets)
  - [SAVING](#save-a-preset)
  - [LOADING](#load-a-preset)
  - [LOADING SHORTCUT VIA FOOTSWITCHES](#load-a-preset-via-footswitches)
- [CHEAT SHEETS](#cheat-sheets)
  - [EFFECT MODE SELECTOR](#effect-mode-selector-cheat-sheet)
  - [AUDIO QUALITY SELECTOR](#audio-quality-selector-cheat-sheet)
  - [EMMIVERB](#emmiverb-cheat-sheet)
  - [RESONESTOR](#resonestor-cheat-sheet)

<div style="page-break-after: always;"></div>

### INTRODUCTION

User manual for [TOMKAT PEDALS](https://tomkatpedals.com/) digital multi effect pedal [CLOUDY V2](https://tomkatpedals.com/collections/effect-pedals/products/cloudy-v2-digital-multi-effect-pedal).  This manual started as the [V1 version](https://tomkatpedals.com/pages/cloudy-info) and has been updated for V2 hardware.

Cloudy is a guitar pedal adaptation of the Eurorack Module "Clouds" by Mutable Instruments. It's based on the "Parasites" alternative firmware which has 6 different digital programs including granular synthesis, pitch shifting, delay, reverb, filters, and resonators.

Brief description of the Granular mode from the Mutable Instruments Clouds page:

"Clouds is focused on the realtime granularization of incoming audio signals, and their transformation into amorphous textures. Grains of adjustable size, pitch and envelope, are extracted at controllable time offsets from the input signal. Grains are seeded randomly, periodically, or whenever the module receives a trigger."

### POWER

Works off standard center negative 9V DC power supply and requires at least 200ma current. Works best with a dedicated channel from a pedal board power supply or it's own One Spot style supply. Please do not use with a daisy chained power supply (one power cord plugged into several pedals).

<div style="page-break-after: always;"></div>

### GENERAL LAYOUT

![layout image](https://cdn.shopify.com/s/files/1/0652/8579/files/layout_large.jpg?v=1552325726)

Cloudy has two light up buttons. The right one allows you to scroll through the different effect modes. The left one allows you to change the audio quality of the recorded buffer in each effect. This allows you to go from crystal clear stereo output with a 1 second buffer down to degraded mono output with an 8 second buffer. 

The Freeze foot switch allows you to freeze your audio buffer, which behaves differently depending on which mode you are in.

There are five small light up knobs on the pedal. When you activate the pedal, these light up white to let you know the pedal is engaged. The white lights turn off when the pedal is bypassed. When you activate the Freeze switch, the knobs light up red. If you have the pedal on (and the knobs are white) and you activate Freeze, the knobs will light up pink. If you engage freeze and then turn the pedal off and the knobs are red, your buffer is still frozen until you hit freeze again and turn the red lights off.

There are four LEDs in the cluster of knobs. They indicate which mode you have selected based on which lights are flashing. They also monitor the input signal level like a vu meter.

There is an input and output attenuverter marked IN and OUT. This allows for about a unity volume when both are at 12 o'clock position. It also allows you to turn down the input volume of hot signals or boost weaker signals. You will see the fourth LED on the vu meter turn red when your input starts to clip.

V2 hardware has left and right inputs and outputs.

<div style="page-break-after: always;"></div>

### EXPRESSION JACK

You can use a normal style (like Moog) expression pedal on the left hand side jack near the freeze switch. Be sure to unplug power from Cloudy before plugging in an expression pedal.

It can control any of the knobs.

To control a knob with the expression pedal, enter expression assignment mode by pressing both **EFFECT MODE** and **AUDIO QUALITY** selector buttons at the same time.  The status LEDs will change to purple.  Rotate any knob to assign the pedal to control it.  The status LEDs closest to a knob indicate expression assignment.

In assignment mode, you can confirm functioning of a plugged in expression pedal as the small lighted knobs show a live meter of the position of the pedal.

Press either **EFFECT MODE** or **AUDIO QUALITY** selector buttons to exit assignment mode.

Some fun uses of expression in **Position** are:

In **GRANULAR** mode with **FREEZE** activated - you can scrub through the frozen buffer.

In **LOOPING DELAY** mode you can change the delay time and create tape scrubbing sounds. If **FREEZE** is activated you can change the position of the playing tape head.

Some fun uses of expression in **Density** are:

In **GRANULAR** mode you can change the frequency of grains produced.

In **EMMIVERB** mode you can change the decay time of the reverb to swell in oscillation.

<div style="page-break-after: always;"></div>

### MODES

### MODE: GRANULAR PROCESSOR

![granular mode](https://cdn.shopify.com/s/files/1/0652/8579/files/gran_medium.jpg?v=1552326991)

Cloudy is a granular audio processor. It creates textures and soundscapes by combining multiple overlapping, delayed, transposed and enveloped segments of sound taken from an audio recording buffer.

**DENSITY**: This is the main control knob for the density of grains produced. At 12 o’clock it produces no grains, which means you won’t hear any effect. Turn clockwise and grains will be sown randomly, counter-clockwise and they will be played at a constant rate. The further you turn, the higher the overlap between grains.

**SIZE**: Controls the size of the grains produced. Clockwise the grains are larger, and counter clockwise they get very tiny.

**POSITION**: Selects from which part of the recording buffer the audio grains are played. Acts like a delay time control.

**TEXTURE**: Morphs through various shapes of grain envelopes. Before 12 o’clock the grains are noisier. Past 2 o’clock, activates a diffuser which smears transients.

**PITCH**: Changes the pitch (transposition) of the grains. 12 o’clock is normal pitch.

**MIX**: Dry signal CCW and wet signal CW

**IN**: Sets the input level

**OUT**: Sets the output volume

**PAN**: Sets the amount of random panning/balance applied to the grains. Only noticeable with stereo output.

**VERB**: Adds reverb to both wet and dry signal. It’s a global effect so even when mix is 100% dry you can still control the amount of reverb.

**FB**: Amount of signal feedback. Noticeable with higher **POSITION** value. Watch out because things can get out of hand past 10 o’clock. If you have tons of crazy feedback happening and the pedal seems like its getting away from you, just turn **FB** all the way down.

<!-- By moving the grain **DENSITY** to 12 o’clock, and sending a trigger input, Cloudy can be controlled like a micro-sample player. -->

In normal quality setting (best quality stereo) there is one second of recorded audio buffer, basically up to one second of delay time if the **POSITION** knob is turned all the way clockwise. In other quality modes the delay can be longer and in the lowest quality mode (low quality mono) the buffer is 8 seconds and if the **POSITION** knob is all the way clockwise you won’t hear you repeats until after 8 seconds of playing and it can get a little confusing but very fun too. Also this low quality has a real tape-like feel to it.

<div style="page-break-after: always;"></div>

### MODE: PITCH SHIFTER/TIME STRETCHER

![pitch shift mode](https://cdn.shopify.com/s/files/1/0652/8579/files/pitch_medium.jpg?v=1552326997)

This mode is quite similar to the granular mode, except that it uses two overlapping grains synchronized with the most salient period of the sound. The grains are carefully spliced so that they mesh well with each other (a technique similar to the “deglitching” of early pitch-shifters). Modulating **POSITION** when recording is frozen will “scrub” through the audio buffer. Clouds’ uses classic time-domain methods which are not suitable for polyphonic or percussive material (unless this percussive material is breakbeats and you liked Akai samplers. Then: smile).

**DENSITY** creates a granular diffusion effect based on all-pass filters.

**TEXTURE** acts as a low-pass/high-pass filter. 12 o’clock there is no filter.

**SIZE** controls the size of the overlapping windows used for pitch-shifting and time-stretching – from an extremely grainy “drilling” sound to smooth bits of loops.

**IN**: Sets the input level

**OUT**: Sets the output volume

**PAN**: Sets the amount of random panning/balance applied to the grains. Only noticeable with stereo output.

**VERB**: Adds reverb to both wet and dry signal. It’s a global effect so even when mix is 100% dry you can still control the amount of reverb.

**FB**: Amount of signal feedback. Noticeable with higher **POSITION** value. Watch out because things can get out of hand past 1 o’clock. If you have tons of crazy feedback happening and the pedal seems like its getting away from you, just turn **FB** all the way down.

 

Basically if you turn position all the way down, the mix all the way up (100% wet) and change the pitch, it will transpose whatever you are playing.

<div style="page-break-after: always;"></div>

### MODE: LOOPING DELAY

![loop mode](https://cdn.shopify.com/s/files/1/0652/8579/files/loop_medium.jpg?v=1552327002)

The looping delay mode continuously plays back audio from the buffer without any kind of granularization.

**POSITION** controls the distance between the playback head and the recording head (in other words, the delay time). Modulating **POSITION** will create effects similar to vinyl scratching or manual manipulation of tape.

When **FREEZE** is activated, the content of the audio buffer is looped (stutter effect). **POSITION** controls the loop start and **SIZE** the loop duration. While **FREEZE** is active, if you press and hold the **FREEZE** switch until the small pink knobs start blinking, the loop will playback in reverse. To go back to forward direction just hold **FREEZE** until the knobs stop blinking.

**DENSITY** creates a granular diffusion effect based on all-pass filters.

**TEXTURE** acts as a low-pass/high-pass filter. 12 o’clock there is no filter.

**SIZE** controls the size of the overlapping windows used for pitch-shifting – fully clockwise for a smooth result that might smear transients, fully counterclockwise for a grainy, almost ring-modulated sound.

**IN**: Sets the input level

**OUT**: Sets the output volume

**PAN**: Sets the amount of random panning/balance applied to the grains. Only noticeable with stereo output.

**VERB**: Adds reverb to both wet and dry signal. It’s a global effect so even when mix is 100% dry you can still control the amount of reverb.

**FB**: Amount of signal feedback. Noticeable with higher **POSITION** value. Watch out because things can get out of hand past 1 o’clock. If you have tons of crazy feedback happening and the pedal seems like its getting away from you, just turn **FB** all the way down.

<!-- When **FREEZE** is enabled, sending a trigger on the TRIG input creates a clock-synchronized stuttering loop. Otherwise, the period of the trigger pulses sets the delay time – provided this delay is shorter than the recording buffer size. -->

<div style="page-break-after: always;"></div>

### MODE: SPECTRAL MADNESS

![spectral mode](https://cdn.shopify.com/s/files/1/0652/8579/files/spectral_medium.jpg?v=1552327008)

In this mode, the incoming signal is converted into “frames” of spectral data, that are stored, transformed, recombined, and resynthesized as a time-domain signal.

**POSITION** selects into which buffer the audio is poured (when **FREEZE** is not active), or from which buffer the audio is synthesised (when **FREEZE** is active). For example, set **POSITION** to its minimum value. Press **FREEZE**. You get a first texture. Set **POSITION** to its maximum value. **UNFREEZE**. Wait for something else to happen in the incoming audio. Press **FREEZE** again. By moving **POSITION** you interpolate between the two textures which had been captured at the press of **FREEZE**. Depending on the quality settings there are 2 to 7 buffers laid out over the course of the **POSITION** knob. What the module does is crossfade between a “wavetable” of FFT slices.

**SIZE** changes the coefficients of a polynomial that determines how frequencies are mapped between the analysis and synthesis buffers. It’s like a 1-knob GRM Warp. Over the course of the knob it’ll do spectral shifting, but also spectral reversal.

**PITCH** controls the transposition (pitch-shifting).

**DENSITY** determines how results from the analyzer are passed to the resynthesizer. Below 12 o’clock, there’s some increasing probability that a given FFT bin won’t get updated, causing a kind of partial freeze. After 12 o’clock, adjacent analysis frames are increasingly merged together (like a low-pass filter in the amplitude each frequency bin). At extreme settings, random phase modulation is applied to smooth things - giving you different flavours of spectral muddling/reverb.

**TEXTURE** does two things: below 12 o’clock, it increasingly quantizes the amplitudes of the spectral components, like a very low-bitrate audio file. After 12 o’clock, it increasingly weakens the strongest partials and amplifies the weakest ones. This has the effect of making the spectrum more noise-like.

**IN**: Sets the input level

**OUT**: Sets the output volume

**PAN**: Sets the amount of random panning/balance applied to the grains. Only noticeable with stereo output.

**VERB**: Adds reverb to both wet and dry signal.

**FB**: Amount of signal feedback. Watch out because things can get out of hand with feedback in this mode. If you have tons of crazy feedback happening and the pedal seems like its getting away from you, just turn **FB** all the way down. I usually leave it all the way down.

<!-- Sending a trigger to the **TRIG** input creates various frequency-domain glitches typical of corrupted (encoded) audio files. It works as a kind of build-up/feedback effect - the shorter the pulse, the smaller the effect. With a continuous gate, it’ll really start to rot… -->

<div style="page-break-after: always;"></div>

### MODE: EMMIVERB

![emmiverb mode](https://cdn.shopify.com/s/files/1/0652/8579/files/emmi_medium.jpg?v=1552327012)

**POSITION**: **Pre-delay**. Controls the time it take for the reverb to kick in after a sound has gone in (from 0 to about half a second).

<!-- When a clock is fed to the **Trig** input, this knob becomes a clock divider/multiplier for the pre-delay: at 12 o'clock, the pre-delay takes the value of the clock length; clockwise, this clock is divided, and counter-clockwise it is multiplied. -->

**SIZE**: **Reverb Size**. Controls the lengths of all the delays internal to the reverb, i.e. the size of the emulated room. It varies from a small resonator to a huge hall.

**DENSITY**: **Decay**. Controls the amount of sound fed back into the reverb loop, i.e. the decay time of the reverb tail. Beyond 3 o'clock, this signal is actually amplified and the reverb enters self-oscillation.

**PITCH**: **Pitch shift** Each time the sound is fed back into the reverb, it can be pitch shifted. The Pitch knob controls, from -1 to +1 octaves how it is pitch shifted. At 12 o'clock, no pitch shifting is applied; fully clockwise, we get the classic shimmer effect; lots of oddities can be found in between. To hear the effect of the pitch shifter, some sound has to be fed back by increasing Decay. Note that Size has an impact on how well the sound is pitch-shifted: the larger the room size, the more accurate the pitch shift.

**TEXTURE**: **Dampening**. Controls the dampening of the reverb. From fully CCW to 12 o'clock, a low-pass filter is applied, simultaing the absorption of the room. From 12 o'clock to fully CW, a high-pass filter is applied for unusual, crystalline effects.

The **Freeze** button sets reverb to (near) infinite decay, and mutes the input. This works best with no pitch shifting and a large size.

**PAN**: **Diffusion**. Controls how much the sound is "smoothened" by the diffusers each time it goes through the loop. Fully clockwise, you get the more dense, continuous sound; fully counter-clockwise, you clearly hear the sound being repeated like in a multi-tap delay.

**VERB**: **Modulation amount**. Controls the amount of modulation applied by the LFOs to the delay time. Small modulations result in subtle chorus and ghost tones, large modulations in random pitch shifts.

**FB**: **Modulation speed**. Controls the speed of these LFOs. It ranges from ~1/100Hz to ~100Hz. It has no effect if modulation amount is null.

**IN**: Sets the input level

**OUT**: Sets the output volume

<div style="page-break-after: always;"></div>

### MODE: RESONESTOR

![resonestor mode](https://cdn.shopify.com/s/files/1/0652/8579/files/reso_medium.jpg?v=1552327017)

This one is deep…

Put the knobs in the following positions:

**Mix**, **Size**, **Density**, **Reverb** and **Feedback** fully **CCW**

**Pitch**, **Position**, and **Texture** at 12 o'clock

**Pan** fully CW

The input feeds the voice/resonator, which decay is controlled by the **Density** knob.

The pitch of the resonator is controlled by the **Pitch** knob. Each voice consists of four "parts" (four resonators), which can be set to different pitches to form chords. The **Size** knob sets the chord.

The resonators can sound very metallic; the **Texture** knob helps attenuating the high/low frequencies each time sound passes through the resonator. At 12 o'clock, no filtering is applied; CCW is a low-pass filter; CW is a band-pass filter. This way, a short sound impulse passing through the resonator will have a long decay with less and less high (and possibly low) frequency.

<!-- Sending a trigger to the **Trig** input will send a short burst of noise to one of the voices. The **Position** knob controls the timbre and duration of this burst, roughly modelling the position on which the string is struck. -->

<!-- Each time a **Trig** is received, the module switches the active voice; therefore, you can get duophony. At any time, the knobs (pitch, chord, feedback, damping) control only the parameters of the resonators of the active voice; the other voice keeps the last parameters it was on. If you are satisfied with the sound of the current voice and want to keep it running (maybe as a drone, using the other voice for melody), press **Freeze**: it will instantly switch voice, and prevent Trig from automatically switching voice. -->

**Decay (Density knob)** Decay time of the current voice. Beyond approx. 3 o'clock, decay is infinite and the sound sustains forever (you can use it as a traditional oscillator).

**Pitch (Pitch knob)** Base pitch of the current voice. At 12 o'clock, the pitch is A3 (220Hz).

**Chord (Size knob)** Chord selection for the current voice. Morphs gradually between Unison, Fat, Superfat, Fat power, Fat octave, Octaves, Power, Major, Major7, Minor7, Minor, Sus2, Sus4, Minor9, Major9, Minor11, Major11, and Major11.

**Dampening (Texture knob)** Controls filtering in the feedback loop of the resonator. At 12 o'clock, no filtering is applied; CCW, a low-pass filter is applied with a increasingly low cutoff frequency; CW, a band-pass filter at the frequency of the resonator is applied with an increasingly high resonance.

**Position (Position knob)** Controls the timbre and duration of the noise burst. CCW, it will be longer and more dampened; CW, it will be shorter and more high pitched. At both ends of the knob, the burst will be inaudible (too damped or too short), which you can use to "mute" a voice.

**Distortion (Mix knob)** Randomly distorts the timbre of the voices by modulating each comb filter by low pass-filtered noise. Fully CCW, the modulation amount is maximum but the noise is filtered out entirely, so there is no effect. Fully CW, the noise is unfiltered, but the modulation amount is null, so there is no effect. In between, you get interesting effects, from subtle swaying to harsh distortion.

**Stereo output (Pan knob)** Assigns each part and voice to an output (Out L or Out R). Fully CCW, each voice goes to a different output. At 12 o'clock, both voices are equally mixed in both output. Fully CW, parts of both voices are distributed on both output for a wide stereo effect.

**Harmonics (FB knob)** Simulates striking the harmonics on a string. Fully CCW, it has no effect. Fully CW, the second harmonic will ring; at 12 o'clock, the third, at 10 the fourth etc.

**Scatter (Verb knob)** Controls the random delay times before the sound (input or burst) hits each resonator of the current voice. Used for K-S synthesis with a chord, this will give the impression that strings are struck sloppily. The delay times are randomized at each voice switch.

<div style="page-break-after: always;"></div>

### PRESETS

Saving a preset will store the **EFFECT MODE** and **AUDIO QUALITY** you are currently in as well as the position of all knobs (except input and output volume since those are analog).

Loading a preset loads the mode, audio quality and knob positions that were saved. If you press **EFFECT MODE** once you will see the mode that was saved. Turning the knobs will have no effect until you reach the position that was saved. This way you have to slowly scrub the knob to find the saved position and then you will be able to change that knob’s parameter. This helps you to remember saved knob positions and also doesn’t accidentally ruin your preset by touching a knob unintentionally.

After loading a preset, if you change the **EFFECT MODE**, the knobs will take the value of whatever actual position they are in. This way you don’t have to go searching for where the knob was saved.

#### SAVE A PRESET
**To save a preset**: Press and hold the **EFFECT MODE** button for one second or until three indicator LEDs start to blink with one indicator fading in and out.

The single fading LED represents the preset location.

You can single press the **EFFECT MODE** button to move through different preset save locations.

There are three banks with four spots in each bank for a total of 12 presets.

First bank is red. Second bank is white. And third bank is pink.

Once you settle on a location, press and hold the **EFFECT MODE** button until the indicator LEDs turn off.

Congratulations, you just saved a preset on Cloudy.

#### LOAD A PRESET
**To load a preset**: This is a mirror of the saving process.

Press and hold the **AUDIO QUALITY** button for one second or until three indicator LEDs are fading and one is blinking.

The blinking LED represents the preset location you want to load.

You can single press the **AUDIO QUALITY** button to move through the different presets to load.

Once you settle on the preset you want to load, press and hold the **AUDIO QUALITY** button until the indicator LEDs turn off.

Congratulations, you just loaded a preset on Cloudy.

#### LOAD A PRESET VIA FOOTSWITCHES
**There’s a shortcut to loading presets**.

If you press both foot switches at the same time you will enter preset loading mode (push bypass, then press freeze, then release both foot switches).

Use the freeze foot switch to scroll through the different presets.

Press and hold the freeze footswitch until the indicator LEDs turn off.

You just loaded a preset using the foot switches.

If you enter this mode accidentally you can cancel by pressing bypass (on button) once or wait and do nothing for 3 seconds.

<div style="page-break-after: auto;"></div>

### CHEAT SHEETS

### EFFECT MODE SELECTOR CHEAT SHEET

![mode selector cheat](https://cdn.shopify.com/s/files/1/0652/8579/files/02_MODE_SELECT_grande.jpg?v=1552325757)

Reverse scroll by pressing **AUDIO QUALITY** button

<div style="page-break-after: always;"></div>

### AUDIO QUALITY SELECTOR CHEAT SHEET

![quality selector cheat](https://cdn.shopify.com/s/files/1/0652/8579/files/03_QUALITY_SELECT_grande.jpg?v=1552325764)

<div style="page-break-after: always;"></div>

### EMMIVERB CHEAT SHEET

![emmiverb cheat](https://cdn.shopify.com/s/files/1/0652/8579/files/EmmiSheet_grande.jpg?v=1552327338)

<div style="page-break-after: always;"></div>

### RESONESTOR CHEAT SHEET

![resonestor cheat](https://cdn.shopify.com/s/files/1/0652/8579/files/ResoSheet_grande.jpg?v=1552327362)

© 2026, TOMKAT PEDALS & ELECTRONICS
