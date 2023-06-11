# mmlabwork
## 第一节课
【课程名称】人体姿态估计与MMPose
【课程链接】https://www.bilibili.com/video/BV1kk4y1L7Xb/?spm_id_from=333.999.0.0&vd_source=357ecabf829bae4a793fa45fb329fff0
【课程说明】人体姿态估计（Human Pose Estimation）是计算机理解人类动作、行为必不可少的一步，本次课程涵盖人体姿态估计的介绍与应用、2D 姿态估计、3D 姿态估计、DensePose、Body Mesh 以及 MMPose 等内容。
【讲师介绍】卢策吾 上海交通大学电院计算机系教授、博士生导师。
【学习形式】录播+社群答疑
【作业布置】本次课程为理论课，无作业安排

## 第三节课  6月2日
【课程名称】MMPose代码教程
【课程链接】3个都是噢
安装MMDetection和MMPose：https://www.bilibili.com/video/BV1Pa4y1g7N7
MMDetection三角板目标检测：https://www.bilibili.com/video/BV1Lm4y1879K
MMPose、RTMPose三角板关键点检测：https://www.bilibili.com/video/BV12a4y1u7sd
【讲师介绍】张子豪  OpenMMLab算法工程师
【学习形式】录播+社群答疑
【作业布置】本次课程有作业，详情见本班的Github issue，提交时间为6月4日晚12点。@所有人

## 第四课MMPretrian
https://www.bilibili.com/video/BV1PN411y7C1/?spm_id_from=333.999.0.0&vd_source=3f43a5e68fd37f6834c6c5688ee3bad0

## 第五节课  6月6日
【课程名称】MMPretrain代码课
【课程链接】https://www.bilibili.com/video/BV1Ju4y1Z7ZE/?spm_id_from=333.999.0.0
【讲师介绍】马泽润  OpenMMLab算法工程师
【学习形式】录播+社群答疑
【作业布置】本次课程有作业，详情见本班的Github issue，提交时间为6月11日晚12点。

## 第六节课  6月7日
【课程名称】目标检测与MMDetection
【课程链接】https://www.bilibili.com/video/BV1Ak4y1p7W9/?share_source=copy_web&vd_source=402147fbebb10633da56a29f470811e2
【讲师介绍】王若晖  OpenMMLab青年研究员
【学习形式】录播+社群答疑
【作业布置】本次课程为理论课，无作业安排。

## 第六节课  6月8日
【课程名称】MMDetection代码课
【课程链接】https://www.bilibili.com/video/BV1Tm4y1q7fy/?vd_source=7a863785a93380d229ded645710a0031
【讲师介绍】深度眸  OpenMMLab算法工程师
【学习形式】录播+社群答疑
【作业布置】本次课程有作业，详情见本班的Github issue，提交时间为6月11日晚12点。

## 作业仓库
学员手册的链接:
https://aicarrier.feishu.cn/docx/QUxadeWW2op8UGxLfaOc1TtanQb
直播回放在哪里
都在B站OpenMMLab的视频里，我也会在每次课后发一次链接
PPT在哪里
1. 在【OpenMMLab】公众号回复‘AI实战营’即可获取，部分PPT需要获取老师的授权，不一定能及时更新             
作业:
CSDN发布笔记，可以在这里发哈  默认直接发在社区@所有人 https://bbs.csdn.net/forums/OpenMMLab-01
飞书链接（提交笔记和作业的链接）:
https://zpfi333jmu.feishu.cn/sheets/DN5nsJv5PhyzEstXkMLcTbp3nkf?from=from_copylink
第一次作业的仓库:
作业的仓库在这里哦（包含数据集，大家把数据集下载到本地）:https://github.com/open-mmlab/OpenMMLabCamp/issues/91
第二次作业的仓库：
https://github.com/open-mmlab/OpenMMLabCamp/issues/112
第三次作业的仓库:
https://github.com/open-mmlab/OpenMMLabCamp/issues/133

## 其他内容
---------------------------------
铛铛~浦源内容平台招募体验官参与内测啦！ 浦源内容平台是面向 AI 开发者和使用者的一站式应用开发平台，用户可以交互式地体验各种有趣的AI应用，也可以轻松地将研究成果变成开箱即用的 Demo，诚邀大家作为体验官参与内测！对于积极反馈和贡献的内测体验官大人，我们将联合 OpenMMLab 提供优质的周边奖励和后续活动的优先权益喔~招募链接：https://wj.qq.com/s2/12450333/75db/ ，或微信扫描海报二维码报名——
-----------------------------
总结下大家在环境安装配置和作业提交上的问题，已经成功的同学可以巩固下，还有问题的同学可以对照排查：
1、openmim、mmcv、mmengine及mm其他库的安装顺序问题(安装顺序错了，会存在版本不对齐和相互链接不上的问题)
2、python版本问题—>建议版本在python3.6～3.9之间
3、pytorch版本问题—>对于一些cuda版本较高的同学，不建议直接用pytorch2.0，安装与cuda对应的即可；如果是使用cpu的，则可以不考虑cuda版本
4、系统环境：这里有Win、macOS、Linux，win环境需要尤其注意环境变量的配置和包含中文名称路径的问题，Linux环境很多安装参考教程直接用终端install即可，macOS与Linux类似
5、openmmlab库的版本，新手可以参考子豪兄对应代码中最新日期的示例，已经熟悉的同学可以去参考对应的文档，文档里面有较为详细的解释和说明；
6、git配置：win的安装配置可以参考：https://blog.csdn.net/Wmeihua/article/details/123257553；
Linux和macOS可以参考这个：https://blog.51cto.com/gblfy/5653420
提交作业，可以先在GitHub上新建一个仓库，然后git add [files] 把文件提交到暂存区，git commit -m "提交信息"，最后git push就可以把代码上传到仓库啦，把这个仓库链接用评论的方式提交到https://github.com/open-mmlab/OpenMMLabCamp/issues/91的issue上即可

