# java SE复习笔记-01

#### Java 基础语法：
- **大小写敏感**：Java是大小写敏感的
- **类名**：对所有的类来说，类名的首字母应该大写。如果类名由若干个单词组成，那么每个单词应该首字母大写。
- **方法名**：所有方法名都应该以小写字母开头。如果方法名有若干个单词，则后面每个单词的首字母大写。
- **原文件名**：源文件名相同。
- **主方法入口**：所有的Java程序由public static void main(String[] args)方法开始执行的。
#### Java 标识符
**Java所有的组成部分都需要名字。类名、变量名以及方法名都可以被称为标识符。**
- 所有的标识符都应该以字母(A~Z或a~z)、美元符($)、下划线(_)开始
- 首字母之后可以是字母(A~Z或a~z)、美元符($)、下划线(_)或数字的任意组合
- 关键词不能作为标识符
- 标识符是大小写敏感的

#### Java 修饰符
**Java可以使用修饰符来修饰类中的方法和属性**
- **访问控制修饰符**：default、public、protected、private
- **非访问控制修饰符**：final、abstract、static、synchronized

#### Java 变量

- **局部变量**
- **类变量(静态变量)**
- **成员变量(非静态变量)**

#### Java 注释

- `//单行注释`
- `/*多行注释*/`

#### Java 关键字

类别|关键字|说明
---|---|---|
访问控制|private |私有的
 - |protected |受保护的
 - |public |公共的
 - |default |默认
类、方法和变量修饰符|abstract |声明抽象
- | class | 类
- | extends |扩充、继承
- | final | 最终值，不可改变的
- | implements | 实现(接口)
- | interface | 接口
- | native | 本地，原生方法
- | new | 新创建
- | static | 静态
- | strictfp | 严格、精准
- | synchronized | 线程、同步
- | volatile | 易失
程序控制语句 | break | 跳出循环
- | case | 定义一个值以供switch选择
- | continue | 继续
- | default | 默认
- | do | 运行
- | else | 否则
- | for | 循环
- | if | 如果
- | instanceof | 实例
- | return | 返回
- | switch | 根据值进行选择
- | while | 循环
错误处理 | assert | 断言表达式是否为真
- | catch | 捕捉异常
- | finally | 有没有异常都执行
- | throw | 抛出一个异常对象
- | throws | 声明一个异常可以被抛出
- | try | 捕获异常
包相关 | import | 引入
- | package | 包
基本类型 | boolean | 布尔型
- | byte | 字节型
- | char | 字符型
- | double | 双精度浮点
- | float | 单精度浮点
- | int | 整型
- | long | 长整型
- | short | 短整型
变量引用 | super | 父类、超类 
- | this | 本类
- | void | 无返回值
保留关键字 | goto | 是关键字、但不能使用
- | const | 是关键字、但不能使用
- | null | 空



