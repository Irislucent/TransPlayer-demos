The following are the sound examples of paper: **TransPlayer: Timbre Style Transfer with Flexible Timbre Control**.

The sample rate is 16000 hz.

### One-to-one transfer
Here are examples of one-to-one transfer comparing to the [baseline GAN model](https://ojs.aaai.org/index.php/AAAI/article/view/3897)  
We trained the baseline GAN model on **guitar** and **piano** data, and trained TransPlayer on all intruments' data. 
This experiment is meant to show that TransPlayer can produce one-to-one transfer results comparable to the baseline, while TransPlayer can apply to more flexible choices of transferring pairs.

--- | Piano to Guitar     | Guitar to Piano
---- | -------- | -----
Source| <audio src="p2g_src.wav" preload="none" controls > </audio> | <audio src="g2p_src.wav" preload="none" controls > </audio>
Baseline| <audio src="p2g_bl.wav" preload="none" controls > </audio> | <audio src="g2p_bl.wav" preload="none" controls > </audio>
TransPlayer| <audio src="p2g_tp.wav" preload="none" controls > </audio> | <audio src="g2p_tp.wav" preload="none" controls > </audio>

### Many-to-many Transfer
We show some generated results when we change the source and target instrument in a flexible manner. The source music of every intrument is randomly selected from validation set.

Electric Piano -> Organ
<audio src="epiano_all_01_epiano_organ.wav" preload="none" controls > </audio>
Electric Piano -> Piano
<audio src="epiano_all_01_epiano_piano.wav" preload="none" controls > </audio>
Electric Piano -> Electric Piano (reconstruction)
<audio src="epiano_all_01_epiano_epiano.wav" preload="none" controls > </audio>
Flute -> Organ
<audio src="flute_all_03_flute_organ.wav" preload="none" controls > </audio>
Flute -> Trumpet
<audio src="flute_all_03_flute_trumpet.wav" preload="none" controls > </audio>
Flute -> Flute (reconstruction)
<audio src="flute_all_03_flute_flute.wav" preload="none" controls > </audio>
Trumpet -> Electric Piano
<audio src="trumpet_all_05_trumpet_epiano.wav" preload="none" controls > </audio>
Trumpet -> Flute 
<audio src="trumpet_all_05_trumpet_flute.wav" preload="none" controls > </audio>
Trumpet -> Organ
<audio src="trumpet_all_05_trumpet_organ.wav" preload="none" controls > </audio>
Trumpet -> Viola
<audio src="trumpet_all_05_trumpet_viola.wav" preload="none" controls > </audio>
Trumpet -> Trumpet (recontruction)
<audio src="trumpet_all_05_trumpet_trumpet.wav" preload="none" controls > </audio>
Piano -> Organ
<audio src="piano_all_00_piano_organ.wav" preload="none" controls > </audio>
Piano -> Electric Piano
<audio src="piano_all_00_piano_epiano.wav" preload="none" controls > </audio>
Piano -> Piano (reconstruction)
<audio src="piano_all_00_piano_piano.wav" preload="none" controls > </audio>

