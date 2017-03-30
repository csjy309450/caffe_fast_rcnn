## caffe_fast_rcnn
Based on caffe for ssd(https://github.com/weiliu89/caffe/tree/ssd) [caffe base version **1.0.0-rc3**]
For myself, the project is forked from git(https://github.com/owphoo/caffe_fast_rcnn)

It was tested on SSD, Fast-RCNN, Faster-RCNN(If you want to use **cudnn v5**)
(In fact this caffe version was available on **cuda toolkit-8.0** and **cudnn v5.1**)

### requirement pkgs
Our caffe_fast_rcnn install in **Ubuntu 16.04STL**
Other dependence we have installed was:

 - numpy ( 1.11.0 )
 - scipy ( 0.17.0 )
 - matplotlib ( 1.5.1 )
 - pandas ( 0.17.1 )
 - sympy ( 0.7.6.1 )
 - nose ( 1.3.7 )
 - opencv（3.1.0）

### compile
cd to CAFFE_ROOT

make -j8

make pycaffe

(installation details refering to http://www.cnblogs.com/supersponge/p/6490931.html)
