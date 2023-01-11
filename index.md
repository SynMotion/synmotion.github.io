<!-- <style>
.markdown-body h1 {
    border-bottom: none
}
.markdown-body h2 {
    border-bottom: 2px solid grey;
}
.markdown-body {
    border-bottom: 2px solid black;
    padding-left: 65px !important;
    padding-right: 65px !important;
    box-shadow: 5px 2px 2px grey;
    background: white;
}
body {
    background: #c1bebe;
}
</style>
<div>
    <br><br><br>
    <h1 style="text-align:center;"><b>ASGaze: Gaze Tracking on Any Surface with Your Phone</b></h1>
<!--     <p style="font-size:20px;text-align:center;"><b>Improving Non-Cooperative Iris Tracking</b></p> -->
</div> 

# SynMotion: Synthesized Millimeter-Waves for Human Motion Sensing 
## Overview
In this project, we presents SynMotion, a new mmWave-based human motion sensing system. Its novelty lies in harvesting available vision-based human motion datasets, for knowing the coordinates of body skeletal points under different motions, to synthesize mmWave sensing signals that bounce off the human body, so that the synthesized signals could inherit labels (skeletal coordinates and the name of each motion) from vision-based datasets directly. SynMotion demonstrates the ability to generate such labeled synthesized data at high quality to address the training-data scarcity issue and enable two sensing services that can work with commercial radars, including 1) zero-shot activity recognition, where the classifier reads real mmWaves for recognition, but it is only trained on synthesized data; and 2) body skeleton tracking with few/zero-shot learning on real mmWaves. To design SynMotion, we address the challenges of both the inherent complication of mmWave synthesis and the micro-level differences compared to real mmWaves. Extensive experiments show that SynMotion outperforms the latest zero-shot mmWave-based activity recognition method. For skeleton tracking, SynMotion achieves comparable performance to the state-of-the-art mmWave-based method trained on the labeled mmWaves, and SynMotion can further outperform it for the unseen users.
## Code
Our code and data samples are open source: [SynMotion](https://github.com/Zxttttttt/SynMotion)
## Citation
If you find our work useful in your research, please consider citing:

```Coming soon...```
