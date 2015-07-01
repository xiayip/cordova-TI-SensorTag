##基于官方EvothingsWorkbench中的cc2650-demo
##点击upload上传sensortag的加速度计数据
##采用post方法，服务器端需要写一个php，接受数据

1. 优化：点击一次上传在服务器端创建一个文件
2. 美化：按钮样式css

v1.2


1. 优化：优化按钮disable，防止upload误操作
2. 优化：优化了sensor tag频率clock，发送时延等参数，现在50组数据都为有效数据
3. 增加：gyroscope、magnetometer参数
4. 增加：php数据表头
