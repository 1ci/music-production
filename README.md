# Ici's Music Production Tools
![Image of mixing in stereo](https://hostr.co/file/KibZkoHqIUkJ/blog_studio_basics_mixing_stereo_hero.jpg)

>_Think of sound as 3-dimensional:_
>1. _Height = Frequency Coverage (Timbre/Harmonics)_
>2. _Width = Stereo Field & Panning_
>3. _Depth = Volume/Amplitude & Ambience_

# Use [generators](#generators) to produce sound out of:
* [Raw Materials](#raw-materials)
* [Sample Managers](#sample-managers)
* [Samplers](#samplers)
* [Romplers](#romplers)
* [Sample Players](#sample-players)
* [Synthesizers](#synthesizers)
* [Midi & Utilities](#midi-and-utilities)

# Use [effects](#effects) to:
* [Analyze the sound](#analyze-the-sound)
* [Filter out the junk](#filter-out-the-junk)
* [Make corrections](#make-corrections)
* [Balance the dynamics](#balance-the-dynamics)
* [Modulate and enhance the good parts to taste](#modulate-and-enhance-the-good-parts-to-taste)

## Analyze the sound
![Image of a spectrum analyzer](https://hostr.co/file/NNbPRVs7K0FK/voxengo.jpg)
>_Figure out where, how and why it needs to sit in the mix._
* [Spectrum Analyzer](#spectrum-analyzers)
* [Stereo Imager](#stereo-imagers)
* [Loudness Meter](#loudness-meters)
* [Oscilloscope](#oscilloscopes)
* [Vectorscope](#vectorscopes)

## Filter out the junk
![Image of Fruity Param EQ2](https://hostr.co/file/a7BSCMEHMAIR/parameq2.png)
>_Get rid of what you don't (want to) / **can't** hear. Control resonant peaks / unpleasant frequencies. Allow for space for other sounds so that they don't clash and clutter up the mix._
* [Equalizer](#equalizers) - _controls the volume of distributed frequencies_
  * Mid EQ - _in the center of a stereo image (mono)_
  * Side EQ - _in the sides of the stereo field. eliminate phasing issues by high-passing._
  * Regular vs Linear Phase EQ - _"Linear-phase EQ is essentially a highly-accurate, “surgical” EQ. Regular EQ's have phase shift between the different bands"_
* [Filter](#filters) - _a form of pre-set EQ with more limited and focused control_
* [Noise Filter](#noise-filters) - _can build noise profiles and subtract noise from the signal. some plugins such as ReaFIR can do it in realtime_

## Make corrections
![Image of FL Studio's Edison](https://hostr.co/file/TVgiClfdKHOn/FL64_Xpr5ErVrly.png)
>_Fade in/out. Declick in/out. Normalize. Remove noise. Blur._
* Audio Editors - _tinker with audio files_
  * Pitch Correction (Melodyne, Newtone) - _fix out of tune vocals_

## Balance the dynamics
![Image of a compressor](https://hostr.co/file/1hDVQgRTfTNN/comp.png)
>_Control transients, sudden peaks and anything to do with volume._
* [Compressor](#compressors) - _automated volume control triggered by the volume of any frequency fed into it_
* [Multiband Compressor](#multiband-compressors) - _automated volume control per band triggered by the volume of frequencies in that band_
* [De-Esser](#de-essers) - _eliminates the excessive prominence of sibilant consonants, such as the sounds normally represented in English by "s", "z", "ch", "j" and "sh". essentially a compressor with a band in the high region of the frequency spectrum_
* [Limiter](#limiters) - _a compressor with an infinite ratio setting. sound cannot get louder past the set threshold/ceiling_
* [Soft Clipper](#soft-clippers) - _like a limiter but hard blocks sound with a softer curve minimizing distortion. peaks get rounded off instead of brick wall square-ified_
* [Transient Processor](#transient-processors) - _controls the volume of transients of very short sounds like drum samples. it can compress or expand to make a drum punchier or fuller_
* [Expander](#expanders) - _an inverse compressor. expands the volume when sound hits its set threshold._
* [Noise Gate](#noise-gates) - _allows for sound to come through only if its volume surpasses the set threshold_
* [Dynamic EQ](#dynamic-eqs) - _side-chained multiband compressor_
* [Volume Envelope/LFO Tools](#volume-envelope-or-lfo-tools) - _used for sidechaining and creative purposes_

## Modulate and enhance the good parts to taste
![Image of Fruity Reverb 2](https://hostr.co/file/RqAXi93j2QEj/reverb2.png)
>_Give spaciousness, brightness, interesting artifacts, harmonies, modulation and processing to sound to enhance the listener's experience._
* [Delay](#delays) - _give echo characteristics_
* [Reverb](#reverbs) - _simulate an ambient space_
* [Distortion/Overdrive](#distortion) - _square-ify_
* [Saturation](#saturation) - _introduce a subtle set of harmonics to give warmth and presence. run hot to increase perceived volume_
* [Harmonizer](#harmonizers) - _generates perfect fifths_
* [Exciter](#exciters) - _pre-set MB compressor, EQ, saturator and probably a couple of other things into one meant to brighten up your sound_
* [Chorus](#chorus) - _"occurs when individual sounds with approximately the same time, and very similar pitches converge and are perceived as one"_
* [Flanger](#flangers) - _"Flanging is an audio effect produced by mixing two identical signals together, one signal delayed by a small and gradually changing period, usually smaller than 20 milliseconds"_
* [Phaser](#phasers) - _"A phaser is an electronic sound processor used to filter a signal by creating a series of peaks and troughs in the frequency spectrum. The position of the peaks and troughs of the waveform being affected is typically modulated so that they vary over time, creating a sweeping effect."_
* [Hyper/Dimension](#hyper-dimension) -_"Hyper/Dimension is a dual effect that pairs a simulated (but CPU-friendly) unison with four subtly modulated delay lines" (SerumFX)_ 
* [Glitcher](#glitchers) - _simulated stutters, artifacts, transient faults_
* [Granulizer](#granulizers) - _"Granular synthesis splits a wave sample into many small pieces (grains) that are looped/played-back according to the settings of the generator. The length and spacing of the grains can also be altered to achieve different tonal effects"_
* [Bitcrusher](#bitcrushers) - _"a lo-fi (low fidelity) digital audio effect, which produces a distortion by the reduction of the resolution or bandwidth of digital audio data. The resulting quantization noise may produce a “warmer” sound impression, or a harsh one, depending on the amount of reduction"_
* [Stereo Shaper/Enhancer](#stereo-shapers) - _controls the spaciousness and width of a sound. may introduce the Haas effect_
* [Autopan](#autopan) - auto modulated panning using pre-set patterns_
* [Autofilter](#autofilters) - auto modulated filtering using pre-set patterns_
* [Pitch Shifter](#pitch-shifters) - _lowers or raises the original pitch of a sound_
* [Formant Shifter](#formant-shifters) - _"Formants are the harmonic frequencies that occur in the human voice. They define the timbre and alter the perception of how a vocal has been performed (more from the diaphragm than from the throat, for example). Formant shifting does not affect the pitch or timing of a segment"_
* [Autotune](#autotune) - _auto tunes vocals/sound to the closest pitch of notes in a selected scale_
* [Vocoder](#vocoders) - _"synthesizes a modulator (usually a voice) in the left channel of a stereo track with a carrier wave in the right channel to produce a modified version of the left channel"_
* [Other/Multi-FX](#other-or-multifx)
  * Time/Pitch/Volume Modulators - _Gross Beat, Half-time_
  * Vinyl Crackler - _makes your sound more lo-fi and vintage_
  * Voice Changer - _a type of formant shifter? i haven't found any vsts yet but it would be cool to look into_
  * Utilities - _envelopes, LFO, XYZ, peak controllers_
  
# Generators
### Raw Materials
> _drum kits, midi, presets, samples, loops, sfx, vox_
* Free
  * [r/Drumkits](https://www.reddit.com/r/Drumkits/)
  * [r/Samples](https://www.reddit.com/r/Samples/)
  * [r/FreeSounds](https://www.reddit.com/r/FreeSounds/)
  * [r/FreeLoops](https://www.reddit.com/r/FreeLoops/)
  * [r/SFXLibraries](https://www.reddit.com/r/SFXLibraries/)
  * [Audioblocks](https://www.audioblocks.com/)
  * [Karoryfer Samples](https://www.karoryfer.com/karoryfer-samples)
  * [Freesound](https://freesound.org/)
  * [Sample Focus](https://samplefocus.com/)
  * [freeSFX](https://www.freesfx.co.uk/)
  * [Soundbible](http://soundbible.com/)
  * [PacDV SFX](https://www.pacdv.com/sounds/index.html)
  * [GRSites SFX](http://www.grsites.com/archive/sounds/)
  * [Soundjay SFX](https://www.soundjay.com/)
  * [Soundgator SFX](http://www.soundgator.com/)
  * [99sounds SFX](http://99sounds.org/free-sound-effects/)
  * [Bird sounds](https://search.macaulaylibrary.org/catalog?mediaType=a)
  * [Soundshock](https://www.soundshockaudio.com/free-downloads-main/)
  * [Echo Sound Works](https://www.echosoundworks.com/free-downloads)
  * [Bass Gorilla](https://bassgorilla.com/free-serum-presets/)
* Paid/Services
  * [Splice Sounds](https://splice.com/features/sounds)
  * [Sounds by NI](https://sounds.com/)
  * [Noiiz](https://www.noiiz.com/)
  * [Zenhiser](http://www.zenhiser.com/)
  * [Loopcloud](https://www.loopcloud.net/)
  * [Soundsnap](https://www.soundsnap.com/)
  * [Audiomicro](https://www.audiomicro.com/)
  * [Kingsway Music Library](https://www.kingswaymusiclibrary.com/)
  * [RawBeatz](https://rawbeatz.com/)
  * [Soundoracle](https://soundoracle.net/)
  * [HipHop Drum Samples](https://hiphopdrumsamples.com/collections/cookin-soul)

### Sample Managers
> _make your entire sample library searchable and more organized. might provide access to a cloud service of samples_
* [Organizing Your Sample Library](https://www.reddit.com/r/edmproduction/comments/22c6e7/organizing_your_sound_library_extensive/)
* [ADSR Sample Manager](https://www.adsrsounds.com/product/software/adsr-sample-manager/)
* [Loopcloud Sample Manager](https://www.loopcloud.net/)
### Samplers
> _can load and play audio files in different ways. for ex. some have ADSR, looping functions and FX modules that operate on the sample_
### Romplers
> _"a rompler is an electronic music instrument that plays pre-fabricated sounds based on audio samples. In contrast to samplers, romplers do not record audio and have limited or no capability for generating original sounds. The term rompler is a portmanteau of the terms ROM and sampler"_
### Sample Players
> _libraries of sampled instruments_
### Synthesizers
> _"an electronic musical instrument that generates audio signals that may be converted to sound. Synthesizers may imitate traditional musical instruments such as piano, flute, vocals, or natural sounds such as ocean waves; or generate novel electronic timbres"_
### Midi and Utilities
> _drum sequencers, arpeggiators, chord builders, controllers, etc_

# Effects
### Spectrum Analyzers
### Stereo Imagers
### Loudness Meters
### Oscilloscopes
### Vectorscopes

### Equalizers
### Filters
### Noise Filters

### Compressors
### Multiband Compressors
### De-Essers
### Limiters
### Soft Clippers
### Transient Processors
### Expanders
### Noise Gates
### Dynamic EQs
### Volume Envelope or LFO Tools

### Delays
### Reverbs
### Distortion
### Saturation
### Harmonizers
### Exciters
### Chorus
### Flangers
### Phasers
### Hyper-Dimension
### Glitchers
### Granulizers
### Bitcrushers
### Stereo Shapers
### Autopan
### Autofilters
### Pitch Shifters
### Formant Shifters
### Autotune
### Vocoders
### Other or MultiFX
