---
layout: page
title: 'Results: Bonsai'
category: Algorithms
---

Comparison to uncompressed methods, compressed methods and prediction costs on the Arduino Uno are reported here.

### Data Statistics

|**Dataset**| **# Train** | **# Test**| **# Features**|
|-----------|-------------|-----------|--------------|
| Chars4K-2 | 4,397       | 1,886     | 400          |
| WARD-2    | 4,503       | 1,931     | 1,000        |
| RTWhalte-2| 5,265       | 5,264     | 2,000        |
| Eye-2     | 456         | 196       | 8,192        |          
| MNIST-2   | 60,000      | 10,000    | 784          |
| USPS-2    | 7,291       | 2,007     | 256          |
| CIFAR10-2 | 50,000      | 10,000    | 400          |
| CUReT-61  | 4,204       | 1,403     | 610          |
| MNIST-10  | 60,000      | 10,000    | 784          |
| Chars4K-62| 4,397       | 1,886     | 400          |
| Bing L3/L4| 704,841     | 123,268   | 50           |


### Comparison to Uncompressed Models

![Comparison of accuracy with uncompressed models][img_001]

![Comparison of model size with uncompressed models][img_002]


[img_001]: {{ site.baseurl}}/img/BonsaiResults/uncompressed_accuracy.png
[img_002]: {{ site.baseurl}}/img/BonsaiResults/uncompressed_model_size.png