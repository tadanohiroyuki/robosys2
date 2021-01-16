# ロボットシステム学 課題2　ROSのパッケージ  
---
# 使用環境＆ツール
* ubuntu20.04.1 LTS  
* ROS  
  * Noetic  
* Python3  
---  
# 実行動画
    リンク:[YouTube](https://youtu.be/eVCRS4W7XYA)  
---  
# インストール
```
cd ~/catkin_ws/src
git clone https://github.com/tadanohiroyuki/robosys2.git
cd ..
catkin_make
source ~/.bashrc
```  
---  
# ワークスペースの準備  
こちらの資料を参考にワークスペースを作成した
    リンク:(https://github.com/ryuichiueda/robosys2020/blob/master/md/ros.md)
---  
# 実行方法  

* 端末1$ roscore  
* 端末2$ chmod +x count.py  
    * 端末2$ rosrun mypkg count.py  
* 端末3$ rosrun mypkg twice.py
