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

### 即将到来：

	1、日志保存到本地，方便检查
	2、工作日中午和下午，下班后自动启动，模拟人工听课

