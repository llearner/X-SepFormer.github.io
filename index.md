# X-SepFormer

## Paper
X-SepFormer: End-to-end Speaker Extraction Network with Explicit Optimization on Speaker Confusion

## Introduction
This is a [demo](https://llearner.github.io/X-SepFormer.github.io/) for our paper **X-SepFormer: End-to-end Speaker Extraction Network with Explicit Optimization on Speaker Confusion**. 

We list some speech examples of our baseline system, and compare our proposed methods with the baseline.

If you have any questions or suggestions, please contact liukai89@huawei.com

## Examples
We divided examples into three categories: 

1. Female-Male Mixtures

2. Male-Male Mixtures

3. Female-Female Mixtures

For better display, we divided each category into 2 groups.

### 1. Female - Male Mixtures (Group 1 & 2)

| <center>Mixture</center> | <center>Ground-Truth</center> | <center>Baseline</center> | <center>X-SepFormer(S2)*</center> | <center>X-SepFormer(S3)*</center> | 
| :--- | :--- | :--- | :--- | :--- |
|<audio src="examples/Female-Male/item4792_mix.wav" controls preload></audio>|<audio src="examples/Female-Male/item4792_source1.wav" controls preload></audio>|<audio src="examples/Female-Male/baseline/item4792_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Male/x-sepformer-s2/item4792_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Male/x-sepformer-s3/item4792_source1hat.wav" controls preload></audio>|
|<img src="examples/Female-Male/item4792_mix.JPG"/>|<img src="examples/Female-Male/item4792_source1.JPG"/>|<img src="examples/Female-Male/baseline/item4792_source1hat.JPG"/>|<img src="examples/Female-Male/x-sepformer-s2/item4792_source1hat.JPG"/>|<img src="examples/Female-Male/x-sepformer-s3/item4792_source1hat.JPG"/>|
|<audio src="examples/Female-Male/item388_mix.wav" controls preload></audio>|<audio src="examples/Female-Male/item388_source1.wav" controls preload></audio>|<audio src="examples/Female-Male/baseline/item388_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Male/x-sepformer-s2/item388_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Male/x-sepformer-s3/item388_source1hat.wav" controls preload></audio>|
|<img src="examples/Female-Male/item388_mix.JPG"/>|<img src="examples/Female-Male/item388_source1.JPG"/>|<img src="examples/Female-Male/baseline/item388_source1hat.JPG"/>|<img src="examples/Female-Male/x-sepformer-s2/item388_source1hat.JPG"/>|<img src="examples/Female-Male/x-sepformer-s3/item388_source1hat.JPG"/>|

| <center>Mixture</center> | <center>Ground-Truth</center> | <center>Baseline</center> | <center>X-SepFormer(S2)*</center> | <center>X-SepFormer(S3)*</center> | 
| :--- | :--- | :--- | :--- | :--- |
|<audio src="examples/Female-Male/item3616_mix.wav" controls preload></audio>|<audio src="examples/Female-Male/item3616_source1.wav" controls preload></audio>|<audio src="examples/Female-Male/baseline/item3616_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Male/x-sepformer-s2/item3616_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Male/x-sepformer-s3/item3616_source1hat.wav" controls preload></audio>|
|<img src="examples/Female-Male/item3616_mix.JPG"/>|<img src="examples/Female-Male/item3616_source1.JPG"/>|<img src="examples/Female-Male/baseline/item3616_source1hat.JPG"/>|<img src="examples/Female-Male/x-sepformer-s2/item3616_source1hat.JPG"/>|<img src="examples/Female-Male/x-sepformer-s3/item3616_source1hat.JPG"/>|
|<audio src="examples/Female-Male/item298_mix.wav" controls preload></audio>|<audio src="examples/Female-Male/item298_source1.wav" controls preload></audio>|<audio src="examples/Female-Male/baseline/item298_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Male/x-sepformer-s2/item298_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Male/x-sepformer-s3/item298_source1hat.wav" controls preload></audio>|
|<img src="examples/Female-Male/item298_mix.JPG"/>|<img src="examples/Female-Male/item298_source1.JPG"/>|<img src="examples/Female-Male/baseline/item298_source1hat.JPG"/>|<img src="examples/Female-Male/x-sepformer-s2/item298_source1hat.JPG"/>|<img src="examples/Female-Male/x-sepformer-s3/item298_source1hat.JPG"/>|

### 2. Male - Male Mixtures (Group 1 & 2)

| <center>Mixture</center> | <center>Ground-Truth</center> | <center>Baseline</center> | <center>X-SepFormer(S2)*</center> | <center>X-SepFormer(S3)*</center> | 
| :--- | :--- | :--- | :--- | :--- |
|<audio src="examples/Male-Male/item2719_mix.wav" controls preload></audio>|<audio src="examples/Male-Male/item2719_source1.wav" controls preload></audio>|<audio src="examples/Male-Male/baseline/item2719_source1hat.wav" controls preload></audio>|<audio src="examples/Male-Male/x-sepformer-s2/item2719_source1hat.wav" controls preload></audio>|<audio src="examples/Male-Male/x-sepformer-s3/item2719_source1hat.wav" controls preload></audio>|
|<img src="examples/Male-Male/item2719_mix.JPG"/>|<img src="examples/Male-Male/item2719_source1.JPG"/>|<img src="examples/Male-Male/baseline/item2719_source1hat.JPG"/>|<img src="examples/Male-Male/x-sepformer-s2/item2719_source1hat.JPG"/>|<img src="examples/Male-Male/x-sepformer-s3/item2719_source1hat.JPG"/>|
|<audio src="examples/Male-Male/item4101_mix.wav" controls preload></audio>|<audio src="examples/Male-Male/item4101_source1.wav" controls preload></audio>|<audio src="examples/Male-Male/baseline/item4101_source1hat.wav" controls preload></audio>|<audio src="examples/Male-Male/x-sepformer-s2/item4101_source1hat.wav" controls preload></audio>|<audio src="examples/Male-Male/x-sepformer-s3/item4101_source1hat.wav" controls preload></audio>|
|<img src="examples/Male-Male/item4101_mix.JPG"/>|<img src="examples/Male-Male/item4101_source1.JPG"/>|<img src="examples/Male-Male/baseline/item4101_source1hat.JPG"/>|<img src="examples/Male-Male/x-sepformer-s2/item4101_source1hat.JPG"/>|<img src="examples/Male-Male/x-sepformer-s3/item4101_source1hat.JPG"/>|

| <center>Mixture</center> | <center>Ground-Truth</center> | <center>Baseline</center> | <center>X-SepFormer(S2)*</center> | <center>X-SepFormer(S3)*</center> | 
| :--- | :--- | :--- | :--- | :--- |
|<audio src="examples/Male-Male/item610_mix.wav" controls preload></audio>|<audio src="examples/Male-Male/item610_source1.wav" controls preload></audio>|<audio src="examples/Male-Male/baseline/item610_source1hat.wav" controls preload></audio>|<audio src="examples/Male-Male/x-sepformer-s2/item610_source1hat.wav" controls preload></audio>|<audio src="examples/Male-Male/x-sepformer-s3/item610_source1hat.wav" controls preload></audio>|
|<img src="examples/Male-Male/item610_mix.JPG"/>|<img src="examples/Male-Male/item610_source1.JPG"/>|<img src="examples/Male-Male/baseline/item610_source1hat.JPG"/>|<img src="examples/Male-Male/x-sepformer-s2/item610_source1hat.JPG"/>|<img src="examples/Male-Male/x-sepformer-s3/item610_source1hat.JPG"/>|
|<audio src="examples/Male-Male/item4332_mix.wav" controls preload></audio>|<audio src="examples/Male-Male/item4332_source1.wav" controls preload></audio>|<audio src="examples/Male-Male/baseline/item4332_source1hat.wav" controls preload></audio>|<audio src="examples/Male-Male/x-sepformer-s2/item4332_source1hat.wav" controls preload></audio>|<audio src="examples/Male-Male/x-sepformer-s3/item4332_source1hat.wav" controls preload></audio>|
|<img src="examples/Male-Male/item4332_mix.JPG"/>|<img src="examples/Male-Male/item4332_source1.JPG"/>|<img src="examples/Male-Male/baseline/item4332_source1hat.JPG"/>|<img src="examples/Male-Male/x-sepformer-s2/item4332_source1hat.JPG"/>|<img src="examples/Male-Male/x-sepformer-s3/item4332_source1hat.JPG"/>|

### 3. Female - Female Mixtures (Group 1 & 2)

| <center>Mixture</center> | <center>Ground-Truth</center> | <center>Baseline</center> | <center>X-SepFormer(S2)*</center> | <center>X-SepFormer(S3)*</center> | 
| :--- | :--- | :--- | :--- | :--- |
|<audio src="examples/Female-Female/item3573_mix.wav" controls preload></audio>|<audio src="examples/Female-Female/item3573_source1.wav" controls preload></audio>|<audio src="examples/Female-Female/baseline/item3573_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Female/x-sepformer-s2/item3573_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Female/x-sepformer-s3/item3573_source1hat.wav" controls preload></audio>|
|<img src="examples/Female-Female/item3573_mix.JPG"/>|<img src="examples/Female-Female/item3573_source1.JPG"/>|<img src="examples/Female-Female/baseline/item3573_source1hat.JPG"/>|<img src="examples/Female-Female/x-sepformer-s2/item3573_source1hat.JPG"/>|<img src="examples/Female-Female/x-sepformer-s3/item3573_source1hat.JPG"/>|
|<audio src="examples/Female-Female/item3979_mix.wav" controls preload></audio>|<audio src="examples/Female-Female/item3979_source1.wav" controls preload></audio>|<audio src="examples/Female-Female/baseline/item3979_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Female/x-sepformer-s2/item3979_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Female/x-sepformer-s3/item3979_source1hat.wav" controls preload></audio>|
|<img src="examples/Female-Female/item3979_mix.JPG"/>|<img src="examples/Female-Female/item3979_source1.JPG"/>|<img src="examples/Female-Female/baseline/item3979_source1hat.JPG"/>|<img src="examples/Female-Female/x-sepformer-s2/item3979_source1hat.JPG"/>|<img src="examples/Female-Female/x-sepformer-s3/item3979_source1hat.JPG"/>|

| <center>Mixture</center> | <center>Ground-Truth</center> | <center>Baseline</center> | <center>X-SepFormer(S2)*</center> | <center>X-SepFormer(S3)*</center> | 
| :--- | :--- | :--- | :--- | :--- |
|<audio src="examples/Female-Female/item1667_mix.wav" controls preload></audio>|<audio src="examples/Female-Female/item1667_source1.wav" controls preload></audio>|<audio src="examples/Female-Female/baseline/item1667_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Female/x-sepformer-s2/item1667_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Female/x-sepformer-s3/item1667_source1hat.wav" controls preload></audio>|
|<img src="examples/Female-Female/item1667_mix.JPG"/>|<img src="examples/Female-Female/item1667_source1.JPG"/>|<img src="examples/Female-Female/baseline/item1667_source1hat.JPG"/>|<img src="examples/Female-Female/x-sepformer-s2/item1667_source1hat.JPG"/>|<img src="examples/Female-Female/x-sepformer-s3/item1667_source1hat.JPG"/>|
|<audio src="examples/Female-Female/item1117_mix.wav" controls preload></audio>|<audio src="examples/Female-Female/item1117_source1.wav" controls preload></audio>|<audio src="examples/Female-Female/baseline/item1117_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Female/x-sepformer-s2/item1117_source1hat.wav" controls preload></audio>|<audio src="examples/Female-Female/x-sepformer-s3/item1117_source1hat.wav" controls preload></audio>|
|<img src="examples/Female-Female/item1117_mix.JPG"/>|<img src="examples/Female-Female/item1117_source1.JPG"/>|<img src="examples/Female-Female/baseline/item1117_source1hat.JPG"/>|<img src="examples/Female-Female/x-sepformer-s2/item1117_source1hat.JPG"/>|<img src="examples/Female-Female/x-sepformer-s3/item1117_source1hat.JPG"/>|

### Links

[[Demo GitHub](https://llearner.github.io/X-SepFormer.github.io/)]
