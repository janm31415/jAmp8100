# jAmp 8100 (AUv3) manual
![](images/Header.jpg)

Welcome to the jAmp 8100 manual! We are thrilled to present you with a powerful and immersive digital emulation of the iconic Marshall VS8100 amplifier, designed to take your guitar playing experience to new heights. Whether you're a seasoned musician, a passionate enthusiast, or a beginner exploring the world of rock and roll, this manual will guide you through every aspect of our cutting-edge software, helping you unleash the raw potential of this legendary amplifier right at your fingertips.

Inside this manual, you'll find a comprehensive overview of the software's features, functionalities, and how to navigate its user-friendly interface. We'll walk you through the diverse range of authentic tones and effects that this simulation offers, providing you with the tools to replicate the distinct Marshall sound that has defined countless music genres.

From the classic, warm tones of vintage blues, over the roaring power chords of hard rock, to the vintage Death metal tones of the '90s, the jAmp 8100 audio plugin has been painstakingly crafted to deliver an unparalleled auditory experience. Join us on this journey as we dive into the world of virtual amplification and unleash the potential of your guitar rig like never before.

So, strap in, plug in your guitar, and get ready to rock out with the jAmp 8100 – the perfect blend of innovation and tradition for the modern guitarist. Let's dive in and discover the limitless possibilities that await you in this digital realm of sonic excellence. Get ready to inspire, create, and elevate your music to a whole new level!

## System requirements

jAmp 8100 is an AUv3 (Audio Unit version 3) plugin that can be used as a stand-alone application on iOS and macOS, or as an audio plugin inside a host application on iOS and macOS. 

Minimal requirements are:
  - iOS 14.0 or later for mobile (iPhone or iPad)
  - macOS 11.0 or later for desktop / laptop

The jAmp 8100 software is distributed via the Apple App store. Click on the App store badge to go to the download location.

