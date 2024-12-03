# FaWeb游戏站代码模板
当前项目用于 Faweb(https://fafafa.ai) 在线一站式出海游戏网站制作工具所使用的代码模板。

# FaWeb 特点
- 无需编写代码即可实现快速上站，不懂一行代码的人也能完成游戏上站
- 支持多语言，支持游戏iframe内嵌配置，支持游戏下载链接配置，配置游戏相关视频，游戏评论，游戏推荐，游戏FAQ等配置

# 演示站点
- [https://sprunkiretake.fun/](https://sprunkiretake.fun/) Iframe嵌入模式
- [https://devourer.fun/](https://devourer.fun/) 下载链接模式



 # update.json配置注意事项
 - 当需要发布新模板版本时，文件更新列里面不可以添加文件夹目录，只需要将需要更新的文件相对路径添加到更新列表中即可。

 # 版本更新记录
 - 2024-12-03 "优化推荐游戏列表、FAQ样式",
            "修复导航菜单过多时导致子菜单位置不正确的问题",
            "修复隐私政策和用户协议菜单页面导致的过多404地址出现的问题",
            "解决推荐游戏列表为空时右侧会出现空白的问题"
 - 2024-11-29 新增游戏列表页面，优化多个组件的性能和功能，更新导航栏组件，更新资源工具函数，更新游戏页面模板消息
 - 2024-11-28 修复下载站多出h1标签的问题
   - 增加弹窗方式显示游戏页面，解决无法嵌入iframe的问题
 - 2024-11-25 修复Google Adsense 配置缺失导致编译报错
 - 2024-11-23 解决配置下载游戏页面显示404的问题，优化loading组件样式，改为黑色背景，去掉默认的游戏推荐数据
    - 删除guide页面,统一采用自定义页面功能
    - 修改导航栏在手机下样式不匹配，链接不正确问题
    - 更新站点配置文件，增加google adsense配置
 - 2024-11-19 修复游戏推荐卡片组件类型编译报错，支持多语言游戏推荐、增加子游戏页面模板
  - 修复游戏推荐组件不显示的问题
  - 支持设置游戏推荐位置
  - 修复子游戏iframe无法加载正确地址的问题
  - 修复多语言下出现路径不正确导致google抓取404的问题
