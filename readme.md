# 加速访问GitHub

👋你好，GitHub是全世界最大的开源代码托管平台，我们可以通过GitHub学习很多优秀的项目和代码，来提高我们的实力，或者是为开源世界做出自己的贡献，但是对于国内用户来说GitHub可能在访问上有点阻碍，如果你也是这样，那么你来对地方了，这个项目可以让你访问GitHub变得更加丝滑一点

## 注意
>1. 本项目只是修改本机的hosts文件，没有任何代理操作，也不会提供任何代理手段
>2. linux系统经过测试可以正常执行，手头上没有windows和mac的机子，暂时没有测试

## 支持环境
> windows_amd64
>
> linux_amd64
>
> darwin_linux
 
## 安装教程
> 直接源码安装，暂时没有releases

## 介绍
> rawHosts.txt文件是当前系统原始的hosts信息
> historyHosts.txt文件记录了当前系统hosts的所有变动
> urls.txt记录了所有需要获取解析的域名
> config.json文件可以配置上述文件的路径

## 使用说明
>1. 首先进入init目录，执行init可执行文件，加载原始的hosts配置到RawHosts文件（仅第一次使用需要初始化，后续再次使用该产品，无需执行该步骤）
>2. 然后进入gogithub目录，使用root权限或者是管理员身份执行gogithub可执行文件

## 最后
> 可以先给个star支持一下，未来会不断更新，增加更多实用的功能，比如
>
> 1. 开机自启动
>
> 2. 定时刷新hosts文件
>
> 3. 配置hosts文件的刷新时间间隔等等...
>
> 4. 增加hosts文件信息的回滚撤销