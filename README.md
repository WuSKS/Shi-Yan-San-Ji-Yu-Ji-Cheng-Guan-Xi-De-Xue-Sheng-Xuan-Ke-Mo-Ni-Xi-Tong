# 实验三    基于继承关系改进学生选课模拟系统
## 实验目的
掌握权限访问控制修饰符的使用；
<br>掌握继承的使用。
## 业务要求
1.保持实验二的代码和readme版本不变；
<br>2.新建代码仓库，在实验二代码的基础上完成本次实验；
<br>3.业务过程同实验二，但在类的设计上，采用父类-子类的继承关系定义，探讨该系统中哪些类具有共性，作为父类，定义子类；
<br>4.父类定义构造方法，子类定义构造方法，掌握super()用法；
<br>5.基础对象类和测试类分别存放于不同的package中，验证权限访问控制、继承后属性及方法的可见性。
## 实验要求
提交源程序到本人代码托管系统，代码仓库命名为“实验三基于继承关系的学生选课模拟系统”。
<br>写实验报告文件（readme.md），体现本次实验在实验二基础上的改进。
## 具体改进
1.Teachers类继承了Students类中的
<br>num属性：表示教师的编号。
<br>name属性：表示教师的姓名。
<br>gender属性：表示教师的性别。
<br>getName()方法：返回教师的姓名。
<br>getGender()方法：返回教师的性别。
<br>getNum()方法：返回教师的编号。
<br>这些属性和方法是从Students类继承而来的，可以在Teachers类中直接使用
<br>2.修改了原本功能实现中，输出课表里信息重复的问题（不同方法返回值重复），这样的改进使得输出的课表信息
<br>更加规范和易读。
## 结构图
<img width="117" alt="image" src="https://github.com/WuSKS/Shi-Yan-San-Ji-Yu-Ji-Cheng-Guan-Xi-De-Xue-Sheng-Xuan-Ke-Mo-Ni-Xi-Tong/assets/145275222/5c72be53-d9d1-43ba-bdb3-545ca4550f1e">

## 系统运行截图
<img width="1280" alt="image" src="https://github.com/WuSKS/Shi-Yan-San-Ji-Yu-Ji-Cheng-Guan-Xi-De-Xue-Sheng-Xuan-Ke-Mo-Ni-Xi-Tong/assets/145275222/d1d1fe90-1883-4cca-858a-5ec6464dd37b">

## 感想与体会
熟悉了访问权限控制和如何运用继承，避免了重复编写相同的代码，提高了代码的灵活性和可扩展性，收获颇多，感谢老师

  



