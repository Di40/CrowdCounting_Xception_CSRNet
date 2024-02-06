# Crowd Counting using Xception and CSRNet

This is our final project for the Vision and Cognitive Systems course at the University of Padua.

Task: Crowd Counting

Dataset: [Mall crowd counting dataset](https://personal.ie.cuhk.edu.hk/~ccloy/downloads_mall_dataset.html)

Approaches: 

- Regression-based: [Xception](https://www.tensorflow.org/api_docs/python/tf/keras/applications/xception/Xception)
    - MAE: 1.5996
- Density-based: [CSRNet](https://arxiv.org/abs/1802.10062)
    - MAE: 3.44 (with pre-training) and 2.72 (CSRNet as a feature extractor)

Group members:
- Dejan Dichoski
- Maksim Kokot
- Suleyman Erim
