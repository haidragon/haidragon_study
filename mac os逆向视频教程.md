# mac os安全视频教程
# 以下不代表全部，视频一直在更新，可以加vx2207344074了解详情！！！ 
## mac os (10.15.3)
# macOS 渗透视频教程

## 基础

* 1.课程介绍
* 2.认识macOS操作系统
* 3.常用工具安装

## 操作系统架构

* macOS版本发展
* macOS系统架构
* NEXT与Darwin
* Mach原语
* 系统调用
* 安全机制介绍
* macOS生态

## 文件系统

* Apple专有文件系统
* 系统卷保护
* POSIX目录
* LaunchDaemons和LaunchAgents
* Applications
* Frameworks
* Extensions
* 文件属性
* Bundles
* 日志系统

## Objective-C/C++

* c语言基础
* c++引用
* c++类
* c++继承
* c++重载
* OC语言基础
* Swift语言基础

## cocoa

* macOS图形库
* 窗口对象
* 视图
* 基本控件
* 布局
* 控制器
* 事件
* 文件与拖放
* 系统服务
* 消息推送
* 多文档应用

## D语言(Dtrace)

* Dtrace介绍
* Dtrace入门
* D程序结构
* 对比c语言
* Dtrace子程序
* 推理追踪
* 脚本
* 提供器介绍
* syscall提供器

## macho文件格式

* 通用二进制文件格式
* macho文件简介
* macho头部
* 加载命令
* macho数据

## 底层原理(runtime)

* Runtime源码编译
* OC对象本质
* class-dump
* NSObject的内存本质
* OC复杂的继承结构
* 属性与方法
* glibc与libmalloc
* OC对象的分类
* isa和superclass
* KVO
* KVC
* Category
* 关联对象
* block
* Runtime-isa
* Runtime-class
* objc_msgSend
* Runtime-super
* Runtime其它api
* dyld介绍
* dyld源码阅读
* dyld共享缓存

## lldb

* lldb介绍与附加
* lldb有无符号断点操
* 线程与栈
* lldb寄存器与打印操
* 模块(镜像)操作
* objc_msgSend参数打
* lldb内存操作与反汇
* 编写第一个lldb脚本
* 利用lldb脚本打印堆栈详细信
* lldb脚本实现trace
* lldb脚本实现UI_inspector

## shellcode与汇编

* 操作系统构架
* 汇编语言介绍
* 寄存器
* 函数
* 函数调用约定(函数传参)
* shellcode编写与提取
* shellcode调试
* asm编写shellcode
* 反向shell编写
* 用c编写shellcode

## hook与注入

* 注入介绍
* 注入分类
* macho注入dylib
* macho添加节
* macho注入shellcode
* DYLD_INSERT_LIBRARIES介绍
* DYLD_INSERT_LIBRARIES限制dyld源码分析
* Dylib劫持介绍
* Dylib劫持dyld源码分析
* 劫持Dlopen
* 远程线程注入
* hook介绍
* 函数回调
* OC函数替换
* inline hook原理

## hook框架

* tweak命令环境搭建
* xcode集成环境搭建
* 通过tweak复习oc反射
* tweak hook oc普通函数
* tweak hook oc构造函数
* tweak oc类添加函数同时调用
* tweak oc修改参数
* tweak 遍历所有动态库与框架
* tweak hook动态库导入导出函数
* tweak hook framework
* tweak hook未导出的函数
* tweak hook无符号函数
* tweak hook c++函数
* tweak hook block
* swift反射与函数名粉碎
* tweak hook swift普通方法
* tweak hook swift构造函数
* CaptainHook使用
* tweak添加其它dylib库
* hook 指令介绍
* hook syscall介绍
* tweak命令工具
* 函数追踪方式1
* 函数追踪方式2
* 函数追踪方式3
* 函数追踪方式4
* frida 环境搭建
* frida 常用命令使用介绍
* frida hook Objc常用方法
* frida hook Objc中常用容器类
* frida hook native层
* frida hook 其它情况
* frida 主动调用
* frida hook Swift

## 签名

* 签名与密码简介
* 对称加密
* 非对称加密
* 证书
* macOS签名流程
* dyld签名审查源码分析
* 重签名与重打包介绍
* 重签名-GUI工具
* 重签名-tweak原理分析
* 重签名-动态库
* 第三方签名工具

