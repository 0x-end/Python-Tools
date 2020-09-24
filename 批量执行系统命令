#!/usr/bin/python3
import os
f = open('1.txt',mode = 'r+',encoding='cp936')  #打开文件
for line in f.readlines():                      #循环读取文件内容
    line = line.strip()                         #去掉每行头尾空白
    A = open('2.txt',mode='a+',encoding='unicode_escape')
    A.write(str(os.popen("ping"+"\t"+line).read())) #将os.popen("ping"+"\t"+line).read()写入文件
A.close()
f.close()   #关闭文件
