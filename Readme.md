# 思源主题: mixture(dark)
![preview](preview.png)

本主题基于[Atom One Dark](https://github.com/zqhjl/Siyuan-Atom-OneDark)修改，并借鉴了Pure Dark和Lavender等其他主题。
主题主颜色为青色，主字体为**思源黑体**，代码字体为**Fira Code**，亮色主题见[Mixture Light](https://github.com/Achuan-2/siyuan-themes-mixture-light)


❤特色
- 目前文件未保存的时候，标签页字体为灰色，保存成功为粉色
- 本主题暂时**隐藏了标签页的文件图标**
- 增大了当前标签页的最大文字宽度
- 点击任务列表有动效，完成的任务列表样式暂定以颜色减淡来取代删除线（删除线太不优雅了，这样也可以多一个选择，可以自行添加），并对特殊样式包括图片、高亮、加粗、超链接、代码块等也进行一定减淡、颜色更改处理
- 弹出窗口有左右展开动效
- 优化了对行内公式和公式块的大小问题

⚠前排提示：
- 如果需要**更改字体**，请在主题文件夹下的 theme.css 中，`--b3-font-family:'SourceHan',... ` 将思源黑体删除、置后或更改
- 任务列表完成默认无删除线，如果需要完成任务列表自动添加的删除线，可以自行添加删除线（`Ctrl+D`），或者自行修改主题：搜索"完成的待办事项删除线",将`/* text-decoration: line-through; */`取消注释注释
- 由于个人习惯一级标题作为文章标题索所以默认为居中，可能对习惯把一级标题作为正文标题的童鞋不太友好，可以搜索`标题样式`，将h1`.vditor-reset h1 {text-align: center;...}`中的`text-align: center;`改为`/* text-align: center; */`以注释，并将`.vditor-reset h1:after {...}`样式全部删掉

---
## v0.2.2/2021-3-8

- 一级标题去掉下划线保持居中，三级竖线调细
- 列表间距调整
- 超链接添加下划线
- 调整数学公式块大小
- 修复预览模式的行内代码左侧凸出的问题
- 调整块引用卡片的阴影
- 添加块引用悬浮动画


## v0.2.1/2021-3-8

- 多窗口当前页面标签页添加底框
- 对待办列表中的代码块复制按钮进行透明度调整
- 调近代办样式的距离
- 调整标签与普通文字距离
- 块引用下划线间距调整"历史代办"
- 对完成的待办事项内容全部调整透明度

## v0.2.0/2021-3-7

又双叒叕来更新了，这是一次大刀阔斧的更新！😏
- 鉴于原先阿里巴巴普惠体版权问题，**更改中文主字体为思源黑体**
- 修复因为标签页与上方选项栏的间距导致主题会出现**两个滑块的问题**
- 修复将body设置了perspective造成的**字体模糊**，**修改窗口弹出动效**为Y轴翻转
- 调整标签页字体放大效果，**调整选中的标签页最大文字宽度**
- **减小文件树列表间距**
- **修正调整字号后主题待办列表checkbox无法完全覆盖checkbox基本样式的bug**
- 对标题样式代码、标签等样式进行重写，使得其能**适配不同字号大小**
- 代码块渲染目前**支持显示部分语言名称**，但语言名称显示会随着滑块移动，待完善
- 修改==高亮==样式, 对完成的待办中高亮样式进行调整
- 调整块引用下划线与文字的间距
- 调整完成的待办列表中的代码样式透明度
- 修改标签样式，圆角增大
- 针对MathJax行内公式和公式块大小进行优化（之前只设置KaTex的）
- 初步对主题css即时渲染行内元素样式的颜色代码进行优化，部分使用变量
- 标签页margin-left改为margin-right

## v0.1.8/2021-3-4

好了，我改不动了，要是没什么大问题近期就不改主题了，毕竟自己笔记都没咋写，光弄花架子了
- 更改行内公式和公式块大小
- 代码块和公式块编辑缩进，同时考虑到有行号时代码块的缩进。（摸索半天，太折腾了，这边改完那边变）
- 增大标签页之间的距离
  
## v0.1.7/2021-3-4

概括：更追求主题的统一性了，算是一个大改进，不像之前总是追求花里胡哨，其实蛮伤眼的也不易读的📣
- 改进行内代码的css代码，避免其影响代码块编辑区
- 对代码块编辑区样式进行修改，之前编辑区是行内代码的样式有点突兀
- 对行内公式编辑样式进行修改
- 减淡引用块背景颜色，去掉背景，更有沉浸感，个人很喜欢
- 又双叒叕更改h2标题颜色，变淡了一点

## v0.1.6/2021-3-4

- 修正行内公式块有多余空间的问题
- 对已完成代办事项中的加粗、斜体、删除线、超链接进行优化，事项中含有的图片透明度设置为60%，鉴于原先默认设置的删除线可能不方便查看，暂时决定取消，可以自行添加删除线(Ctrl+D)，或者自行修改主题,搜索"完成的代办事项下划线",`/* text-decoration: line-through; */`取消注释
- 更改h3标题与上下文的间距
  
## v0.1.5/2021-3-3

- 修复从edge复制的超链接，形如[思源笔记更新日志(ld246.com)](https://ld246.com/tag/siyuan-announcement)，分多块hover高亮的问题
  
## v0.1.4/2021-3-3

- 仿照Lavender设置界面动效，更改设置的关闭按钮颜色和hover背景
- 仿照Passion设置选中项的圆角
- 更改弹出菜单样式

## v0.1.3/2021-3-3

- 更改字体：主字体为阿里巴巴普惠体，代码字体为Fira Code
- 更改标题，统一色系为天蓝色
- 更改引用块样式
- 更改标签页样式，去除标签页前的文件图标样式
- 更改超链接hover颜色
- 更改块引用样式
- 添加图片阴影

## v0.1.2/2021-2-23

- theme.css 初步整理
- 标题样式修改,h3标题增加左边框，h4-h6颜色为白色
- 对flowchart、graphviz、plantuml渲染块背景进行优化
- 更改超链接颜色
- 复选框勾选增加动效

## v0.1.0/2021-2-22

- 标题样式更改
- 超链接样式更改
- 复选框样式更改
- 代码块更改
- 行内代码样式更改
- 分割线样式更改
- 标签样式更改
- list focus样式更改