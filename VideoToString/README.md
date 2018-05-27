作用：将视频在cmd下用字符显示出来 <br>
思想：利用cv2（处理视频）、PIL（处理图片）、threading（多线程）、pygame（播放音乐）等这些库的部分内容， <br>
      从视频中取出一帧图片，进行转换显示在cmd下，再取下一帧，如此循环，即可实现视频在cmd上显示。 <br>
环境：本人的测试环境为windows8.1专业版，python3.6.3
运行：运行test.py，即可运行
备注：VideoToString是将视频在cmd上播放的类，ImageToString是将指定图片在cmd上显示的类，video文件夹存放着测试用的mp4，music文件夹存放的是测试用的mp3