## ollvm

* llvm介绍
* llvm项目编译与安装
* clang编译与调试(xcode)
* clang外部项目构建与安装(xcode)
* Compiler-RT介绍与使用
* libc++标准库介绍
* 使用llvm独立工具
* 编写第一个llvm项目
* clang插件编写
* clang前端-之实现一个自定义检查规范
* 编写第一个llvm pass(编译与调试)
* clang前端-之实现clang诊断
* clang前端-之理解词法分析与实现遍历
* 实现一个函数名称加密Pass
* ollvm介绍
* ollvm编译(macOS)
* ollvm集成xcode
* 使用ollvm注意事项
* ollvm老版本代码提取(移植)
* ollvm源码分析之sub(指令替换)
* ollvm源码分析之fla(控制流程平坦化)
* ollvm源码分析之bcf(虚假控制流程)
* ollvm源码分析之其它杂项
* 最后一个实战字符串加密Pass

## unicorn 

* unicorn介绍
* unicorn源码编译
* unicorn简单使用与调试
* unicorn 源码框架了解
* 实现一个最简单的my_qemu(kvm)
* shellcode 指令追踪使用
* shellcode 指令追踪源码分析
* 使用中断事件hook源码分析 (syscall)
* 使用中断事件hook源码分析(arm syscall)
* 内存操作事件hook(读写执行)
* 内存操作事件hook源码分析
* 异常事件使用与源码分析
* 再谈unicorn(框架定位与缺陷)
* 模拟单个参数函数与获取返回值(x86_64构架)
* 模拟多个参数函数(x86_64构架)
* 模拟获取全局变量函数(x86_64构架)
* 外部符合libc库函数调用模拟(x86_64构架)
* 模拟多个函数调用链(x86_64构架)
* 模拟base64编码(x86_64构架)
* aes算法模拟(x86_64构架)
* des算法模拟(x86_64构架)
* rc4算法模拟(x86_64构架)
* 其它算法模拟思路(x86_64构架)
* 模拟单个参数函数与获取返回值(arm64构架)
* 模拟多个参数函数(arm64构架)
* 模拟获取全局变量函数(arm64构架)
* arm构架中的算法模拟(arm64构架)
* unicorn macho文件模拟
* unicorn调试器介绍
* unicorn结合capstone使用
* 生成CFG(控制流程图)
* ollvm反混淆思路

## Daemon与XPC

* Daemon介绍
* Daemon管理
* 编写第一个Daemon
* Daemon分类
* Daemons
* User agents
* Privileged helpers
* Login items
* System extensions
* XPC service
* 再谈XPC
* XPC消息传递
* XPC安全

## 网络

* socket服务器客户端复习
* http_post提交简单实现
* openssl简单使用
* https实现请求百度
* https服务器客户端简单实现
* https服务器客户端实现添加CA验证
* https服务器客户端双向证书验证实现
* https解密思路
* http抓包原理及实现
* https抓包原理与实现
* https双向证书验证绕过原理
* 数据包中证书提取实现

## 漏洞利用基础

* 缓冲区溢出-栈溢出
* 缓冲区溢出-堆溢出
* pwntools使用
* 堆练习House of Force
* ROP链原理
* ret2text
* ret2shellcode
* ret2syscall
* ret2libc
* jmp rsp
* 其它常见二进制漏洞-整数溢出漏洞
* 其它常见二进制漏洞-格式化字符串漏洞
* 其它常见二进制漏洞-双重释放漏洞
* 其它常见二进制漏洞-数组越界访问漏洞

## macOS安全机制与绕过

* macOS Sandbox
* Sandbox Containers
* Sandbox debug
* Disable Sandbox
* Sandbox Profile文件(SBPL)
* 编写自己的Sandbox Profile
* 系统的Sandbox Profile
* Sandbox逃逸
* Sandbox逃逸-QuickLook
* Sandbox逃逸-Word
* macOS TCC
* TCC 内部结构
* TCC绕过
* CVE-2020-29621漏洞分析与利用
* CVE-2020-24259漏洞分析与利用
* 获得全盘访问权限
* 符号链接
* 文件系统权限模型
* 寻找错误的链接
* CVE-2020-3855漏洞分析与利用
* 驱动加载限制
* 驱动开发环境搭建
* 第一个驱动程序
* 驱动加载过程
* CVE-2020-9939

