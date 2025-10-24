# Additive Synthesizer
**Owner:** Charlie Zhu

**Overview:** An additive synthesizer component that is implemented by adding together sinusoids with different amplitudes to make a sound.

---

## Features Supported
*  #### Sinusoid playback on demand from the sequencer
   *  The component can correctly **read from an xml score file and play the notes** using the right instrument, at the right pitch, right time and right duration.
*  #### Definition of all harmonics
   *  The component can correctly read harmonics from the **\<harmonicsA>** and **\<harmonicsB>** tags inside each note tag of the score file and use the amplitude values from these tags to calculate the audio output.
*  #### Envelop generation
   *  Attack and release of **0.05 seconds** are applied to every note the instrument plays through the class **CAR**.  
*  #### Polyphony
   *  Notes read from the score file can be scheduled and played by the instruments **simultaneously**.
*  #### Sound cross-fading
   *  When \<harmonicsA> and \<harmonicsB> are both present inside a note tag, the note will **gradually transition** from the amplitude value specified in \<harmonicsA> to the amplitude value specified in \<harmonicsB> for each harmonic level **based on time using interpolation**. 

---

## Grading elements supported
10 - Sinusoid playback on demand from the sequencer
20 - Definition of all harmonics
30 - Envelope generation
35 - Polyphony
40 - Sound cross-fading