# 21tb 时代光华 自动学习



>   原版来自https://github.com/iloghyr/21tb_robot
>
>   初级前端，因公司需要学分，在github找到了上面的原版
>
>   同事优化了其获取听课列表逻辑
>
>   在这基础上，学了一个月python，尝试着自己写了一下
>
>   主要的视频观看逻辑照搬了原版
>
>   很多方面都没有考虑到，会慢慢更新上去
>
>   ps：需答题的课程，水平有限，暂不考虑

### 前期准备：
    
    修改api.conf：
    corpcode = 公司标识
    host = 公司听课主页地址
    
    

### 启动说明：

    无python环境，双击study.exe
    python环境下，有安装python3,双击study.bat

### v1.1

    更新内容：
    
	1、无需安装python，直接双击study.exe即可运行
	2、可视化界面，中文日志输出
	3、自动选课，在已选课程都学完后，自动选择评估课程（只需课程评估即可获得学分）
	4、修改了一些逻辑和bug
   
    
### v1.2

    更新内容：
    
	1、自动评估获取学分，选课听课评估一条龙    
	2、修改了一些逻辑和bug
	
    ps:因逻辑不完善，如果评估课程失败，建议删除‘课程中心’-‘我的课程’-‘进行中’下的全部课程

### v1.3

    更新内容：
    
    1、默认学习2小时，到期自动关闭
    2、增加自动关机按钮，停止学习后自动关机

### v1.3.1

    更新内容：
    
    1、程序启动后，自动最小化，增加隐蔽性
    2、网站协议由http换成https
    
    
    
### 已知bug：

	1、日志输出不能默认显示最新
	2、日志输出无法按顺序输出

###  2019.9.19：
	1、尝试过用python添加计划任务，但是会被360等判定为非法操作，所以自己添加计划任务吧，很容易的，记得操作栏里要添加参数和起始于，不然exe启动不了
	2、功能其实很不完善，只考虑了理想情况下的学习，异常情况没有处理机制，碰到不能走下去的情况，个人建议：有问题的话，浏览器登录，删除全部已选课程，然后再打开软件试一下。我就是这样操作之后，再加上使用了计划任务，这三个多月，每天12点准时启动，自动学习自动关闭，学分也能正常获取，再也没有手动操作过。
	3、关于更新的问题，因为工作比较忙，再加上最近几个月，我机器上的程序都在良好的学习，核心功能已经实现了，所以对产品的关注度直线下降，激情也消退了，本来就是现学的python，几个月不碰，忘得差不多了，所以下一次更新，可能遥遥无期了。
