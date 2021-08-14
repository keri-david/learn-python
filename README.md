<!-- TOC -->

- [Python环境的搭建](#python%E7%8E%AF%E5%A2%83%E7%9A%84%E6%90%AD%E5%BB%BA)
    - [python安装](#python%E5%AE%89%E8%A3%85)
    - [IDE安装](#ide%E5%AE%89%E8%A3%85)
- [变量和字符串](#%E5%8F%98%E9%87%8F%E5%92%8C%E5%AD%97%E7%AC%A6%E4%B8%B2)
    - [基本概念](#%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5)
    - [字符串的分片与索引](#%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E5%88%86%E7%89%87%E4%B8%8E%E7%B4%A2%E5%BC%95)
    - [字符串格式化输入](#%E5%AD%97%E7%AC%A6%E4%B8%B2%E6%A0%BC%E5%BC%8F%E5%8C%96%E8%BE%93%E5%85%A5)
- [函数](#%E5%87%BD%E6%95%B0)
    - [内置函数](#%E5%86%85%E7%BD%AE%E5%87%BD%E6%95%B0)
    - [自建函数](#%E8%87%AA%E5%BB%BA%E5%87%BD%E6%95%B0)
    - [函数习题](#%E5%87%BD%E6%95%B0%E4%B9%A0%E9%A2%98)
    - [传递参数和参数类型](#%E4%BC%A0%E9%80%92%E5%8F%82%E6%95%B0%E5%92%8C%E5%8F%82%E6%95%B0%E7%B1%BB%E5%9E%8B)
        - [分类](#%E5%88%86%E7%B1%BB)
        - [习题](#%E4%B9%A0%E9%A2%98)
    - [需要知道的运算符](#%E9%9C%80%E8%A6%81%E7%9F%A5%E9%81%93%E7%9A%84%E8%BF%90%E7%AE%97%E7%AC%A6)
- [逻辑控制与循环](#%E9%80%BB%E8%BE%91%E6%8E%A7%E5%88%B6%E4%B8%8E%E5%BE%AA%E7%8E%AF)
    - [布尔类型](#%E5%B8%83%E5%B0%94%E7%B1%BB%E5%9E%8B)
    - [逻辑运算符](#%E9%80%BB%E8%BE%91%E8%BF%90%E7%AE%97%E7%AC%A6)
        - [常见的相同比较类型](#%E5%B8%B8%E8%A7%81%E7%9A%84%E7%9B%B8%E5%90%8C%E6%AF%94%E8%BE%83%E7%B1%BB%E5%9E%8B)
        - [不同类型的比较](#%E4%B8%8D%E5%90%8C%E7%B1%BB%E5%9E%8B%E7%9A%84%E6%AF%94%E8%BE%83)
        - [布尔类型的比较](#%E5%B8%83%E5%B0%94%E7%B1%BB%E5%9E%8B%E7%9A%84%E6%AF%94%E8%BE%83)
    - [成员运算符和身份运算符](#%E6%88%90%E5%91%98%E8%BF%90%E7%AE%97%E7%AC%A6%E5%92%8C%E8%BA%AB%E4%BB%BD%E8%BF%90%E7%AE%97%E7%AC%A6)
        - [列表](#%E5%88%97%E8%A1%A8)
            - [创建列表](#%E5%88%9B%E5%BB%BA%E5%88%97%E8%A1%A8)
            - [添加元素](#%E6%B7%BB%E5%8A%A0%E5%85%83%E7%B4%A0)
            - [访问元素](#%E8%AE%BF%E9%97%AE%E5%85%83%E7%B4%A0)
    - [布尔运算](#%E5%B8%83%E5%B0%94%E8%BF%90%E7%AE%97)
        - [bool（）](#bool)
        - [None](#none)
        - [运算符](#%E8%BF%90%E7%AE%97%E7%AC%A6)
    - [条件控制if---else](#%E6%9D%A1%E4%BB%B6%E6%8E%A7%E5%88%B6if---else)
    - [循环](#%E5%BE%AA%E7%8E%AF)
        - [for循环基本格式](#for%E5%BE%AA%E7%8E%AF%E5%9F%BA%E6%9C%AC%E6%A0%BC%E5%BC%8F)
        - [嵌套循环](#%E5%B5%8C%E5%A5%97%E5%BE%AA%E7%8E%AF)
        - [while循环](#while%E5%BE%AA%E7%8E%AF)
        - [练习](#%E7%BB%83%E4%B9%A0)
    - [综合练习](#%E7%BB%BC%E5%90%88%E7%BB%83%E4%B9%A0)
- [数据结构](#%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84)

<!-- /TOC -->

# Python环境的搭建

## python安装
- Windows平台
1. 官网下载安装包
2. 点击安装时，注意勾选将python添加到环境变量
- Mac平台
1. 官网下载安装包
2. 点击安装
---
1. 提前安装好homebrew
2. 输入命令`brew install python3`
- Linux平台
1. Debian系列
> apt-get install python3
2. RedHat系列
> yum install python3

## IDE安装
> - 官网下载pycharm社区版,免费使用

# 变量和字符串

## 基本概念
- 变量要赋值使用，大小写敏感
- 用print(a)可以打印出变量内容
- 字符串：用单（双）引号括起来的内容
- 可以适用连接符`+`，来链接字符串内容，形成新的字符串
- 连接符左右两个单元，必须是字符串或字符，类型要一致
- 如果想要知道变量是啥类型，可以用print(type(a)),打印出来
- 为了防止，中文注释出现乱码，可以开头声明`#coding:utf-8`，或者编辑器设置编码。
- 如果想要类型一致，可以用强制类型转换，如int（a）就是把a变量变成整型
- 字符串还可以乘上数字，就变成了好几个内容
```python
words='words'*3
print(words)*3
wordswordswords
```
- 可以适用len（a）来测量出a字符串的长度，是整型
![len测量长度](pictures/len.png)

## 字符串的分片与索引
![索引](pictures/索引.png)
![索引2](pictures/索引2.png)
- 类似于数组的索引
- `name[11,14]`的意思是从11个开始，不包含14的切片
- `name[5:]`代表从5到结尾
- `name[:5]`代表从开头到5,不包含5
![切片](pictures/切片.png)
- 输出的结果是`fiend`
![切片2](pictures/切片2.png)
- 输出结果为`*********0006`
- replace是替换的一个字符串方法
![切片3](pictures/切片3.png)
- find是字符串的搜索方法，返回初始位置

## 字符串格式化输入
- 下面三个方法都用format方法来格式化输入
![](pictures/format.png)
- 下面是用百度天气的api开发片段
![](pictures/format2.png)

# 函数

## 内置函数
![](pictures/函数.png)
- python3.5 内置了上面的这些函数

## 自建函数
```python
def fuction(arg1,arg2):
    ...
    ...
    return result
```
- 下面是摄氏度转华氏度的函数自定义
![](pictures/摄氏度转华氏度.png)
- 如果我们要调用上面的函数
![](pictures/摄氏度转华氏度2.png)
运行完，就会得到想要的结果

## 函数习题
![](pictures/函数习题.png)
- 第一题答案
```python
def fuction(weight):
    result=weight/1000
    return result
print(fuction(56))
```
- 第二题答案
```python
def fuction(a,b):
    result=pow(pow(a,2)+pow(b,2),.5)
    return result
print('The Right triangle thrid side \' length is '+str(fuction(3,4)))
```

## 传递参数和参数类型

### 分类
1. 位置参数
- area(1,2,3)
2. 关键字参数
- area(base_up=1,base_down=2,height=3)
![](pictures/函数参数传递.png)
1. 完全是关键字参数，无关排序
2. 当到3的时候，变成位置参数，对应height，但是height在之前已经输入过了
3. 参考第二条语句，参数都正确的输入了
4. 当到3的时候，变成关键字参数，输入无误
- **无论什么参数，只要函数定义了，输入时就缺一不可**
- **除非我们在定义函数的时候，定义了默认值**
- **即使设置了默认值，调用时任然可以自己更改**
```python
print('  *',' **','***',' | ')
print('  *',' **','***',' | ',sep='\n' )
```
- 默认逗号是空格间隔，但是如果改成换行，就会变成一棵树

### 习题
- 打开桌面上的文件，同时写入内容，输入：1.文件名2.写入内容，输出提示完成
![](pictures/打开桌面文件写入内容.png)
- `'w'`代表写入模式，如果该位置有文件就覆盖，没有就创建
- 打开文件，使用完就要关闭文件

## 需要知道的运算符

|符号|描述|
|---|---|
|%|返回余数|
|**|次方运算符|
|//|返回商的整数部分|

# 逻辑控制与循环
## 布尔类型
![](pictures/布尔类型.png)
- 只有0和1两个值，也就是false和true
## 逻辑运算符

|符号|描述|
|---|---|
|==|判等|
|!=|不等于|
|>|大于|
|<|小于|
|>=|大于等于|
|<=|小于等于|
### 常见的相同比较类型
1. 常量的比较
2. 变量的比较
3. 字符串的比较，区分大小写
4. 函数的结果比较
### 不同类型的比较
- 不能用>,<,>=,<=进行比较，可以用==，!=进行比较
- 浮点类型和整型可以进行比较
### 布尔类型的比较
- 把false当成0,true当成1,运算完就可以进行比较
## 成员运算符和身份运算符
### 列表
#### 创建列表
1. 空列表`album=[]`
2. 非空列表`album=['Black','david',25,false]`
#### 添加元素
> album.append('new str')
#### 访问元素
- album[0],album[-1]代表第一个和最后一个元素
***
- 所以in可以这样用
> 'Black' in album
- is可以这样用
> album[1] is album[-4]
- is和in可以加上not来否定
## 布尔运算
### bool（）
- 除了0,None和所有空的序列和集合（列表、字典、集合）的布尔值为空，其他都是true.可以用bool（）来判断。
### None
- 如果一个函数没有返回值，却赋值给了一个变量，那么这个变量就是None
- 在定义一个变量的时候，没想好赋值，那么可以赋值为None
### 运算符
- 有一下几个

|符号|描述|
|---|---|
|not|否定|
|and|并且的意思|
|or|或者的意思|
- or 有真则真，and有假则假
## 条件控制if---else
- 一个模拟密码登陆系统
1. 普通思路
![](pictures/ifelse1.png)
2. 布尔值传入判断
![](pictures/ifelse2.png)
- 用elif来模拟密码重置
![](pictures/elif.png)
## 循环
### for循环基本格式
![](pictures/for循环.png)
- 一般用法
```python
for num in rang(1,11):
    print(str(num)+'+1=',sum+1)
```
- rang,不包含11,所以是1-10的整数
```python
songslists=['holy','tharuk','rebel]
for song in songslists:
    if song=='holy:
        print(song,'-Dio')
    elif song=='tharuk':
        print(song,'-AC/DC')
    elif song=='rebel':
        print(song,'-david')
```
### 嵌套循环
- 打印乘法口诀表
```python
def fuction():
    tmp=0
    for i in range(1,10):
        for j in range(1,i+1):
            print('{}X{}={}\t'.format(j,i,i*j),end=' ')
        print()
fuction();
```
### while循环
- 基本语法
![](pictures/while.png)
- while循环要注意，不能死循环
- 可以构成while-else循环结构
```python
tries=3
while tries>0:
    ***
else:
    ***
```
### 练习
1. 设计函数，在桌面上创建10个文本，分别是数字1-10.txt
```python
def fuction():
    for num in range(1,11):
        file=open('/home/keri/Desktop/'+str(num)+'.txt','w')
fuction();
```
2. 编写一个函数，参数包含资金、利率、投资时间，返回投资时间内的每年的金额
```python
def fuction(amount,rate,time):
    for num in range(1,int(time)+1):
        amount = amount * (1+rate/100)
        print("Year{}:${}".format(num,amount))
fuction(100,5,8)
```
3. 打印1-100之内的偶数
```python
def fuction():
    for num in range(1,101):
        if num%2==0:
            print(num,end="\t")
fuction()
```
## 综合练习
1. 随机生成三个数字，让用户去猜大小，大应在11-18之间，小应该在3-10之间
```python
import random
def fuction(str):
    list=[0,0,0]
    list[0] = random.randrange(1,7)
    list[1] = random.randrange(1,7)
    list[2] = random.randrange(1,7)
    if(sum(list)>10):
        result='big'
    else:
        result='small'
    print("the list are [{},{},{}]".format(list[0], list[1], list[2]))
    if(result==str):
        print('you are win')
    else:
        print('you are lose')

str=input('输入：\n')
fuction(str)
```
2. 基于前一个练习，编写一个投注游戏，初始金额1000,赔率默认1,输光为止
```python
import random
def fuction():
    list = [0, 0, 0]
    money=1000
    while money>0:
        print('-----   STSRT   -----')
        str=input('big or small?')
        duzhu=input('how mush you wanna bet?')
        if (0<int(duzhu)<=money):
            list[0] = random.randrange(1, 7)
            list[1] = random.randrange(1, 7)
            list[2] = random.randrange(1, 7)
            if (sum(list) > 10):
                result = 'big'
            else:
                result = 'small'
            print('-----ROLL THE DICE!-----')
            print("the list are [{},{},{}]".format(list[0], list[1], list[2]))
            if (result == str):
                money = money + int(duzhu)
                print('you are win,you gained {}'.format(duzhu))
            else:
                money=money-int(duzhu)
                print('you are lose,you lost {}'.format(duzhu))
            print('you have {} now'.format(money))
        else:
            print('invaild input!')
    else:
        print('-----   OVER    -----')

fuction()
```
3. 检测一个号码是否合法
```python
import random
def fuction(str):
    oper=None
    CN_mobile=[134,135,136,137,138,139,150,151,152,157,158,159,182,183,184,187,188,147,178,1705]
    CN_union=[130,131,132,155,156,185,186,145,176,1709]
    CN_telecom=[133,153,180,181,189,177,1700]
    if len(str)==11:
        if str[:3]=='170':
            if str[3]=='5':
                oper='CN_mobile'
            elif str[3]=='9':
                oper='CN_union'
            elif str[3]=='0':
                oper='CN)_telecom'
        else:
            if int(str[0:3]) in CN_mobile:
                oper = 'CN_mobile'
            elif int(str[0:3]) in CN_union:
                oper = 'CN_union'
            elif int(str[0:3]) in CN_telecom:
                oper = 'CN)_telecom'
        if oper:
            print("Operator:{}".format(oper))
            print('我们将发送验证码到号码：{}'.format(str))
        else:
            print('不是合法的号码')
    else:
        print('不是11位号码，重新输入')
str=input('输入号码：\n')
fuction(str)
```
# 数据结构
