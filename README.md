metis_catkin
=============

A catkin wrapper for metis http://glaros.dtc.umn.edu/gkhome/metis

下载metis-5.1.0.tar.gz时无法连接服务器
=============

去原始地址：
https://gitee.com/luhongquan66/thirdparty_library_binaries/raw/master/metis-5.1.0.tar.gz
https://github.com/luhongquan66/thirdparty_library_binaries/raw/master/metis-5.1.0.tar.gz
下载压缩包到本地

然后将CmakeList.txt中的
set(METIS_URL https://github.com/luhongquan66/thirdparty_library_binaries/raw/master/metis-5.1.0.tar.gz)
设置为本地路径：
e.g. set(METIS_URL /home/lhq/metis-5.1.0.tar.gz)
