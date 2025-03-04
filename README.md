# MNIST-Image-Recognition-Based-on-Xgboost-Algorithm-and-Features-Extraction
by ***Yingxin LIN***
### Introduction
- Different from the common practice of MNIST image recognition using *CNN* algorithm, I apply NumPy and OpenCV to extract relevant features from each MNIST figure, and then train a __*Xgboost*__ recognition model. After gradually adjusting parameters, the accuracy of the optimal model on the test set can reach 88%.
- In addition, since I've made extensive use of the __*broadcasting mechanism of NumPy*__ instead of loops when coding, the code can run at an excellent speed.
- I also define the handwritten numeral edge scanning function *totally based on NumPy*, which can scan the number of *on pixels* within image edge with excellent speed and precision in a short time. Some scanning results are shown below:
#### *Fig.1 Scanning from right to left (The first 49 pictures in MNIST)*
![fig.1](https://github.com/lyx66/MNIST-Image-Recognition-Based-on-Xgboost-Algorithm-and-Features-Extraction/blob/main/Scanning%20from%20right%20to%20left%20(The%20first%2049%20pictures%20in%20MNIST).png?raw=false)
#### *Fig.2 Scanning from top to bottom (The first 49 pictures in MNIST)*
![fig.2](https://github.com/lyx66/MNIST-Image-Recognition-Based-on-Xgboost-Algorithm-and-Features-Extraction/blob/main/Scanning%20from%20top%20to%20bottom%20(The%20first%2049%20pictures%20in%20MNIST).png?raw=false)
### Files loaded
- Train set: __*train-labels.gz* (label)__ + __*train-images-idx3-ubyte.gz* (featrues)__
- Test set: __*test-labels.gz* (label)__ + __*t10k-images-idx3-ubyte.gz* (featrues)__
### Tips
- It's necessary to unzip files suffixed with __*'.gz'*__ before running the code.
- You can learn more details from the PDF file [*Data ming report & Userguide (in Simplified Chinese).pdf*](https://github.com/lyx66/MNIST-Image-Recognition-Based-on-Xgboost-algorithm-and-Features-extraction/blob/main/Data%20ming%20report%20%26%20Userguide%20(in%20Simplified%20Chinese).pdf).
### Copyright notice
- AUTHOR: __*Yingxin LIN*__
- Company: *School of Finance, Central University of Finance and Economics* (CUFE)
- Contact: lyxurthebest@163.com or lyxurthebest@outlook.com
- The copyright belongs to __*Yingxin LIN*__ , 2021/08/11.
#### *Enjoy*（。＾▽＾) *! (...and extend/modify)* 😊
