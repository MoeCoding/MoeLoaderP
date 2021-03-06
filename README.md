[![Pull Request Welcome](https://img.shields.io/badge/Pull%20request-welcome-brightgreen.svg)](#)

# MoeLoader-P


## 安装 & 使用 & 更新记录

> http://leaful.com/moeloader-p

## 关于 MoeLoader-P 

MoeLoader-P 全称为 MoeLoader PlusOneSecond，诞生于 2018-09 ，为 Moeloader 图片浏览和收集工具的衍生分支续命版，对原 MoeLoader 代码进行了大量重构，精简了部分功能，增强了实用功能，美化了界面。 MoeLoader 原作者为 esonic ，项目地址为 https://github.com/esonic/moe-loader-v7 ，作者已销声匿迹失多年，本项目也参考了非官方版 MoeLoader Δ 项目代码，作者为 YIU ，项目地址为 https://github.com/usaginya/MoeLoader-Delta 。

![avatar](http://leaful.com/wp-content/uploads/2018/09/SNAG-2018-9-23-0.39.35.jpg)

## MoeLoader-P 特点

- 代码完全重构，将原来的自定义站点的项目 MoeSite 、SitePack 整合到原项目中，使用新的语法与类库，降低代码耦合度，更符合语法规范，使用 Task 代替 Thred ， HttpClient 代替 WebClient 等，尽量减少不必要的静态类的使用。

- 界面重构，使用了更多美化元素，使用了 Storyboard 、Effect 、VisualStateManager 、Fontawesome 、FluentWpf 等组件对软件进行美化，支持 Win10 亚克力效果。

- 增加了页码导航、标签识别、预览图缩放等功能，对搜索参数、过滤条件（分辨率、格式、评级等）进行了整合优化。

- 优化右键菜单，支持标签大爆炸，点击后直接上搜索栏；下载支持多页子项目、动态显示进度。

- 增加了B站bilibili画友、摄影站点。

- 暂时移除了导出下载列表、已浏览、预览窗口、自定义站点、背景图的功能，其他功能持续优化中。

- booru 类型站点引擎已重构，其他站点陆续跟进更新中。

- 欢迎提供建议，需要自己开发站点可以 Fork 本项目到您自己的 Repositories 中，修改您自己的版本，可以从 Core\Sites\MoeSite.cs 开始上手，若开发好了站点功能需要加入 Master Branch 的敬请 Pull Request。

- 软件神秘代码： ( smash F8 ten times )
 
## 已知Bug及计划中实现功能

- 下载文件名规则自定义

- 部分站点下载图片出错