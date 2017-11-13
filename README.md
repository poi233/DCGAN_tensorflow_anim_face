# DCGAN_tensorflow_anim_face
An animation face generator using [DCGAN](https://github.com/carpedm20/DCGAN-tensorflow)<br>
![tensorflow_version](https://img.shields.io/badge/tensorflow-0.12.1+-green.svg)
![python_version](https://img.shields.io/badge/pyton-2.7/3.3+-green.svg)
![scipy](https://img.shields.io/badge/dependencies-scipy-blue.svg)
![pillow](https://img.shields.io/badge/dependencies-pillow-blue.svg)
![moviepy](https://img.shields.io/badge/dependencies-moviepy(optional)-blue.svg)

## Usage
<code>python main.py --input_height 96 --input_width 96 --output_height 48 --output_width 48  --dataset faces --crop --train --epoch 300 --input_fname_pattern "*.jpg" --visualize
</code>

* dataset: dir name of dataset in /data
* train: True-train False-test

## Data
link:http://pan.baidu.com/s/1c2Gqucg  password:4eh3

## Data Obtain
data_scratch/crawl.py: Get pictures from [KONACHAN](http://link.zhihu.com/?target=http%3A//konachan.net/)<br>
data_scratch/scratch_face.py: Get faces from images above<br>
data_scratch/AnimCrawl.ipynb: Crawl HD landscape from [KONACHAN](http://link.zhihu.com/?target=http%3A//konachan.net/)<br>


## Results
result after 1 epoch<br>
![epoch1](samples_try0(6epoch)/train_01_0058.png)<br>
result after 5 epoch<br>
![epoch5](samples_try0(6epoch)/train_05_0094.png)<br>
result after 10 epoch<br>
![epoch10](samples_try3(10epoch)/train_00_0798.png)<br>
result after 30 epoch<br>
![epoch30](samples_try4(10epoch)/train_09_0829.png)<br>
result after 100 epoch<br>
![epoch100](samples_try7(63epoch)/train_60_0798.png)<br>


## Reference
https://zhuanlan.zhihu.com/p/24767059