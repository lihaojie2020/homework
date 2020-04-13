# 网络攻防

用法：IP地址输入格式：点分十进制（如192.168.1.1）

端口输入格式：端口号以逗号分隔，支持输入端口范围（如1,2,30-80），建议端口范围不要太大。

#### 实验结果：

```python
=======
Input IP :58.250.137.36
Input PORT:80-85
[+] 80 is open
[+] 81 is closed
[+] 82 is closed
[+] 84 is closed
[+] 83 is closed
[*] The scan is complete!
[*] A total of 1 open port 

=======
Input IP :39.156.69.79
Input PORT:80-85
[+] 80 is open
[+] 83 is closed
[+] 81 is closed
[+] 84 is closed
[+] 82 is closed
[*] The scan is complete!
[*] A total of 1 open port 
```

#### 总结：

本实验对qq_IP和百度IP进行了端口80-85的扫描，从此实验结果来看，可以看到成功建立连接的端口和未建立连接的端口，并对成功建立连接的端口进行了计数统计。通过此实验，更加了解了connect()的使用。

