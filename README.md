The following are the sound examples of paper: **TransPlayer: Timbre Style Transfer with Flexible Timbre Control**

### One-to-one transfer
Here are examples of one-to-one transfer comparing to the [baseline GAN model](https://ojs.aaai.org/index.php/AAAI/article/view/3897)  
We trained the baseline GAN model on **guitar** and **piano** data, and trained TransPlayer on all intruments' data. 
This experiment is meant to show that TransPlayer can produce one-to-one transfer results comparable to the baseline, while TransPlayer can apply to more flexible choices of transferring pairs.

--- | Piano to Guitar     | Guitar to Piano
---- | -------- | -----
Source| <audio src="p2g_src.wav" preload="none"  > </audio> | <audio src="g2p_src.wav" preload="none"  > </audio>
Baseline| <audio src="p2g_bl.wav" preload="none"  > </audio> | <audio src="g2p_bl.wav" preload="none"  > </audio>
TransPlayer| <audio src="p2g_tp.wav" preload="none"  > </audio> | <audio src="g2p_tp.wav" preload="none"  > </audio>

### Many-to-many Transfer
We show some generated results here (source music randomly selected from validation set).

Electric Piano -> Organ

Electric Piano -> Piano





Transferred by baseline:
<audio src="p2g_bl.wav" preload="none"  > </audio>
Transferred by TransPlayer:
<audio src="p2g_tp.wav" preload="none"  > </audio>
