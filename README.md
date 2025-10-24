# CSE 471 project 1 - Music synthesizer
---
**Title of selection:** Echoes of light

**Group members:** Charlie Zhu

**Score file format:** XML
* The root tag is the score tag that contains values of “bpm” (beats per minute) and “beatspermeasure”.
* Inside the score tag are the instrument tags that specify the names of the instruments.
* Inside each instrument tag, there are note tags that contains the values of:
  * At what measure the note should be played
  * At what beat in that measure the note should be played
  * How long the note should last in beats
  * The pitch of the note
* Inside the note tag, there are two harmonics tags: 
  * The first one is harmonicsA. It specifies the different amplitudes of the sine wave for different harmonics for harmonic set A.  
  * The second one is harmonicsB. It specifies the different amplitudes of the sine wave for different harmonics for harmonic set B.
  
**The score file I used for my selection:**