## libFuzzer

* libFuzzer介绍
* libFuzzer安装
* 第一个空libFuzzer测试程序
* 利用libFuzzer测试第一个程序
* LibFuzzer 语料库(corpus)
* fuzzing-任意数据输入
* fuzzing-以Null结尾的字符串输入
* fuzzing-基于文件的输入
* fuzzing-作为输入的CPP字符串
* fuzzing-非缓冲区数据
* Sanitizers 介绍
* 内存越界访问-ASan
* Double-free-ASan
* (带符号)整数溢出-UBSan
* 未初始化内存-MSan
* 内存泄漏-LSan
* 实例-CVE-2014-0160
* 实战-Libcaca-fuzzing(上)
* 实战-Libcaca-fuzzing(下)
* 高效fuzzing介绍
* Seed实例
* dictionaries实例
* coverage实例
* 结构感知模糊测试介绍
* 自定义LibFuzzer Data参数
* 程序状态 Fuzzing
* protobuf mutator
* 语法Fuzzing-protobuf
* 实战-Fluent Bit Fuzzing
* 实战-PHP Fuzzing
* 实战-Chromium fuzzing
* Python fuzzing

## C2&&frameworks

* payloads编码
* 加密payloads(异或)
* 加密payloads(AES)
* 加密payloads(RC4)
* 加密payloads(RSA)
* api简单混淆
* 字符串内存中动态加解密
* macho文件插入后门
* Metasploit Framework介绍
* Metasploit 源码架构
* ruby语法复习
* MSF源码调试环境搭建
* 调试分析渗透攻击模块(exploit)
* 调试分析攻击载荷模块(payload)
* 调试分析编码器模块(encodes)
* 调试分析后渗透攻击模块(post)
* 调试分析辅助模块(auxiliary)
* 反射式注入复习
* 反向shell原理与实现(c语言)
* 反向shell原理与实现(汇编)
* payload生成源码再次调试
* payload运行原理(sockedi调用约定上)
* sockedi调用约定(下)
* sockedi调用约定抓包分析
* sockedi调用约定调试分析(后门)
* 自己实现MSF loader(c语言)
* MSF stagers开发(go语言)
* reverse_http 原理与实现
* reverse_https 原理与实现
* CobaltStrike介绍与安装

# java基础
* ---1.第一个java程序
* ---2.制作最简单的jar包(上)
* ---3.制作最简单的jar包(下)
* ---4.含两个类的jar包
* ---5.有目录结构的jar包
* ---6.制作jar包含有jar包
* ---7.jar调用内部的jar包
* ---8.制作含有资源文件的jar包
* ---9.资源文件jar包外部调用
* ---10.native层动态库编写
* ---11.java调用native接口
* ---12.jar调用native接口
* ---13.java反射复习
* ---14.java代理原理(上)
* ---15.java代理原理(下)
* ---16.class文件格式
* ---17.遍历java函数 
* ---18.java-hook(一)
* ---19.java-hook(二)
* ---20.java-hook(三)
* ---21.jar调试
* ---22.第三方java app调试
* ---23.java-ui---窗口
* ---25.java-ui---窗口事件
* ---26.method-trace 
* ---27.java混淆
* ---28.dump method
* ---29.java2c原理
* ---30.实战第一个java程序破解



 
* 高级调试器对抗(以下只讲64位同时除了原理讲解其它全是用户层实现不涉及到内核)
* ---1.操作系统原理之中断.mp4
* ---2.操作系统原理之异常.mp4
* ---3.操作系统原理之syscall.mp4
* ---4.intel amd64构架syscall实现原理.mp4
* ---5.arm armv8构架syscall实现原理.mp4
* ---6.libc函数原理.mp4
* ---7.自己实现libc函数.mp4
* ---8.利用libc实现反调试.mp4
* ---9.自己实现libc反调试.mp4
* ---10.利用syscall反调试.mp4
* ---11.指令 hook介绍.mp4
* ---12.libc反反调试.mp4
* ---13.自己实现的libc反反调试.mp4
* ---14.syscall hook原理.mp4
* ---15.syscall反反调试.mp4

* XNU 源码
* --- XNU源码编译
* --- XNU源码修改
* --- XNU驱动编写
* --- ...
# [实战](https://github.com/haidragon/study_frida) 
