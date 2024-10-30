# xxl-job-FLM
xxl-job调度器内存马【此内存马需要执行器与调度器在同一个环境中】

测试通过：`2.1.0~2.1.4`

## 功能：

1、不出网无回显打入内存马

2、不需要完整的jdk环境也可以打入内存马

3、自动判断系统版本打入对应的内存马


```
URL:http://192.168.65.137:8080/xxl-job-admin/toLogin
password:Gsehcvfao
User-Agent: Mozilla/5.0 (Yckq; Macintosh; magic Mac OS X 10.15; rv:121.0) Gecko/20100101 Firefox/121.0
```

![image](https://github.com/user-attachments/assets/93ac75d2-4156-4a12-a4ce-1d41dbded1ed)
![image](https://github.com/user-attachments/assets/22767cce-d475-4bd7-b030-8424934a107b)
找到对应的EXP，并修改代码，点击保存
![image](https://github.com/user-attachments/assets/b56f5dc8-7012-411c-aac2-7863da2cf871)
点击执行
![image](https://github.com/user-attachments/assets/8d42d814-8bf6-4615-9959-8b90359d1d76)
查看执行日志
![image](https://github.com/user-attachments/assets/3c4f4224-648b-4c3e-b997-56317dd1f5a6)
执行成功之后会显示JAR保存位置，注入的PID，其中【com.xxl.job.admin.XxlJobAdminApplication】为调度器的类名
![image](https://github.com/user-attachments/assets/c7b3d55b-f2f1-4210-adf6-8e49480719f0)
填入信息
![image](https://github.com/user-attachments/assets/aa594706-35f7-4bce-8a90-4d4b50955c2e)
第一次访问会显示【页面存在，但是无法获取密钥!】关闭对话框，在访问一次即可，第一次访问是激活内存马。
![image](https://github.com/user-attachments/assets/a79728ba-5e56-4052-839d-8d51e6e6545d)
![image](https://github.com/user-attachments/assets/76482632-02eb-4a7a-acda-0454e3b05cb8)

## TODO
哥斯拉内存马
suo5内存加载
