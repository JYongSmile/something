服务器


nvidia-smi
source ~/.bashrc
ps -ef | grep 8868
rm -r /home/ai/Jiangyong/PPose3D
rm -r /data/ai/
cp -ri /data/ai/davidTeng/mask_pos/pos_dl/3d_Person_Pose/SVN/Person_Pose_3d/* /home/ai/Jiangyong/
cp -ri /data/ai/Sunjw/Person_Pose_Estimation/3D_pose/hgStarMap-3d/* /home/ai/Jiangyong/hgStarMap-3d/
cp -ri /data/ai/JF/kaggle/clouds/* /data/ai/Jiangyong/kaggle/clouds/

tar -xvf yolov3_coco.tar.gz

ps uax | grep python  
#看系统中运行的 python 进程
kill -9 PID 和 kill -KILL PID
#强制终止某进程
strace -p PID
#调试分析诊断


https://blog.csdn.net/qq_16559905/article/details/51743588
https://www.linuxidc.com/Linux/2019-09/160471.htm   #visual studio 远程 linux 

-out server.csr -config openssl.cnf


192.168.16.232 8080


cat /proc/version  查看系统版本号
cuda version   cat /usr/local/cuda/version.txt
cudnn       cat /usr/local/cuda/include/cudnn.h | grep CUDNN_MAJOR -A 2


