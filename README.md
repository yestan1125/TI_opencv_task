# 2023年电赛E题上位机程序开源
代码在香橙派5plus上运行，main(pc).py为pc可运行调试版本  
使用时需要安装opencv库与wiringpi（香橙派）库  

0为输出红色激光与绿色激光的偏差， 1为输出激光点与扫矩形目标点的偏差, 2为输出激光点与一直线往复运动的目标点的偏差，模式4为输出激光点与1目标点的偏差  
由于实际检测时仍然有可能出现部分误判，加入卡尔曼滤波预测激光点位置，参数未调，实际效果存疑  
通讯协议类似“#P1=xx.x!”,发送给下位机  
***
喜欢的话欢迎支持  
github主页[主页](https://github.com/simplemaxq)  
bilibili主页[主页](https://space.bilibili.com/419762243?spm_id_from=333.880.0.0)


以下为 TI_labortory 寒假集训任务
[Uploading OPENCV任务（软件）.pdf…]()
因为时间太短，代码还有很多瑕疵，欢迎pr😇😇😇
