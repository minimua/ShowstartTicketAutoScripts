# ShowstartTicketAutoScripts

## 秀动抢票

### 1.安装对应版本的chromedriver
修改`driver.py`中的`executable_path`值为chromedriver的位置

### 2.引入需要的包
```
pip install selenium
pip install flask
```

### 3.获取需要抢的票的event和ticketId
打开F12
获取event：
![image](https://user-images.githubusercontent.com/61929966/174842224-cad75c14-3f3a-439e-bb76-bb0436dd53b4.png)

获取ticketId
点response
![image](https://user-images.githubusercontent.com/61929966/174842731-845f97a1-87ab-40b6-b1c8-0ab2a0c3a9a5.png)
搜索ticket
![image](https://user-images.githubusercontent.com/61929966/174845061-6210c838-a8e8-4375-a832-aacf3a8670ab.png)
可以复制出来，获取需要的票种的id
![image](https://user-images.githubusercontent.com/61929966/174843735-d091cc47-d3cb-4303-afce-87f85d461cad.png)

### 4.修改配置
修改`app.py`中的`event`和`ticketId`

### 5.启动
