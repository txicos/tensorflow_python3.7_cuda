As per April/2020 there is no official tensorflow package for CUDA 10.2.

The purpose of this page is to provide a tensorflow 2.2 wheel package to be 

used with python3.7 and CUDA 10.2.

download and install as:

`sudo pip3.7 install tensorflow-2.2.0rc2-cp37-cp37m-linux_x86_64.whl `

consider, also, reading [officil tensorflow pip installation](https://www.tensorflow.org/install/pip)





**Note:** tensorflow makes use of calls to operational system. Whenever these calls

return a string it will use the new decoding feature of python3. Sometimes the codec

used is plain *ASCII*, so any string containing special characters may generate runtime 

failures. It is advisable to change system language to plain *English*.

