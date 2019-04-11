SBIndexApplicationTests01
	
	直接运行main方法或使用maven命令: spring-boot:run
	
	测试:
		http://localhost:8080/index
	
	参数-中文:
		http://localhost:8080/index/get?name=柯金
	
	url:
		http://localhost:8080/index/get/1/kngines
	
SBIndexApplicationTests02
	
	Application属性文件，按优先级排序，位置高的将覆盖位置低的
		1. 当前目录下的一个/config子目录
		2. 当前目录
		3. 一个classpath下的/config包
		4. classpath根路径（root）

	properties url:	
		http://localhost:8080/index/getprop?name=%E6%9F%AF%E9%87%91
