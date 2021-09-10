### 更新Raspberry Pi的自带python

1.安装python3

```
sudo apt install python3
```

2.删掉原来的python链接(这一步之前可以考虑卸载旧python)

```
sudo rm /usr/bin/python
```

3.创建新链接指向安装的python3.7

```
sudo ln -s /usr/bin/python3.7 /usr/bin/python
```

![update](https://github.com/Gotttit/Raspberry-Pi-AI/blob/main/python_update/pics/python_update.png)

<center>图示为python链接删除和python3添加</center>

