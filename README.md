# ffmpeg视频切割机

参数说明
~~~
  -f 源文件
  -h 保存目录
  -d 指定分割段数   （与-s不能同时执行）
  -s 指定时间割段数（秒） （与-d不能同时执行）
~~~

~~~
例子1（将一个视频分割为10段）
  php ./cutting.php -f ./IMG_5272.MOV -h ./ -d 10
~~~

~~~
例子2（将一个视频每段以120秒进行分割）
  php ./cutting.php -f ./IMG_5272.MOV -h ./ -s 120
~~~