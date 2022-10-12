# Code and Dataset of Paper 1765

An implementation code for NeurIPS-2022 paper ID "1765".

## Table of Contents

- [Background](#background)
- [Usage](#usage)
- [Dataset](#Dataset)
- [License](#License)

## Background
A new Spatial-Temporal Deepfake Detection and Localization (ST-DDL) network with the newly proposed Anchor-Mesh Motion (AMM) algorithm and Fusion Attention (FA) module. In addition, a new public forgery dataset, **ManualFake**, with over 16,000 videos, including the new properties such as the generation of commercial software, the transmission of online social networks, namely the Facebook (Post), Facebook (Messenger), Wechat (Mobile), Wechat (PC), YouTube, Whatsapp, and Tiktok.

<p align='center'>  
  <img src='https://github.com/paper1765/paper1765/blob/master/imgs/framework.jpg?raw=true' width='870'/>
</p>
<p align='center'>  
  <em>The framework of ST-DDL.</em>
</p>


## Usage

For pre-process the videos:
```bash
cd preprocess
python preprocess.py
```

For testing:
```bash
python test.py
```
Then the model will detect the videos in the `data/ManualFake_preview/` and save the results in the `res/` directory.

Note: The pre-trained weight can be downloaded from [here](https://drive.google.com/drive/folders/1vzvLCWBVR-iv6_Y9fetb5rvG_PD_jq56?usp=sharing).

<p align='center'>  
  <img src='https://github.com/paper1765/paper1765/blob/master/imgs/result.jpg?raw=true' width='480'/>
</p>
<p align='center'>  
  <em>Demo results of localization.</em>
</p>

## Dataset

We construct a new Deepfake dataset, namely **ManualFake**, that innovatively features commercial Deepfake software, online social network scenarios, and multi-source videos (e.g., online interviews). The full dataset can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1dT3A69sLi592RwAw_XfvOmLexNRX-7mf?usp=sharing). **Please do NOT share as relevant license is still in production. Thanks!**

<p align='center'>  
  <img src='https://github.com/paper1765/paper1765/blob/master/imgs/dataset.jpg?raw=true' width='480'/>
</p>
<p align='center'>  
  <em>The overview of ManualFake.</em>
</p>


## License
The ManualFake dataset is for non-commercial research and educational purposes only. Before we provide your access to download, please put your ACADEMIC email address in [Google Form](https://www.google.com) and the download link will be sent to you once the form is accepted.