<style>
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
    <h1 style="text-align:center;"><b>SynMotion: Synthesized Millimeter-Waves for Human Motion Sensing </b></h1>
<!--     <p style="font-size:20px;text-align:center;"><b>Improving Non-Cooperative Iris Tracking</b></p> -->
</div>




## **Overview**

In this project, we presents SynMotion, a new mmWave-based human motion sensing system. Its novelty lies in harvesting available vision-based human motion datasets, for knowing the coordinates of body skeletal points under different motions, to synthesize mmWave sensing signals that bounce off the human body, so that the synthesized signals could inherit labels (skeletal coordinates and the name of each motion) from vision-based datasets directly. SynMotion demonstrates the ability to generate such labeled synthesized data at high quality to address the training-data scarcity issue and enable two sensing services that can work with commercial radars, including 1) zero-shot activity recognition, where the classifier reads real mmWaves for recognition, but it is only trained on synthesized data; and 2) body skeleton tracking with few/zero-shot learning on real mmWaves. To design SynMotion, we address the challenges of both the inherent complication of mmWave synthesis and the micro-level differences compared to real mmWaves. Extensive experiments show that SynMotion outperforms the latest zero-shot mmWave-based activity recognition method. For skeleton tracking, SynMotion achieves comparable performance to the state-of-the-art mmWave-based method trained on the labeled mmWaves, and SynMotion can further outperform it for the unseen users.


## Publication

**Synthesized Millimeter-Waves for Human Motion Sensing**

**Xiaotong Zhang**, Zhenjiang Li, Jin Zhang

ACM SenSys, 2022

<a href="https://dl.acm.org/doi/pdf/10.1145/3560905.3568542">[pdf]</a>  <a href="https://github.com/Zxttttttt/SynMotion">[code]</a>  <a href="https://www.cs.cityu.edu.hk/~zhenjili/2022-SenSys-Synmotion-Slides.pdf">[slides]</a>


## Citation

If you find our work useful in your research, please consider citing:

```
@inproceedings{zhang2022synthesized,
  title={Synthesized Millimeter-Waves for Human Motion Sensing},
  author={Zhang, Xiaotong and Li, Zhenjiang and Zhang, Jin},
  booktitle={Proceedings of the 20th ACM Conference on Embedded Networked Sensor Systems},
  pages={377--390},
  year={2022}
}
```
