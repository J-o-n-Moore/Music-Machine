# Music-Machine
A little program I made to generate random melodies which, for the most part, stick to the basic "rules" for writing cheesy melodies, as one would in a music theory exam.

![screen shot 2018-05-10 at 13 53 20](https://user-images.githubusercontent.com/28049022/39874152-4a64eb8c-546d-11e8-825a-7514633def4a.png)

First I wanted to focus on the melody generation so I hardcoded in a "cheesy accompaniment". The same accompaniment pattern is generated for which ever chords are entered into the chord progression text field. This sentece may be difficult to understand but if you listen to one of the "cheesy" samples you will instantly see what I mean.

I kept the structure of the pieces constant. It is as follows:  
bar for each chord  
bar for each chord  
modulate up one semitone  
bar for each chord  
bar for each chord

Each piece therefore consists of 4 bars.

The melody was generated by progressively adding random notes. However, the notes are not entirely random. Some constraints on the rhythm and pitch such as ensuring that on the main beats the current note of the melody is always one from the chord of that bar. The constraints are difficult to explain here in words, but should be easy enough to understand by looking at the source especially if you are familiar with reading and writing music.

Outputs with cheesy accompaniment:

[cheesy major 1-5-6-4 (m4a)](https://github.com/StuartMesham/files/blob/master/output_2_cheesy_major_1-5-6-4.m4a?raw=true)

[cheesy minor 1-4-7 (m4a)](https://github.com/StuartMesham/files/blob/master/output_4_cheesy_minor_1-4-7.m4a?raw=true)

Outputs with random accompaniment:

[random major 1-5-6-4 (m4a)](https://github.com/StuartMesham/files/blob/master/output_6_random_major_1-5-6-4.m4a?raw=true)

[random minor 1-4-7 (m4a)](https://github.com/StuartMesham/files/blob/master/output_8_random_minor_1-4-7.m4a?raw=true)

Enjoy!

Footnote:  
Yes, I apologise for the Netbeans generated Swing GUI. We live and we learn, right?
