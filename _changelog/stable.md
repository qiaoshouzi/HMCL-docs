---
title:  "稳定版更新日志"
permalink: /changelog/stable.html
date:   2021-08-22 23:18:02 +0800
categories: 更新日志
toc: true
---

![Hits](https://hits.zkitefly.eu.org/?tag=https%3A%2F%2Fdocs.hmcl.net%2Fchangelog%2Fstable.html)

*Notice: changelogs are written in Chinese.*

<h1 id="nowchange">HMCL 3.6.15</h1>

- 下载
  - GP-4085: 更新模组下载页游戏版本列表至 1.21.8 (by Glavo)
- 错误修复
  - GP-4086: 修复安装 Oracle JDK 后可能无法使用启动器的问题 (by Glavo)
  - GP-4096: 修复无法使用部分日志字体的问题 (by Glavo)
  - GP-4097: 修复 InstallersPage 可能意外地显示滚动条的问题 (by Glavo)

# HMCL 3.6.14

版本介绍: [cv42290390](https://www.bilibili.com/opus/1088221679199453185)

- 启动器
  - GP-3938: 使用 Java 8 打开启动器时弹出弃用警告 (by Glavo)
  - GP-4032: 使用 Java 8 运行时禁止更新 (by Glavo)
  - GP-3854: 右键主页“启动游戏”按钮时展开版本列表菜单 (by Glavo)
  - GP-3875: 使用工作路径下的 .hmcl 文件夹存放所有配置文件 (by Glavo)
  - GP-3914: 启动时在日志中记录用户设备的 CPU 信息 (by Glavo)
  - GP-3893: 启动时在日志中记录用户设备的 GPU 信息 (by Glavo)
  - GP-3974: 更新日志中仅显示本次更新内容 (by Wulian233)
  - GP-4040: 更新模组数据 (by Glavo)
- 游戏管理
  - GP-3734: 折叠高级设置中不适用于当前系统的选项 (by Wulian233)
  - GP-3951: 新增原理图管理界面 (by Glavo)
  - GP-3991: 新增世界管理页面 (by Glavo)
- 整合包
  - GP-3547: 重构 MultiMC 整合包兼容功能 (by Burning_TNT)
  - GP-3836: 自动安装页面隐藏 mcbbs 项 (by 辞庐)
  - GP-3981: 忽略与版本 JSON 指定的 Java 相冲突的 Java 检测规则 (by Glavo)
- 账户
  - GP-3823: 默认限制境外地区使用离线账户功能 (by Glavo)
  - GP-3853: 优化离线账户名称中包含非 ASCII 字符时的提示 (by Glavo)
  - GP-3860: 添加 XBox 封禁相关提示 (by 辞庐)
- 下载
  - GP-2794: 支持下载光影 (by Burning_TNT)
  - GP-3247, GP-3799: 支持下载部分特殊版本 (by zkitefly)
  - GP-3830: 将模组/整合包/资源包的默认下载源调整为 Modrinth (by Burning_TNT)
  - GP-3876: 优化代理设置功能 (by Glavo)
  - GP-4011: 更新模组下载页游戏版本列表至 1.21.7 (by Glavo)
- 外观
  - GP-3800: 优化整合包导出类型选择界面 (by Wulian233)
  - GP-3822: 统一导出和导入整合包页面样式 (by 辞庐)
  - GP-3944、GP-3949: 优化版本列表为空时，主页切换版本菜单的显示效果 (by GeneralK1ng)
- 本地化
  - 优化软件文案，完善英语、西班牙语、俄语翻译
- 错误修复
  - GP-3768: 修复模组下载界面无法正常翻页，以及类别会在切换下载源时出错的问题 (by Burning_TNT)
  - GP-3769: 修复离线账户切换模型时左侧 3D 预览不会即时更新的问题 (by Burning_TNT)
  - GP-3770: 修复 Windows 平台部分语言编码下无法打开 Minecraft 中文 Wiki 的问题 (by Burning_TNT)
  - GP-3771: 修复资源包和世界下载对话框标题为“模组下载”的问题 (by 辞庐)
  - GP-3772: 修复模组管理内“安装到当前版本”与“下载到本地文件夹”实际效果相同的问题 (by Burning_TNT)
  - GP-3776: 修复 LiteLoader 下载相关问题 (by Burning_TNT)
  - GP-3778: 修复 macOS 平台使用 Rosetta 2 转译运行启动器时无法正确识别系统架构的问题 (by YiZhiMCQiu)
  - GP-3793: 修复启动器更新下载对话框中有两个相同进度条的问题 (by Burning_TNT)
  - GP-3797: 修复无法打开游戏购买页面的问题 (by zkitefly)
  - GP-3806: 修复 RISC-V 平台游戏识别 CPU 名称出错的问题 (by Glavo)
  - GP-3814: 修复 Fabric Metadata 无效时 FabricInstallTask 抛出 NPE 的问题 (by Glavo)
  - GP-3817: 修复自定义背景图片路径包含无效字符时启动器崩溃的问题 (by Glavo)
  - GP-3826: 修复无法正常解析 NeoForge 愚人节版本的问题 (by Burning_TNT)
  - GP-3856: 修复导出过长日志时可能发生 OutOfMemoryError 的问题 (by Glavo)
  - GP-3863: 修复游戏崩溃分析窗口乱码的问题 (by Glavo)
  - GP-3866: 修复下载游戏内容页面搜索新内容时分页按钮未重置的问题 (by Wulian233)
  - GP-3874: 修复在已安装游戏版本的自动安装界面中游戏版本名称报红的问题 (by e74yp8)
  - GP-3877: 修复启动器退出时未压缩日志的问题 (by Glavo)
  - GP-3883: 修复当离线账户用户名中包含中文字符时，无法使用 LittleSkin 皮肤的问题 (by e74yp8)
  - GP-3888: 修复无法一键更新整合包的问题 (by mzdluo123)
  - GP-3901: 修复模组/整合包下载界面无法完整显示多行信息的问题 (by e74yp8)
  - GP-3922、GP-4036: 修复部分 Linux 环境中未正确选择默认字体的问题 (by Glavo)
  - GP-3942: 修复无法正确处理版本服务器地址设置中的 IPv6 地址的问题 (by Glavo)
  - GP-3968: 修复 Java 管理页面中无法添加 IKVM 的问题 (by Glavo)
  - GP-3995: 修复 Controller 未能读取 JAVA_VERSION_TIP 的问题 (by Burning_TNT)
  - GP-3996: 修复在 schematics 文件夹不存在的情况下，打开投影管理页面会抛出异常的问题 (by Glavo)
  - GP-3998: 修复模组搜索返回结果为空时下载界面异常的问题 (by Burning_TNT)
  - GP-4001: 修复自动安装界面中更改 MC 版本后无法点击安装键的问题 (by Burning_TNT)
  - GP-4007: 修复光影下载页面中标签名称未翻译的问题 (by Glavo)
  - GP-4009: 修复 macOS 上无法读取 CPU 信息的问题 (by Glavo)
  - GP-4015: 修复代码中的拼写错误 (by kfatyuip)
  - GP-4016: 修复 MultiMC 整合包中包含相同标识符的库时无法导入的问题 (by Burning_TNT)
  - GP-4065: 修复添加游戏文件夹页面缺少灰色背景的问题 (by 辞庐)
  - GP-4069: 修复使用 JavaFX 25 EA 时下载界面布局错位的问题 (by Glavo)

# HMCL 3.6.12

版本介绍：[cv41174209](https://www.bilibili.com/opus/1050013108961017859)

- 启动器
  - GP-3457: 实验性支持 WebP 格式的背景图片
  - GP-3523: 模组列表页中按下 ESC 键时取消选中
  - GP-3601: 更新模组数据
  - GP-3603: 支持临时隐藏预览版提示
  - GP-3610, GP-3613: 统一并优化软件内日期时间格式
  - GP-3619: 在启动器日志中记录处理器型号（仅 Windows）
  - GP-3620: 修改整合包下载对话框内「安装到当前版本」按钮的文本为「安装整合包」，修正对话框标题
  - GP-3621: 点击安装整合包时无条件关闭整合包下载对话框
  - GP-3629: 删除全局游戏设置页面的离线账户更换皮肤提示
  - GP-3628: 在版本的游戏设置中添加「复制全局游戏设置」选项
  - GP-3650: 点击账户卡片空白处时切换账户
  - GP-3653: 优化 NBT 查看器，修复无法打开空 mca/mcr 文件的问题
  - GP-3663: 启动时尝试从 HMCL_DIRECTORY 中加载字体
  - GP-3665, GP-3673: 支持双击复制世界信息、安装 Java 页面信息、模组详情对话框信息
  - GP-3689: 在世界管理界面显示世界图标
  - GP-3675: 更新 Microsoft 应用商店链接
  - GP-3711: 优化世界管理界面，新增备份世界页面
  - GP-3736: 优化账户信息卡片的显示效果
  - GP-3432: 优化滚动页面时的性能
  - GP-3747: 在日志中记录编码信息
  - GP-3749, GP-3750: 消除使用 Java 24 运行 HMCL 时控制台中的弃用警告
  - 优化软件文案，完善英语、西班牙语、俄语翻译
- 下载
  - GP-3484, GP-3744: 更新模组下载页游戏版本列表至 1.21.5
  - GP-3517: 游戏下载页面添加搜索功能
  - GP-3244: 安装新游戏/整合包时检查版本名称是否包含非 ASCII 字符
  - GP-3476: 在 Linux RISC-V 平台为「下载 Java」对话框添加 [banshanjdk-8](https://www.zthread.cn/) 下载地址
  - GP-3605: 添加 NeoForge 的 BMCLAPI 代理支持
  - GP-3625: 允许用户在「下载 → 游戏」页面搜索时调整搜索范围
- 外观
  - GP-3458: 降低窗口阴影质量以改善性能
  - GP-3442: 添加打开启动器时的窗口动画
  - GP-3652: 添加关闭启动器时的窗口动画
  - GP-3657: 添加最小化和还原启动器窗口的动画
  - GP-3666, GP-3677: 禁止标题栏按钮获取焦点
  - GP-3668, GP-3680: 优化动画效果
  - GP-3687: 更新全部图标至 Material Symbols
  - GP-3695: 优化离线登录对话框
  - GP-3723: 在游戏崩溃界面添加滚动条
  - GP-3729: 为更新日志对话框添加平滑滚动
  - GP-3730: 为世界信息页面和版本高级设置页面背景添加半透明遮罩
  - GP-3755: 更新 macOS Dock 栏图标
- 跨平台
  - GP-3536: 优化对 Linux RISC-V 64 平台的支持
- 错误修复
  - GP-3490: 修复 OAuth 登录时轮询过于频繁的问题
  - GP-3464: 修复在更新日志界面无法拖动启动器窗口的问题
  - GP-3503: 使用 Zink 渲染器时禁用 DRI3
  - GC-`5fd52bb`: 皮肤缓存不再保存到 .minecraft 目录
  - GC-`81b3911`: 修复按 ESC 键时文本框内的值没有保存的问题
  - GC-`260f4b6`: 修复输入对话框中 ESC 键不起作用的问题
  - GC-`7d12ef6`: 修复内存滑块提示被设备内存进度条覆盖的问题
  - GC-`78e15d1`: 修复游戏设置中内存没有实时刷新的问题
  - GC-`6f53da1`: 完善模组下载界面
  - GP-3252: 修复无法补全部分第三方 Minecraft 客户端游戏资源的问题
  - GC-`56d20a5`, GC-`397edae`: 修复 Linux 平台调整窗口大小的问题
  - GP-3531: 修复在 FreeBSD x86-64 平台未正确替换 LWJGL 本地库的问题
  - GP-3541: 修复安装 MultiMC 整合包后没有设置版本图标的问题
  - GP-3549: 修复 macOS 平台 HMCLauncher.sh 不会显示 Java 下载页面的问题
  - GP-3594: Java 下载对话框中切换包类型时不应重置版本字段
  - GP-3598: 修复使用自定义字体时未正确设置字重的问题
  - GP-3602: 修复使用系统 GLFW/OpenAL 时无法启动部分游戏版本的问题
  - GC-`ecafc9d`: 修复安装新游戏页面中组件框的高度问题
  - GP-3618: 修复无法识别 Intel64 架构的问题
  - GP-3626: 修复离线账户选择 Steve/Alex 皮肤时模型错误的问题
  - GP-3622: 修复在非官方支持的平台上 Minecraft 1.21 与 Sodium 不兼容的问题
  - GP-3638: 修复 NeoForge 版本识别错误的问题
  - GP-3645: 修复在 macOS 平台无法找到通过 DMG 安装的 Java 的问题
  - GP-3623: 修复离线账户皮肤对话框「本地皮肤图片文件」部分选项文字被覆盖的问题
  - GP-3651: 当微软账户 Token 过期时应当刷新账户
  - GP-3654: 修复标题过长时窗口异常的问题
  - GP-3676: 修复对话框关闭动画缺失的问题
  - GP-3708: 修复更改游戏 Java 时路径显示错误的问题
  - GP-3733: 删除更新日志对话框中多余的换行符
  - GP-3735: 修复在 Modrinth 上获取模组版本时未正确处理 404 响应的问题
  - GP-3752: 修复取消导出整合包时弹出报错对话框的问题
  - GP-3759: 修复无法解析部分 Java 版本号的问题

# HMCL 3.6.11

- 启动器
  - GP-3233: 在 Linux/FreeBSD 平台打开日志、模组等位置时会选中该文件
  - GP-3274: 优化日志窗口
  - GP-2988: 添加 Java 管理页面，优化查找、下载、自动选择 Java 等功能 （[BV1WvCUY4EwK](https://www.bilibili.com/video/BV1WvCUY4EwK)）
  - GP-3280: 在删除账户和认证服务器时弹出确认提示
  - GP-3314: 优化 Linux/FreeBSD 平台上显示的系统信息
  - GP-3282: 发现更新弹窗添加取消按钮
  - GP-3237: 设置页面添加打开启动器日志文件夹按钮
  - GP-3264: 在 Linux LoongArch64 平台支持 Minecraft 1.20.2+
  - GP-3234: 在安装新游戏版本页面的默认游戏版本名称中包含已选择的加载器名称
  - GP-3221: 模组管理搜索操作更改为文本更新后触发
  - GP-3375: 支持微软账户上传皮肤
  - GP-3032: 检查模组更新界面加入全选/取消全选复选框
  - GP-3373: 更新模组下载页游戏版本列表至 1.21.3
  - GP-3232: 支持在模组管理页面通过右键单击模组查看模组详情
  - GP-3427: 更新 EXE 图标
  - GP-3435: 在游戏下载列表中添加 Minecraft Wiki 链接
  - 优化文本描述/翻译
- 下载
  - GP-3251, GP-3259: 支持从官方源下载 Forge
  - GP-3256: 选择要安装的 Forge 版本时显示版本发布时间
- 外观
  - GP-3271: 隐藏版本管理的 Fabric API 和 QSL/QFAPI 自动安装选项
  - GP-3088: 隐藏整合包安装页面上的整合包文件位置
  - GP-3278: 调换游戏管理侧边栏上“自动安装”和“模组管理”的顺序
  - GP-3347: 当整合包没有描述时，隐藏查看整合包描述按钮
  - GP-3378: 优化首页公告，添加隐藏按钮
  - GP-3396, GP-3397, GP-3406: 优化账户列表页面按钮图标
  - GP-3424: 调整字体选择组合框的默认宽度
  - GP-3450: 使最小化按钮居中
- 错误修复
  - GP-3030: 修复导入 MultiMC 整合包时未移除 JVM 参数两侧引号的问题
  - GP-3224: 修复部分游戏版本无法正常安装的问题
  - GP-3227: 修复模组详情页图标显示问题
  - GP-3142: 修复日志窗口错误地将 authlib-injector 日志识别为 ERROR 类型的问题
  - GP-3306: 修复下载界面中，模组等资源版本图标全部显示为“R”而不是对应版本标签图标的问题
  - GP-3308: 修复启动 Modrinth 整合包时补全已禁用的 mod
  - GP-3324: 修复对话框标题和按钮未使用用户字体的问题
  - GP-3364: 修复 Windows 上无法识别为当前用户安装的字体的问题
  - GP-3379: 修复部分按钮无法用键盘触发的问题
  - GP-3380: 修复部分控件响应鼠标任意按钮点击的问题
  - GP-3392: 修复微软账户登录对话框中“忘记密码”链接
  - GP-3421: 修复打开游戏设置页时启动器崩溃的问题
  - GP-3425: 修复 HMCLauncher 无法正确识别 Windows on Arm 平台的问题
  - GP-3434: 修复为 Minecraft 1.20.5+ 自动选择 Java 17 的问题
  - GP-3439: 修复 Minecraft 1.20.2+Forge 默认图标错误的问题
  - GP-3470: 修复无法读取部分 Forge 模组信息的问题

# HMCL 3.5.9

- 启动器
  - GP-3121、GP-3194: 微软登录界面对 Xbox 400 错误给予提示
  - GP-3097: 更新 Linux ARM64 支持
  - GP-3197: 优化对 Linux RISC-V 64、FreeBSD x86-64 平台的支持
  - GP-3058: 支持解析更多游戏版本号
  - GP-3092: 移除 KOOK 入口
- 下载
  - GP-3023: `特定游戏设置 - 自动安装` 中禁止升级或卸载由其他启动器安装的游戏组件
  - GP-3089、GP-3114: 优化 `下载 - 模组` 中模组版本推荐逻辑
- 外观
  - GP-3181: 支持使用 `HMCL_FONT` 环境变量指定字体
- 错误修复
  - GP-2838: 修复本地模组查看信息时标签错误的问题
  - GP-3023: 修复 1.20.4 版本 Forge 和 OptiFine 同时安装的情况下游戏无法启动的问题
  - GP-3027: 修复低版本游戏在开启版本隔离后没有声音的问题
  - GP-3028: 修复 `全局游戏设置 - 版本隔离` 中错误展示路径的问题
  - GP-3066: 修复 CurseForge 搜索 API 对翻页总量计算不正确的问题；修复 `下载 - 模组` 切换下载源时不刷新页面的问题
  - GP-3081: 修复启动器退出时卡死的问题
  - GP-3082: 修复整合包 NeoForge 版本识别不正确的问题
  - GP-3117: 修复 `下载 - 游戏` 选择游戏版本后窗口标题重复的问题
  - GP-3126: 修复无法正确读取微软账户 Token 过期时间的问题
  - GP-3128: 修复 1.21 NeoForge 无法下载的问题
  - GP-3130: 修复 1.8 及 1.9 可能无法安装 OptiFine 的问题
  - GP-3133、GP-3136: 修复 1.7.10-pre4 版本 Forge 安装问题
  - GP-3160: 修复游戏启动过程中部分情况下点击取消按钮会导致启动器出错的问题
  - GP-3197: 修复部分平台无法运行 1.14 ~ 1.14.2 的问题
  - GP-3198: 修复无法同时安装 LiteLoader 与 Forge 的问题
  - GC-85b68ad: 修复 Linux 系统上无法找到 Mojang 提供的 Java 的问题

# HMCL 3.5.8

- 启动器
  - GP-2947: 更新模组和整合包翻译信息
  - GP-2951: 优化了启动器长期运行后的性能表现
  - GP-2942: 游戏版本的图标现在支持 JPG、GIF 等格式
  - GP-2950: 启动器启动后，将自动加载同目录下的 `font.ttf` 或 `font.otf`
- 下载
  - GP-2958: 还原对 MCBBS 的鸣谢。谢谢你，MCBBS！
  - GP-3031: 适配新版本 NeoForge 模组，修复部分模组无法被正确识别的问题
  - GP-3045: 支持自动安装 Java 21
- 错误修复
  - GP-2943: 修复了高版本启动器内皮肤预览与游戏内真实皮肤不匹配的问题
  - GP-2986: 修复了微软登录部分情况下会错误提示“没有购买记录”的问题
  - GP-2989: 修复部分情况下，整合包导入会失败的问题
  - GP-2994: 修复自动安装界面 NeoForge 图标在高分辨率屏幕上会很模糊的问题

# HMCL 3.5.7

- 启动器
  - GP-2929、GP-2904、GP-2915: 更新翻译
  - GP-2905: 更改语言选项添加重启后生效的提示
  - GP-2885: 在 Linux 系统上且处于未知桌面环境时，禁用删除至回收站功能
  - GP-2889: 删除 Mojang 登录支持
  - GP-2897: 主界面移除联机大厅按钮，添加引导用户进入官方 QQ 群的按钮
  - GP-2888: 移除设置 - 赞助页面
  - GP-2862: 默认不进行降级更新（手动切换更新源时依然会正常提示)

- 下载
  - GP-2921: 允许使用系统属性禁用系统代理
  - GP-2917: 不再尝试下载 `.pack.xz` 文件
  - GP-2921: 当系统属性 `java.net.useSystemProxies` 被设置为 `false` 时不再使用系统代理
  - GP-2912: 当下载失败时，打印重定向链至日志
  - GP-2916: 在 CurseForge 下载源中搜索时始终会按照模组标题与关键词的相似性排序
  - GP-2886: 自动下载 Java 支持下载 Java 21

- 外观
  - GP-2856: 当加载网络背景图片超时时回退至默认背景，解决启动时卡死的问题

- 整合包
  - GP-2881: 修复无法安装带有 NeoForge 的 Modrinth 整合包的问题

错误修复: 

- **GP-2908 \[重要\]: 修复微软账户登录失败的问题**
- GP-2939: 修复游戏启动时包装命令会被添加两次的问题的问题
- GP-2936: 修复无法读取远古版本版本号的问题
- GP-2919: 修复 Minecraft 1.6 之前的版本没有声音的问题
- GP-2920: 修复了在 CurseForge 下载源中使用中文搜索无法呈现结果的问题
- GP-2933: 修复高版本变更离线皮肤可能不生效的问题
- GP-2928: 修复自动更新整合包导出页面教程链接错误问题
- GP-2926: 修复保存 ETag 索引可能写入不全的问题
- GP-2804: 修复游戏非正常退出提示界面文字编码显示错误的问题
- GP-2906: 修复未初始化 FileDownloadProvider 的问题
- GP-2869: 修复下载 Java 不会尝试备用下载源的问题
- GP-2871: 修复导出启动脚本时无法正确处理“游戏启动前执行命令”和“游戏结束后执行命令”的问题，现在会预解析命令

# HMCL 3.5.6

- GP-2864: 改善在非 Windows 平台任务栏图标的质量
- GP-2859: 修复 Forge 和 NeoForge 安装失败的问题
- GP-2840: 修复 Linux RISC-V 64 平台的支持
- GP-2846: 修复使用 Java 19+ 启动游戏时，游戏 JVM 字符编码参数错误导致控制台乱码的问题
- GP-2857: 修复搜索页面搜索结果为空，即总页面为 0 时点击最后一页按钮会跳转到不存在的页面导致无法正常使用的问题，现在会自动禁用该按钮
- GP-2858: 修复 Windows 下自定义命令中使用 $INST_DIR 等带有反斜杠的内容会错误触发转义导致路径错误的问题
- GP-2859: 修复启动器在版本 JSON 缺失 Patches 信息时无法获得游戏版本，导致游戏启动参数重复、管理版本表现不正确等问题
- GP-2836: 更新启动器发布页至官网，而不是 MCBBS
- GP-2700: 优化游戏版本比较规则，现在模组下载界面能够正常排序 Minecraft 正式版、快照版或其他版本了
- GP-2805: 默认开启自动选择并发数
- GC-9361719、GC-420d77d、GP-2839: 移除 MCBBS 的下载源和鸣谢文本，介于其下载源已不再可用
- GP-2801: 添加部分 CurseForge 的分类翻译文本
- GP-2742: 支持在游戏崩溃提示界面显示 Fabric Loader 给出的警告信息
- GP-2813: 当日志中含有部分常见报错信息时，即使进程退出代码为 0 也显示游戏崩溃提示界面
- GP-2828: 支持检测 Forge 模组重复导致的游戏崩溃
- GP-2834: 支持检测 Forge 安装不完整导致的游戏崩溃
- GP-2785: 支持检测 JVM 堆内存不足导致的游戏崩溃
- GP-2790: 支持检测 Forge 与高版本 Java 不兼容导致的游戏崩溃
- GP-2760: 更新对 Linux RISC-V 64 系统的支持
- GP-2745: 修复只会从 MCBBS 源下载 authlib-injector 的问题
- GP-2746: 修复部分情况下修改并发下载数量会导致启动器崩溃的问题
- GP-2756: 修复网络下载缓存当缓存索引文件所在目录不存在时会导致下载失败的问题
- GP-2758: 修复 HMCL 背景网络图片 URL 输入框会持续触发网络请求的问题，现在仅会在输入结束后加载图片
- GP-2768: 修复自动安装界面错误提示 Quilt 与 Fabric API 不兼容的问题，现在两者能够同时安装了
- GP-2770: 修复 CurseForge 整合包启动时检测游戏完整性极其缓慢的问题，并支持显示进度条；修复光影包会被错误的安装至模组文件夹的问题
- GP-2775: 修复本地 NeoForge 模组被错误地识别为 Forge 模组的问题
- GP-2788: 修复选中使用非默认皮肤的离线账户时，启动器主页头像会被错误地显示为默认皮肤头像的问题，现在正常显示用户选择的皮肤头像
- GP-2789: 修复皮肤预览界面 Alex 皮肤被显示为 Classic 模型的问题，现在会使用 Slim 模型
- GP-2791: 修复世界管理界面下载按钮图标不正确的问题，使更加贴切其功能
- GP-2799: 修复由低版本 HMCL 升级后，窗口位置不会显示在正中央的问题
- GP-2810: 修复本地模组搜索功能无法正确处理大小写，导致有大写字母的模组永远不可能被搜索到的问题
- GP-2811: 修复 Java 8 上 JavaFX 不存在时英文提示不正确的问题
- GP-2827: 修复启动器主窗口隐藏后从日志窗口复制内容导致启动器崩溃的问题
- GP-2835: 修复关于界面上启动器图标仍为旧版图标的问题
- 完善 Quilt 支持
- 添加了对 NeoForge 的支持
- 打开启动器时会验证 JavaFX 完整性
- 放弃 EXE 版本与 Windows XP 的兼容性，如果需要可以使用 JAR 版本（当前版本的 EXE 版本并未放弃，在不久的将来会构建不支持 Windows XP 的 HMCLauncher 并分发。如果是从旧版本通过启动器更新升级到最新版本，则 HMCLauncher 并不会被覆盖修改，仍然支持 Windows XP）
- 支持从 Modrinth 更新模组，会比对 CurseForge 和 Modrinth 取最新版本
- 支持在模组管理和模组搜索中显示所支持的模组加载器
- 支持日志窗口中的复制操作，选中要复制的行，按 Ctrl+C 即可
- 日志窗口默认显示行数调整至 1000
- 添加光影包文件夹和日志文件夹打开按钮
- 在离线账户创建时对不合法的账户名做出警告
- 游戏安装界面现在会隐藏不可用的模组加载器
- 现在系统 GLFW 和系统 OpenAL 也可在 Windows 上使用
- 在出现 InternalError 的时候提示用户 Java 损坏
- 添加了翻页按钮，用户可以按照 50 个一页分页查找
- 在从 CurseForge 上按照“名称”搜索排序时能正确按照相关度显示
- 在中文搜索时会额外按照中文相关度排序
- 移动依赖信息显示到模组/整合包/资源包文件详情界面，分依赖类型显示文件依赖详情
- 资源选择页面会根据所选版本的模组加载器、游戏版本推荐最新的合适资源
- 整合包安装界面添加跳转至搜索整合包页面的按钮
- 将阿里镜像源替换至腾讯云镜像源
- 不默认修改 `forceUnicodeFont` 游戏设置
- 优化文件详情无效依赖的提示
- 更新了启动器图标
- 新增 OptiFine 图标
- 支持查看 NBT 文件，将 NBT 文件拖动至主页面即可查看
- 添加龙芯新世界支持
- 添加了更多的日志分析规则
- 支持导出待更新模组列表
- 支持导出游戏运行栈文件
- 适配高版本自动进入服务器功能
- 对多个语言文件进行了更新和修正
- 标题黑白颜色跟随主题设置
- 优化游戏进程被 SIGKILL 信号终止时的提示
- 网络请求支持 Gzip 解压
- 等待启动游戏时显示假进度条
- 记忆窗口位置，打开程序时会按照上次的窗口位置
- 在模组管理页面点击搜索按钮时自动将光标定位到输入框
- 将网络超时设置为 8000 毫秒
- 支持在 Linux/FreeBSD 删除操作时移动至回收站
- 优化日志性能
- 支持复制账户的 UUID
- 支持 FreeBSD x86-64
- 添加帮助按钮

# HMCL 3.5.5

- 启动器
  - 拒绝在被 Fractureiser 病毒感染的设备上启动 HMCL（若检测到将会提示并退出，[详情](https://github.com/fractureiser-investigation/fractureiser#readme)）
  - 检测 HMCL 是否处于 macOS 上的 App Translocation（macOS 使用了 [App Translocation](https://lapcatsoftware.com/articles/app-translocation.html) 机制，可能会自动将 HMCL 移动至 `/private/var/folders` 中的临时文件夹内，导致用户关闭 HMCL 后游戏数据和设置丢失）
  - 日志分析窗口中显示物理内存大小
  - 更新 Minecraft 购买链接
  - 优化 SSL 异常报错信息
  - 添加更多日志分析规则
  - 更新游戏版本号检测性能
  - 添加隐藏测试版提示开关
  - 在 Linux 上支持 `MESA_LOADER_DRIVER_OVERRIDE` 环境变量，适配 Zink 驱动程序
  - 更新翻译

- 下载
  - 更新搜索版本号

- 游戏设置
  - 添加删除游戏资源文件按钮
  - 将版本高级设置拆分至单独页面中
  - 添加环境变量设置
  - 添加渲染器设置

- 跨平台
  添加 Linux RISC-V 64 平台支持

错误修复: 

- 修复日志分析窗口的渲染问题
- 修复在 Minecraft 1.20 不能正常使用游戏内聊天功能的问题
- 修复在 Windows on ARM 平台上的启动问题
- 修复使用系统 GLFW 选项对 1.19+ 不生效的问题
- 修复无法使用 macOS aarch64 JRE 启动部分版本的问题
- 修复一些崩溃问题

# HMCL 3.5.4

- 启动器
  - 多人联机功能暂时下线维护 [详情](https://hmcl.huangyuhui.net/api/redirect/multiplayer-migrate)
  - 不再支持添加 Mojang 账户 [迁移至微软账户](https://aka.ms/MinecraftMigration)
  - 默认在用户文件夹中存储账户信息，提高安全性
  - 优化性能与资源占用，解决卡顿问题
  - 优化文本提示
  - 优化自动内存分配功能
  - 优化游戏 JVM 参数，改善游戏性能
  - 优化自动选择 Java 功能
  - 优化自动下载 Java 功能
  - 优化微软账户登录功能
  - 支持 Gif 格式背景图
  - 优化高分辨率屏幕上图标的显示效果
  - 更新反馈页面
  - 默认加入 Little Skin 登录选项
  - 为 Linux 提供 sh 格式构建
  - 新添加 JVM 选项 `-Dhmcl.home`，允许用户自行指定 HMCL_DIRECTORY

- 下载
  - 支持整合包下载页使用中文搜索
  - 支持下载安装 Modrinth 整合包
  - 支持 Quilt 自动安装
  - 默认将搜索排序修改为“热度”

- 游戏设置
  - 默认开启“自动选择合适的 Java”
  - 添加世界信息界面，允许玩家在启动器内查看详细世界信息以及修改世界设置
  - 添加模组列表搜索
  - 优化自动内存分配

- 跨平台
  - 适配 Windows ARM64 平台
  - 适配 Linux LoongArch64（旧世界）平台
  - 适配 Linux ARM32 平台
  - 适配 Linux ARM64 平台
  - 适配 MacOS ARM64 平台

此外，本版本包含数百项错误修复，详情请查看[测试版更新日志](https://docs.hmcl.net/changelog/dev.html)。

# HMCL 3.5.3

- 启动器
  - 支持多人联机
  - 自动选择新添加的 Authlib-injector 服务器
  - 添加修改离线账户皮肤的功能，允许使用本地图片和 LittleSkin 等皮肤站
  - 自动检测系统内安装的 OpenJDK，包括 Liberica/Microsoft/Zulu/AdoptOpenJDK
  - 允许修改启动器字体
  - 游戏崩溃时提供崩溃分析报告
  - 添加帮助页面
  - 更换默认背景图
  - 修复微软登录页可能白屏的问题
  - 任意页面按 ESC 键可返回上一页
  - 修复启动器打开时提示找不到 DST ROOT CA X3 证书的问题
  - 修复对系统平台的识别错误导致部分平台不能正确下载 JavaFX 的问题
  - 修复 Log4j 远程代码执行漏洞

- 游戏启动
  - 支持官方启动器为 Minecraft 启动参数提供的一些占位符
  - 兼容 TLauncher 游戏客户端
  - 如果在 macOS/Windows ARM 设备上使用 HMCL，HMCL 会优先使用 x86 的 JDK 运行游戏
  - 解决 Java 16 下部分 mod 不能正常运行的问题
  - 修复 Windows 下打开使用 Unicode UTF-8 提供全球语言支持选项后启动器无法打开的问题
  - 修复不能启动 BakaXL 安装后的游戏的问题
  - 修复不能正常启动 Minecraft 1.5 及以下版本的问题（需要手动删除 options.txt）

- 下载
  - 启动 Minecraft 1.17 及以上版本时自动下载官方提供的 Java 16
  - 支持 CurseForge 整合包、Mod、资源包、地图 下载
  - 支持 1.17 Forge 的自动安装与游戏启动
  - 支持 1.17 下 OptiFine 与 Forge 同时安装
  - 添加模组批量更新功能
  - 添加自动选择下载源的功能
  - 允许修改默认的下载并发数

- 游戏设置
  - 允许在 Java 自定义参数内覆盖启动器默认提供的启动参数，而不需要再禁止启动器生成默认参数
  - 允许在 Minecraft 自定义参数内使用 ${game_directory} 等占位符
  - 改进版本管理和游戏设置的界面
  - 添加修改游戏进程优先级的功能
  - 支持自动选择游戏内存大小
  - 添加查看模组详细介绍及打开其官方页面的功能
  - 添加 Linux 下使用系统 GLFW 及 OpenAL 的功能
  - 自定义本地库路径，允许 M1 设备运行 ARM 版本的 Minecraft
  - 添加自动选择 Java 选项，省去提示用户需要更改 Java 版本的步骤

- 整合包
  - 支持使用 Fabric 作为 Mod 加载器的 CurseForge 整合包
  - 支持我的世界中文论坛整合包规范第二版，兼容 CurseForge 整合包格式，允许导入 MultiMC
  - 修复安装整合包时可能崩溃的问题
  - 修复 MCBBS 整合包实现不符合规范的问题

# HMCL 3.3.188

- 启动器
  - 修改界面
  - 更新俄语翻译
  - 改善游戏下载速度
  - 添加复制游戏实例功能
  - 支持微软正版账户登录
  - 自动设置游戏的默认语言为中文
  - 兼容 Java11+，在 Java 11+ 上运行时会自动下载 JavaFX
  - 配置文件会优先选择启动器同目录而不是工作目录
  - 支持 Authlib-injector 账户上传皮肤
  - 支持 Authlib-injector 服务器用邮箱以外的账户登录
  - 上传皮肤时自动检测 Steve、Alex 模型
  - 刷新账户时将显示进度条
  - 自定义本地库路径，允许 M1 设备运行 ARM 版本的 Minecraft
  - 启动 Minecraft 1.17 时自动下载官方提供的 Java 16
  - 允许第三方修改 HMCL 的 BMCLAPI 下载源，从而支持第三方下载源
  - 自动检测系统内安装的 OpenJDK，包括 Liberica/Microsoft/Zulu/AdoptOpenJDK
  - 修复启动 Minecraft 1.0 时不会停止等待游戏启动的问题
  - 修复首次打开整合包会弹出 3 个新建账户窗口的问题
  - 修复运行在 Java 12+ 时列表和下拉菜单不能正常显示的问题
  - 修复鼠标指针不正常的问题
  - 修复添加外置登录的正版账号后会与普通正版账号冲突的问题
  - 修复因为线程过多导致在 macOS 系统上运行崩溃的问题
  - 修复重命名游戏版本点击移动窗口而不是移动光标的问题
  - 尝试修复在游戏启动后启动器直接关闭时导致游戏卡死的问题
  - 修复启动器设置 HTTP 代理后，游戏无法访问网络的问题
  - 修复下载支持库文件失败时启动器崩溃的问题
  - 修复不能识别部分数据包的问题
  - 修复 Windows 下打开使用 Unicode UTF-8 提供全球语言支持选项后启动器无法打开的问题
  - 解决 Java 16 下部分 mod 不能正常运行的问题

- 整合包
  - 更新游戏整合包后会显示新的版本号
  - 支持我的世界中文论坛整合包标准
  - 修复更新整合包下载地址不能使用在线下载自动更新整合包的问题
  - 修复服务端自动更新整合包不能更新游戏、Forge 版本的问题

# HMCL 3.3.172

- 启动器
  - 修改界面
  - 更新俄语翻译
  - 改善游戏下载速度
  - 添加复制游戏实例功能
  - 添加清理缓存文件夹按钮
  - 修改默认下载源为 MCBBS
  - 提升与 ServerSync 的兼容性
  - 添加为正版账号上传皮肤的功能
  - 支持调整并记住启动器窗口大小
  - 在日志窗口添加导出游戏日志功能
  - 现在会校验资源索引文件的完整性
  - 现在启动器代理设置对启动后的游戏有效
  - 在启动游戏、安装游戏等界面显示总下载速度
  - 游戏崩溃后显示游戏崩溃报告而不是游戏日志
  - 允许在启动游戏按钮上滑动鼠标滚轮切换游戏
  - 在删除 Mod、世界、数据包时弹出删除确认提示
  - 允许使用在启动器同目录下的 authlib-injector.jar 文件
  - 在游戏崩溃后的第二次启动时自动检查资源和支持库文件是否完整
  - 添加启动器的 JVM 参数 -Dhmcl.font.override=fontfamily 以允许 Linux 用户更换字体以解决白屏问题
  - 修复部分整合包无法修改启动时游戏窗口大小的问题
  - 修复终止游戏后启动器不会停止等待的问题
  - 修复 1.5.2 及以下版本不能下载资源文件的问题
  - 修复某些情况下启动游戏时，启动器会崩溃的问题
  - 修复进入游戏设置后无法重命名部分游戏版本的问题
  - 修复不能在 Java 17 下载 Forge 和自动更新的问题
  - 修复重命名版本时，输入不合法的新名字后的错误提示
  - 修复重命名被依赖的版本后，会破坏其他依赖这个版本的版本的问题
  - 修复在自定义游戏运行目录时，输入不合法的路径会导致崩溃的问题
  - 修复在输入特定错误的 authlib-injector 服务器地址时会导致启动器崩溃的问题

- 自动安装
  - 在 OptiFine 库缺失时可以自动补全
  - 提升自动安装功能与其他启动器的兼容性
  - 在当前下载源下载失败后自动重试其他下载源
  - 在启动游戏、安装游戏等界面显示明确的安装步骤
  - 安装游戏向导内可直接切换下载源，而不需要返回启动器设置页面
  - 支持同时安装 Minecraft 1.14.4 及以上版本的 Forge 和 OptiFine
  - 自动安装页面将提示不兼容的第三方库，比如 Forge 和 Fabric 不兼容
  - 修复无法安装 Forge 1.12.2 2852 的问题
  - 修复在 Curse 整合包安装遗漏部分 Mod 的问题
  - 修复在 Curse 整合包安装部分成功时删除游戏的问题
  - 修复 1.5.2 及以下版本安装 Forge 后启动失败的问题
  - 修复从 MCBBS 下载源下载文件可能会下载到空文件的问题
  - 修复 1.12.2 同时安装 Forge, OptiFine 时无法进入游戏存档的问题

- 整合包
  - 修复整合包配置丢失后整合包游戏版本不能修改配置的问题
  - 修复服务器自动更新整合包更新时可能会出现 AccessDeniedException 的问题

# HMCL 3.2.149

- 启动器
  - 改进部分错误提示
  - 更新繁体中文语言文件
  - 在主界面账户栏添加鼠标滚轮便捷切换游戏账户
  - 在主界面账户栏添加鼠标悬浮提示以查看完整游戏名
  - 修复原版游戏用熔炉图标标识的问题
  - 修复无法取消启动过程和安装过程的问题
  - 修复无法启动使用 Vivecraft 安装器新安装的游戏的问题
  - 修复启动 1.15 时不会停止等待的问题
  - 修复 Windows 下导出启动脚本对双引号的错误转义
  - 修复部分正版账号登录 1.7.10 会导致游戏崩溃的问题
  - 修复关闭 JVM 检查时仍然会检查 java.exe 是否合法的问题
  - 修复使用 BMCLAPI 不能下载 authlib-injector 和加载游戏列表的问题

- 自动安装
  - 添加 MCBBS 下载源
  - 在资源索引文件不合法时尝试重新下载
  - 添加 Fabric 的 BMCLAPI 和 MCBBS 下载源支持
  - 现官方下载源下载 Forge 时依赖文件不再强制从 BMCLAPI 下载
  - 修复重复下载游戏依赖文件的问题

- 整合包
  - 导出整合包时将剔除所有日志文件和 CustomSkinLoader 的缓存
  - 修复导入 HMCL 整合包时无法安装 Forge 的问题
  - 修复无法下载 Curse 整合包部分 Mod（如潘马斯）的问题
  - 修复下载 Curse 整合包 Mod 失败后会删除整合包的问题
  - 修复下载服务端整合包没有对链接转义而无法下载的问题

# HMCL 3.2.139

- 启动器
  - 添加西班牙语，更新英语、俄语翻译
  - 主页面按回车键启动游戏
  - 游戏列表内点击列表项进入游戏设置，右键列表项打开游戏管理菜单
  - 不再强制使用 java.exe
  - 日志窗口允许关闭自动滚动
  - 避免安装游戏时输入的游戏名称不符合 Windows 系统要求
  - 修复输入某些错误的 Java 路径时崩溃的问题
  - 修复浏览 Mod 列表可能出现的崩溃问题
  - 修复无法识别 Java 12、13 的问题

- 自动安装
  - 添加 Fabric 自动安装
  - 新安装的游戏可以修改游戏版本
  - 修复 OptiFine 自动安装
  - 修复同时安装 Forge 和 OptiFine 自动安装失败的问题
  - 修复某些情况下无法安装 1.12.2 及以下版本的 Forge 的问题
  - 修复导出整合包导入时无法安装 1.13 Forge 和 OptiFine 的问题
  - 修复部分情况下无法下载 Forge 安装包的问题
  - 修复无法安装 1.14 和 1.15 游戏的问题

- 整合包
  - 允许从给定链接下载整合包并进行安装
  - 支持导出 MultiMC 整合包
  - 修复无法下载 Curse 模组的问题
  - 修复下载 Curse 整合包失败后会删除游戏的问题

- 服主功能
  - 添加 authlib-injectors.json，允许服主将添加账号页面更改为默认添加指定服务器的 Authlib Injector 账户
  - 访问 [https://www.huangyuhui.net/index.php/2019/09/09/109/](https://www.huangyuhui.net/index.php/2019/09/09/109/) 以查看添加方法
  - 添加服务器自动更新整合包，允许服务器远程更新游戏客户端
  - 访问 [https://www.huangyuhui.net/index.php/2019/11/12/118/](https://www.huangyuhui.net/index.php/2019/11/12/118/) 以查看添加方法


# HMCL 3.2.130

- 启动器
  - 在启动器更新时显示更新日志
  - 启动前检查是否是 Java 8~10
  - [https://www.huangyuhui.net/index.php/2019/01/27/83/](https://www.huangyuhui.net/index.php/2019/01/27/83/)支持整合包自带 Java 运时
  - 在缓存目录无效时自动更改设置
  - 在登录对话框中添加注册链接
  - 将游戏依赖的动态链接库解压到 .minecraft 中而不是系统临时文件夹
  - 更新 authlib-injector

- 自动安装
  - 只从 BMCLAPI 获取 Forge、OptiFine 列表
  - 添加 BMCLAPI 赞助信息
  - 支持 Forge 1.13 的自动安装
  - 支持 Forge、LiteLoader、OptiFine 的手动更新
  - 添加提示部分版本的 Forge 和 LiteLoader 不兼容的问题
  - 下载库文件失败时提供更友好的提示
  - 安装游戏时更新资源文件
  - 启动时下载缺失的 Minecraft 本体文件
  - 在安装游戏失败时删除不完全的游戏

- 游戏管理
  - 支持对 Fabric 模组的管理
  - 支持数据包列表页面、模组管理面板多选
  - 添加刷新模组列表的按钮
  - 在未安装 Mod API 的情况下禁用模组管理面板
  - 忽略游戏存档名中的颜色转移符
  - 隐藏游戏版本不匹配的游戏存档
  - 添加打开存档文件夹的菜单
  - 删除在版本管理页面中的删除游戏和重命名按钮
  - 提醒用户在修改版本独立选项时需要注意游戏文件的转移
  - 支持拖拽游戏存档压缩包到游戏界面以便安装游戏存档

- 整合包
  - 支持整合包拖拽到主页面打开安装向导
  - 支持新版 MultiMC 整合包的导入
  - 在更新整合包时进行游戏文件的备份
  - 从 Cursemeta 上下载 Curse 上被删除的 Mod 文件

- 修复
  - 修复头像不显示头盔层的问题
  - 修复删除模组时可能导致的崩溃
  - 修复刷新数据包列表时可能的崩溃问题
  - 修复启动器皮肤预览异常的问题
  - 修复下载失败后无法删除游戏版本的问题
  - 修复刷新版本列表时的卡顿问题
  - 修复 mods 不是文件夹时无法安装模组的问题
  - 修复启动按钮无法根据背景颜色更改字体颜色的问题
  - 修复 Java 10 上 UI 错位的问题
  - 修复启动 Curse 整合包时尝试下载被禁用的模组的问题
  - 修复皮肤图片文件损坏时导致的崩溃问题
  - 修复配置文件格式不正确时导致的崩溃问题
  - 修复 Curse 整合包更新失败的问题
  - 修复自动更新弹出气泡的界面错乱问题
  - 修复下载资源文件时潜在的崩溃问题
  - 修复导入整合包时的乱码问题
