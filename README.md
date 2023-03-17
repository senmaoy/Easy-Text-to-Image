# Introduction
To make text-to-image (T2I) easy（方便灌水）, this repository provide a collection of image models, training / validation scripts that aim to pull together a wide variety of T2I models.  We provide simple demos,  and experimental experiences from volunteers. 还有一个CCF B~C的相关中英文期刊会议列表
## Simple Demos
[Demo 1](https://github.com/Heavenhjs/demot2i) [Demo 2](https://github.com/Tryici/RAT-GAN)
## A Comprehensive Survey
[Awesome-Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image) Click here

## Repoduced-Results-of-text-to-image-models

We would like to maintain a list of repoduced results of text-to-image models. Please feel free to [open an issue]to add your results.

### Submit your results as a new issue and volunteers will add them to the summary list.
The results of each person matters. You are encouraged to submit your results and join us to help more people.

[Click here to submit](https://github.com/senmaoy/Repoduced-Results-of-text-to-image-models/issues/new/choose)

The submission formate is defined in [Submission Example](https://github.com/senmaoy/Repoduced-Results-of-text-to-image-models/issues/1). If you have more than one result, submit them in a single issue and summurize them in the title.



### <a name="list">Summary sheets</a>
In this sheet, we report the best reproduced results.

|    Paper    |  Method  |  Conference  |  Code |  IS(bird) | FID(bird)|IS(COCO) |FID(COCO)|IS(flower) |FID(flower)|
|   :------:  | :------:  | :------: | :------: |:------: |:------: |:------: |:------: |:------: |:------: |
| [DF-GAN]() | GAN | CVPR| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | 5.10 | 14.81 |- |   19.32   |     -      |      -      |
| [stack-GAN]() | GAN | CVPR| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | 3.70±.07 | 51.89 |8.45±.03 |   74.05   |  3.20±.01  |55.28|
| [LAFITE]() | GAN | arxiv| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | - | 9.25 |- |  -   |- |-|
| [stack++]() | GAN | Tpami| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | 4.04±.05 | 15.30 |8.30±.10 |   81.59   |3.26±.01 |48.68|
| [DCGAN]() | GAN | ICML| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | - | - |    -     |-|- |-|
| [RAT-GAN]() | GAN | arxiv| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | 5.36±.20 | 13.91 |- |   14.60   |4.09 |-|


In this sheet, we summarize the original results in the paper.

|    Paper    |  Method  |  Conference  |  Code |  IS(bird) | FID(bird)|IS(COCO) |FID(COCO)|IS(flower) |FID(flower)|
|   :------:  | :------:  | :------: | :------: |:------: |:------: |:------: |:------: |:------: |:------: |
| [DF-GAN]() | GAN | CVPR| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | 5.10 | 14.81 |- |   19.32   |     -      |      -      |
| [stack-GAN]() | GAN | CVPR| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | 3.70±.07 | 51.89 |8.45±.03 |   74.05   |  3.20±.01  |55.28|
| [LAFITE]() | GAN | arxiv| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | - | 9.25 |- |  -   |- |-|
| [stack++]() | GAN | Tpami| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | 4.04±.05 | 15.30 |8.30±.10 |   81.59   |3.26±.01 |48.68|
| [DCGAN]() | GAN | ICML| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | - | - |    -     |-|- |-|
| [RAT-GAN]() | GAN | arxiv| [Pytorch](https://github.com/Hzzone/DeepClustering.SSL) | 5.36±.20 | 13.91 |- |   14.60   |4.09 |-|

### <a name="Result List">Detailed Results</a>


 <a href="#2022">2022</a>
 - [DF-GAN: deep fusion generative adversarial networks for text-to-image synthesis`CVPR` `2022`](https://github.com/senmaoy/Easy-Text-to-Image/blob/main/Reproduce/DFGAN.json) 
 - [RAT-GAN：Recurrent Affine Transformation for Text-to-image Synthesis](https://github.com/Cwj1212) 
 - [LAFITE : Towards Language-Free Training for Text-to-Image Generation`CVPR` `2022`](https://github.com/senmaoy/Easy-Text-to-Image/blob/main/Reproduce/LAFITE.json) 
 - [SSAG:Text to Image Generation with Semantic-Spatial Aware GAN`CVPR` `2022`](https://github.com/senmaoy/Easy-Text-to-Image/blob/main/Reproduce/SSA-GAN.json)
<a href="#2017">2017</a>


<a href="#2018">2018</a>

- [StackGAN++:Realistic Image Synthesis with Stacked Generative Adversarial Networks `CVPR` `2018 `](https://github.com/senmaoy/Easy-Text-to-Image/blob/main/Reproduce/AttnGAN.json)


 <a href="#2016">2016</a>
 - [Generative adversarial text to image synthesis  `ICML` `2016`](https://github.com/senmaoy/Easy-Text-to-Image/blob/main/Reproduce/Generative%20text-to-image%20synthesis.json)

### <a name="list">Jornal sheets</a>
相关三区期刊列表
1、COMPUTER VISION AND IMAGE UNDERSTANDING
  
2、Image and Vision Computing
 
3、SIGNAL PROCESSING-IMAGE COMMUNICATION
 
4、JOURNAL OF VISUAL COMMUNICATION AND IMAGE REPRESENTATION
 


### <a name="list">Conference sheets</a>

# Contributors

|    Name   |  Results Submitted  |  Other Contribution |
|  :---------  | :------: | :------: |
| [Wenjun Chen](https://github.com/Cwj1212)  | 1 | -|
| [Shouxin Zhang](https://github.com/secularism)  | 0 | Routine maintenance |
| [Jingsong Su](https://github.com/Heavenhjs) | 2 | Build the demos |
| [Yutong Zhou](https://github.com/Yutong-Zhou-cv)  | - | Build the survey|