[![](images/AppStore.png)](https://apps.apple.com/us/app/jAmp8100/id000000)


## Purchase info

Installation of jAmp 8100 is free, but it will run in DEMO mode. This means that every minute jAmp 8100 will output 3 seconds of silence. This allows the user to test the audio plugin in depth before purchasing it.

Purchasing jAmp 8100 is a straightforward and user-friendly process, following the standard steps from the Apple App Store you're likely familiar with. Once the plugin is unlocked, the DEMO mode will be gone, and you can enjoy the full potential.

![](images/Payment.jpg)

To start the payment process you have to run jAmp 8100 in stand-alone mode. A popup as in the image above should appear. Simply tap or click on "Purchase" and the Apple App Store will guide you through the process.

Note that you should only pay once to unlock the plugin. In case you have a new device, you can get the plugin unlocked by clicking on "Restore". If you go a second time through the payment system, no worries, Apple will notice this and give you the plugin for free.

![](images/PluginDemo.jpg)

Note that it is not possible to purchase the audio plugin via a host application. If you run jAmp 8100 via for instance GarageBand you will get a message as in the image above. Just start the stand-alone jAmp 8100 application if you want to purchase.

## AMP section

![](images/AMP.jpg)

### Top row

At the top left you can control the amount of oversampling. Generally, the more oversampling that is used, the better the simulation will be. The default oversampling rate is x4 and the amplifier is tweaked to sound best for this oversampling rate. If you go to a lower oversampling rate (x1 or x2), the plugin will be less demanding for your CPU but the sound quality is less. It is advised to keep the oversampling rate at x4 if your CPU can handle it.

In the middle we have the preset section. There are a bunch of factory settings that you can experiment with. Furthermore, you can also save your own user settings. The icon with the arrow pointing downward will allow you to save your preset. A popup will show up asking you for the name of your user preset. If the suggested name is colored red, it means that you will overwrite an already existing user preset. You can also delete a user preset by tapping or clicking on the icon with the X mark. Note that you cannot delete factory settings.

If you run jAmp 8100 in it's stand-alone format, you will have an icon of a speaker on the top right. This is your muting button. By default, at startup, the amplifier will be muted to avoid any unwanted feedback. Don't forget to unmute before you start playing.

### Bottom row

Left and right you will see the IN and OUT control knobs. The IN knob controls the volume of the signal that goes in the audio plugin, while the OUT knob controls the volume of the signal that goes out of the audio plugin.

The GATE, OD, EQ, AMP, OUT EQ, CAB, and PED buttons allow you to switch to the corresponding effect.


### Front panel features

#### Normal channel

##### Clean

This controls the volume of the Normal channel.

##### Clean / Crunch 

This button will crunch up your guitar sound for semi-distorted chords. The amount of distortion will be controlled by the Clean control.

##### Bass

The Bass control allows you to shape the low-end frequencies of your guitar's tone. Turn the knob clockwise to increase the bass for added depth and warmth, or counterclockwise to decrease it for a tighter and punchier sound. 

##### Middle

The Middle control enables you to adjust the mid-range frequencies of your guitar's tone. By turning the knob clockwise, you can boost the mids for a fatter sound. Conversely, turning it counterclockwise reduces the mid-range for obtaining a thinner sound.

##### Treble

The Treble control empowers you to shape the high-frequency content of your guitar's sound. When turned clockwise, it boosts the treble, adding brilliance and sparkle to your tone.

#### Channel select

Allows for switching between the Normal and Boost channel.

#### Boost channel

##### Gain

This control governs the input signal from your guitar and the level of gain within the pre-amp while using the Boost channel. Raising the gain enhances the distortion in your guitar sound and, to some degree, boosts the volume. Keeping the gain at a lower level will yield a vintage-style blues crunch, while turning it up will produce higher gain sounds, perfectly suited for classic rock tones.

##### OD1 / OD2

Switches between Overdrive 1 and Overdrive 2. Overdrive 2 takes off where Overdrive 1 finishes, boosting the amplication factor even more.

##### Bass

The Bass control allows you to shape the low-end frequencies of your guitar's tone. When using a heavily distorted tone, turning the knob clockwise will make the tone darker and heavier.

##### Middle

The Middle control enables you to adjust the mid-range frequencies of your guitar's tone. By turning the knob clockwise, you can boost the mids for a fatter sound. Conversely, turning it counterclockwise reduces the mid-range for obtaining a thinner sound.

##### Treble

The Treble control empowers you to shape the high-frequency content of your guitar's sound. When turned clockwise, it boosts the treble, adding brilliance and sparkle to your tone.

##### Contour

The Contour control alters the mid-range frequencies in your guitar tone. Turning the Contour knob fully clockwise removes most of the middle frequencies, creating a 'thrash' tone when combined with heavy distortion, high Treble, and Bass settings, ideal for aggressive rhythms and fierce leads. On the other hand, turning the Contour knob fully anti-clockwise produces excellent fusion-type tones. Experiment with this control to discover the perfect setting for your style. If unsure, keeping the control at 12 o'clock is a good starting point.

##### Volume

Controls the volume of the Boost channel.

#### Master

##### Reverb

Reverb will add ambience and size to your guitar tone, giving the effect of playing in a large empty room or hall.
This knob controls the amount of reverb.

##### Volume

Controls the main output volume.

##### Cab

Turns on / off the cabinet loader section. When turned off you can add any other custom cabinet loader to your stack of audio plugins to simulate the desired cabinet sound effect.

##### Power sim

Turns on / off the power amplifier simulation. When turned off the output volume will be louder and you will hear some hard clipping which is less appealing to the ear. This option however allows to add another custom power amplifier to your stack of audio plugins.

##### Power

Turns on / off the amplifier. Can be useful in case you only want to use some of the pedals.

## GATE section

![](images/GATE.jpg)

Designed to elevate your guitar playing experience, this pedal comes equipped with versatile controls to give you unparalleled command over unwanted noise in your signal chain. Tame those pesky hums, buzzes, and hisses while retaining your guitar's natural dynamics and sustain. 

### Threshold

The threshold control determines the level at which the noise suppression effect is activated. When set, the noise suppressor remains inactive until the incoming audio signal drops below the specified threshold level. Once the noise suppressor engages, the input signal will be reduced or eliminated (depending on your chosen settings with the other controls). Adjusting the threshold control allows you to tailor the noise suppression to your specific setup, ensuring a clean and noise-free performance while still preserving your desired guitar tones and sustain.

### Attack

The attack control on the noise suppressor governs the speed at which the noise reduction effect disengages once the incoming signal surpasses the threshold level. A shorter attack time means the noise suppressor inactivates quickly, bringing back the input signal almost instantaneously after the threshold is exceeded. On the other hand, a longer attack time introduces a more gradual introduction of the input signal.

### Hold

When the noise suppression is activated (which happens when the incoming audio signal drops below the specified threshold level), the input signal will not be reduced for a given time in milliseconds controlled by the hold knob.

### Release

When the noise suppression is activated (which happens when the incoming audio signal drops below the specified threshold level), the input signal will not be reduced for a given time in milliseconds controlled by the hold knob. After that period, the input signal will start dropping in volume gradually, spread over a given time in milliseconds controlled by the release knob. This will eventually result in a fully eliminated input signal, provided that the input signal never surpasses the specified threshold level in the time period controlled by the hold and release knobs.

### Foot switch

Turn the noise suppression on or off.

## OD section

![](images/OD.jpg)

The Tube Booster is a digital emulation of the legendary Ibanez Tube Screamer. This pedal is a timeless classic cherished by guitarists across generations for its unparalleled ability to add warmth, smoothness, and that elusive "scream" to your guitar tone.

### Drive

The Drive control determines the amount of overdrive or distortion applied to your guitar signal.

### Tone

Acting as a high-frequency filter, the Tone knob allows you to adjust the brightness or darkness of the sound to suit your preferences and playing style.

### Level

The Level control determines the output volume of the pedal. 

### Foot switch 

Turn the Tube Booster on or off.

## EQ section

![](images/EQ.jpg)

Our Ten Band Equalizer offers you the ability to shape and customize your sound to perfection. With ten adjustable frequency bands at your fingertips, you can boost or cut specific frequencies to enhance clarity, balance, and depth in your music.

### Frequency bands

Adjust the boost or cut of the selected band by 12dB.

### Foot switch 

Turn the 10 band equalizer on or off.

## OUT EQ section

![](images/OUTEQ.jpg)

This is a five-band post-amp equalizer designed to shape the amplifier's sound before it reaches the cabinet.

### Frequency bands

Adjust the boost or cut of the selected band by 12dB.

### Foot switch 

Turn the equalizer on or off.

## CAB section

![](images/CAB.jpg)

### Foot switch 

Turn the IR loader on or off.

## PED section

![](images/PED.jpg)

## Credits

- [AudioKit Controls](https://github.com/AudioKit/Controls)
- [Cabinet IRs by forward-audio.com](https://www.forward-audio.com)
- [Cabinet IRs by Valhallir.at](https://valhallir.at)
- [DSP Filters by Vinnie Falco](https://github.com/vinniefalco/DSPFilters)
- [File Picker by Mark Renaud](https://github.com/markrenaud/FilePicker)
- [Lobster font](https://github.com/impallari/The-Lobster-Font)
- [R-Solver](https://github.com/jatinchowdhury18/R-Solver)
- [SwiftUI animation by Finsi Ennes](https://github.com/KeatoonMask/SwiftUI-Animation)
