**[点我获取源码](https://x-x.fun/e/ZSbbd63c2cHey)💕🤞**

**[点我获取源码+论文参考示例](https://x-x.fun/e/TS5cc5a4773oB)💕🤞**

**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

#### 1.项目介绍

技术栈+工具： SpringBoot + Vue + redis + rabbitMQ + MySQL5.7及以上 + Maven + IDEA2022

系统角色： 管理员、HR、员工等，可自行根据需求定义

系统功能：管理员：公共模块（登录、在线聊天）、员工管理、员工发展（调动、考勤、培训、奖惩）、薪资管理、人事统计、系统管理等；HR：人事管理、在线聊天、考勤、薪资管理；员工：登录、在线聊天、考勤等

#### 2.系统部署

##### 2.1 后端部署

- 创建数据库，导入sql文件

- 打开idea，导入项目hr-admin

- 根据本地数据库环境，修改数据库连接 src/main/resources/application.yml  6-9行

- 安装redis，启动redis服务，根据本地环境修改配置文件src/main/resources/application.yml  22-26行

- 安装rabbitMQ， 启动rabbitMQ服务，根据本地环境修改配置文件src/main/resources/application.yml  30-34

- 启动后端服务

##### 2.2 管理web

- 打开idea（需要安装Vue插件）或者其他前端IDE，导入项目hr-web

- 测试的node版本V12，进入项目所在目录，执行：npm install

- 执行 npm run serve

- 启动成功后打开链接，管理员账号/密码： admin/123  HR账号/密码：xuanyuanqingfeng/123   员工账号/密码：张三丰/123

- 在线聊天， 请打开两个浏览器。登录两个账号进行测试