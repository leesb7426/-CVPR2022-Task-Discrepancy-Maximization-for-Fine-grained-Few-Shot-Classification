# -CVPR2022-Task-Discrepancy-Maximization-for-Fine-grained-Few-Shot-Classification
Official PyTorch Repository of "Task Discrepancy Maximization for Fine-grained Few-Shot Classification" (CVPR 2022 Oral Paper)


# Task-Discrepancy-Maximization-for-Fine-grained-Few-Shot-Classification


<!--
  Title: 
  Description: This is the code for .
  Author: 
  -->

<figure style="text-align: center;">
  <figcaption style="text-align: center;"><b>Overall Framework</b></figcaption>
    <img src=figures/overall.png width="95%"> 
</figure>

<!-- <figure style="text-align: center;">
  <p align="center">
  <figcaption style="text-align: center;"><b>Support Attention Module</b></figcaption>
    <img src=figures/SAM.png width="45%"> 
  </p>
</figure>

<figure style="text-align: center;">
  <p align="center">
  <figcaption style="text-align: center;"><b>Query Attention Module</b></figcaption>
    <img src=figures/QAM.png width="45%"> 
  </p>
</figure> -->


<!-- 
<p align="center">
    <img src=figures/SAM.png width="45%"> 
    <img src=figures/QAM.png width="45%"> 
  <figcaption align = "center"><b>SAM     QAM</b></figcaption>
</p> -->


## Data Preparation

Please download the dataset before you run the code.

CUB200: [CUB200 download link](https://drive.google.com/file/d/1hbzc_P1FuxMkcabkgn9ZKinBwW683j45/view)

Aircraft: [Aircraft download link](https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/archives/fgvc-aircraft-2013b.tar.gz)

met-iNat : [met_iNat]()

Stanford-Cars : [Stanford-Cars]()

Stanford-Dogs : [Stanford-Dogs]()

Oxford-Pets : [Oxford-Pets]()



## Pretrained Weights

 Method | Dataset | 1-shot | 5-shot | Model file
 -- | -- | -- | -- | --
  |  |  |  | [model]()
 |  |  |  | [model]()
  |  |   | | [model]()

## Usage

### Requirement
All the requirements to run the code are in requirements.txt
You can download requirements by running below script.
```
pip install -r requirements.txt
```

### Train
We provide scripts for training.
```
python train_aaa.py --dataset cub200
```

## Citation
If you find TDM helpful for your works, please consider citing:
```
Task Discrepancy Maximization for Fine-grained Few-Shot Classification
```

## Contact
If there are any questions, please feel free to contact with the authors:  SuBeen Lee (leesb7426@gmail.com) WonJun Moon (wjun0830@gmail.com). Thank you.
