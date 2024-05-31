# rl_depoly
在go2 jestion上使用unitree_guide

##### 安装jetpack
cat /etc/nv_tegra_release

sudo bash -c 'echo "deb https://repo.download.nvidia.com/jetson/common r34.1 main" >> /etc/apt/sources.list.d/nvidia-l4t-apt-source.list'

sudo bash -c 'echo "deb https://repo.download.nvidia.com/jetson/t234 r34.1 main" >> /etc/apt/sources.list.d/nvidia-l4t-apt-source.list'

注意版本号和导入的链接是否对应
go2上是35.3保留两位即可

sudo apt update

sudo apt dist-upgrade

sudo reboot

sudo apt install nvidia-jetpack

配置cuda cudnn

安装anaconda

安装pytorch

参考：https://blog.csdn.net/weixin_43702653/article/details/129249585
