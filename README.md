<div align="center">

# ModemPro 基带进化

这是一个适用于MIUI 13/14的基带增强型Xposed模块

<a href="https://github.com/Weverses/ModemPro/actions"><img alt="Android CI" src="https://github.com/Weverses/ModemPro/workflows/Android%20CI/badge.svg"></a> <a href="https://github.com/Xposed-Modules-Repo/com.weverses.modempro/releases/"><img alt="Github Releases" src="https://img.shields.io/github/v/release/Xposed-Modules-Repo/com.weverses.modempro"></a> <a href="https://github.com/Xposed-Modules-Repo/com.weverses.modempro/releases"><img alt="GitHub all releases" src="https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.weverses.modempro/total?label=Downloads"></a> <a href="https://github.com/Weverses/ModemPro/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/Weverses/ModemPro"></a> <a href="https://github.com/Weverses/ModemPro/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/Weverses/ModemPro"></a> <a href="https://github.com/Weverses/ModemPro/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/Weverses/ModemPro"></a>

</div>

## 功能
- 为部分机型增加双卡5G支持
- 解锁N5/N8/N28频段支持
- 智能双卡切换
- 副卡VoLTE通话时可联网
- 解锁MTB的开发权限限制
- 智能双卡
- 机场/郊野/地铁网络场景优化
- 无视白名单开启郊野网络场景优化
- 全局开启5G双卡数据并发
- 全局开启5G双卡数据辅助

## 设备/系统要求
- 是小米/Redmi手机，非sgsi/gsi
- Android版本≥12, MIUI版本≥13
- 双卡5G支持需要使用骁龙865/870机型方可开启
- 智能双卡...全局5G双卡数据并发等功能需要使用小米13系列机型方可使用

## 使用方法
- 在LSPosed仓库内下载并安装
- 在LSPosed App内开启本模块，并勾选所有的推荐作用域
- 开启/关闭你需要的功能
- 重启手机后即可享用

## 已知问题
- 解锁N5/N5/N28频段后实际可能因为信令不上报导致无效，如果有大佬能解决欢迎pr

## 注意事项
- 双卡5G功能因为副卡为5G NSA，且因为目前NSA基站较少，系统不会优先连接，请自行在拨号盘输入*#*#4636#*#*锁定NR，若无服务则说明附近没有NSA基站
- 请勾选<b>全部的作用域</b>，否则可能出现在系统设置里没有功能开关的问题

## 下载
- Github Action: https://github.com/Weverses/ModemPro/actions
- Github Releases: https://github.com/Xposed-Modules-Repo/com.weverses.modempro/releases/
- Xposed Modules Repo: https://modules.lsposed.org/module/com.weverses.modempro

## 主仓库
- 源码
[ModemPro](https://github.com/Weverses/ModemPro)

## 第三方开源引用
- GNU Lesser General Public License v2.1
  [577fkj/blockmiui](https://github.com/577fkj/blockmiui)
- Apache License 2.0
  [KyuubiRan/EzXHelper](https://github.com/KyuubiRan/EzXHelper)

## License
[GNU General Public License v3.0](https://github.com/Weverses/ModemPro/blob/main/LICENSE)

