## main文件
停留点提取运行主程序，顺序：
区域筛选——>漂移现象——>停留点提取
## main_OD 
D提取流程的运行主程序，用于生成OD流，在提取出停留点后执行，顺序：
格网映射——>OD提取——>OD流聚合 
## SpatialFiltering 
用于筛选研究范围内的数据
## Draft 
用于处理漂移现象
## StayPoint
用于提取停留点
## OD模块
- fishnet 用于将停留点经纬度映射为格网编码    
- OD 文件用于提取用户OD    
- ODFlow文件用于生成OD流    