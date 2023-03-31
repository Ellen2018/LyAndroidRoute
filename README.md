# Android知识体系总结(Update By 2023)
> &emsp;&emsp;本人的Android学习路线，希望对你有帮助请star一下，是我最最大动力，感谢支持.  
> &emsp;&emsp;请一定要看下面的脑图，笔者总结的非常详细，下面只是列举了一个大致的知识脉络.脑图还没有完善，大概5月底可以做完。   
> &emsp;&emsp; 详细脑图请跳转:[Android 2023知识体系大纲 Version 1.0.0](https://github.com/Ellen2018/LyAndroidRoute/blob/master/Android%E7%9F%A5%E8%AF%86%E4%BD%93%E7%B3%BB%E6%80%BB%E7%BB%93%E6%95%B4%E7%90%86/Android%202023%E7%9F%A5%E8%AF%86%E4%BD%93%E7%B3%BB%E5%A4%A7%E7%BA%B2%20Version%201.0.0.xmind)

# Java
## 初级
- JDK & JVM & JRE
- 基本数据类型与引用类型
- 流程控制
- 运算符
- 面向过程 & 面向对象
- 内部类
- 数组
- 字符串
- 字符串模板
- 正则表达式
- IO流
- 异常体系
- 集合
- 多线程
- 网络编程
- 基础设计模式
## 中级
- 集合的使用与部分原理透析
- IO进阶：AIO/BIO/NIO
- 并发编程与底层原理
- 泛型
- 反射
- 注解
- JVM初级
- 动态代理
- 其它设计模式
## 高级
- 集合使用与原理
- 并发编程
- APT
- AOP
- 字节码插桩技术
- JVM
- JMM


## Kotlin
### 初级
- 基本数据类型
- 变量的声明与自动类型推断
- 流程控制 & 具有返回值
- 字符串模板
- 运算符
- 数组
- 集合
- IO编程
- 异常
- 函数式编程
- lambda表达式
- 面向对象
- 空类型安全
- 协程
- Flow
- Java与Kotlin互调
### 中级
- 高阶函数
- 泛型
- 反射
- 并发编程
### 高级
- Kotlin的编译器与语法糖
- 协程的原理

## 数据结构与算法
### 数据结构
- 数组
- 链表
- 队列
- 栈
- 散列表
- 树
- 堆
### 算法
- 时间复杂度 & 空间复杂度
- 排序算法
- 查找算法
- 加密算法
- 其它算法

## 计算机网络
- 计算机网络5层
- 什么是Http
- Http版本
- Http三次握手与四次挥手
- Http请求头与响应体
- Https是什么
- Https握手过程
- Socket与WebSocket
- Http缓存
- DNS
- 浏览器访问一个url的过程
- Cookie和Session & Token

## Android
### App开发方向
#### App开发方向初级
- 四大组件之Activity
- 控件的使用
- 四大组件之BroadcastReceiver
- 四大组件之ContentProvider
- 四大组件之Service
- Fragment
- 组件间通信问题
- Handelr
- Context
- Application
- 数据本地持久化
- Toast
- 对话框
- 通知:Notification
- Android权限编程
- 常用的轮子
- H5交互
- Jetpack
- 原生解决方案音视频开发
- 蓝牙开发
- 网络编程
- 图片编程
- Drawable
- 其它知识点
#### App开发方向中级
- 自定义View
- 架构:MVX系列(MVC,MVP,MVVM,MVI) & 组件化
- 原理透析之原生：Handler,广播,Jetpack等
- 原理透析之轮子：Glide,ARouter,OkHttp,LeakCanary等
- 进程间通信
- App优化:内存优化&UI适配&卡顿优化等
#### App开发方向高级
- 架构：MVX系列(MVC,MVP,MVVM,MVI) & 组件化 & 混合开发
- 原理透析:原生和第三方轮子很多都十分懂
- JNI
- gradle
- App优化:具有非常丰富的优化经验
- 热修复 & 插件化 & 增量更新
- Framework层原理

## SDK开发方向
- 具备App开发知识
- 类&方法&属性 访问权限
- 设计模式
- 系统兼容
- API与文档

## 系统应用开发方向：车载 & 电视TV等
- 具备App开发知识
- 进程间通信
- 常用的adb命令

### Android Automotive OS【谷歌官方车载系统】

- 什么是Android Automotive OS
- CarService:汽车服务
- CarPropertyService:车辆属性服务
- CarAudioService:汽车音频服务++                                                                                                                                                                      
- UX Restrictions:汽车用户体验限制
- 电源管理
- 输入事件管理
- 多屏幕支持
- 多用户支持
- 车外影像系统
- 车载系统应用：语音助手 & 导航应用 & 媒体应用 & 其它应用等

> 无论电视TV也好，还是车载或者其他的，你是从事系统应用开发，还是从事Framework层开发，我们都需要熟悉Android系统的Framework的一些机制，
> 这更加有利于你有更强的平台技术能力，从而达到我们心中想要的就是高薪。


## 跨平台开发
### Flutter
#### Dart
#### Flutter
### Compose

&emsp;&emsp;Compose的编程语言是Kotlin，也是Android现在开发的官方语言，因此Kotlin必须学的十分好才行。

## 计算机功底积累
- 数学
- 计算机组成原理
- 编译原理
- 算法与数据结构
- 数据库
- 操作系统
- 必须掌握的编程语言
- ......（学的越多越好）