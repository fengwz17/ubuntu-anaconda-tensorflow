# ubuntu-anaconda-tensorflow
ubuntu下用anaconda配置环境
## 1. https://www.anaconda.com/download 下载anaconda
## 2. $bash ~/Downloads/Anaconda3-5.0.1-Linux-x86_64.sh
 注意按实际路径和文件名修改
 
 注意询问环境变量的时候默认为no，要手选yes，否则用$export PATH=/home/xxxxx/anaconda3/bin:$PATH添加环境变量，然后关闭终端并重新开一个，或者执行命令$source ~/.bashrc使上面更新的环境变量生效
## 3. $conda create -n name python=3.6 创建conda环境
 $source activate name激活环境
 
 $source deactivate退出环境
## 4. 激活环境下安装tensorflow 
$conda install --channel https://conda.anaconda.org/jjh_cio_testing tensorflow-gpu

其他相关环境安装见链接：https://blog.csdn.net/liuyan20062010/article/details/78872729

