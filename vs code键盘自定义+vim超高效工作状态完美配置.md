# vs code 键盘自定义快捷键，超高效工作状态完美配置

### 快速跳转，模拟vim风格（用alt+vim默认的跳转键位）

* alt+vim默认的跳转键位，alt+h\j\k\l 快速上下移动，替代 方向键盘
* 快速跳转行首，行尾和页头，页尾， 用 home, end, page up, page down, 跳转到指定行用 ctrl+g 输入行号，然后回车

### 跳出的建议框上下移动选择快捷键

 建议框 selectNextSuggestion, selectPrevSuggestion 上下选择用 alt+u, alt+n 替代方向键

 ### 用键盘快捷键显示鼠标悬停效果（显示语法提示或者翻译插件用）

 官方默认为 ctrl+i 或者 ctrl+k，为了方便单手操作，我添加一个 alt+q

 ### 一个单词一个单词快速跳转  原 ctrl+RightArrow 改成 alt+w  ctrl+LeftArrow 改成 alt+b

 ### 避免按alt键导致失去焦点，跑到标题栏的问题

 在 settings.json 中，添加以下内容 

 

``` json
"window.titleBarStyle": "custom",
"window.customMenuBarAltFocus": false,
"window.enableMenuBarMnemonics": false,

 ```

添加后，解决了按alt失焦问题，但是自定义alt键依然无效，可能和系统的默认值有关系，我是ubuntu系统

### 显示提示框 在快捷键设置中，搜索: show hover 默认快捷键 ctrl+k，个人喜欢用 alt+q 用这个命令，在完全没有鼠标的情况下，查看解释和调出翻译窗口，非常实用（翻译插件 code-translate 悬浮翻译）

### 多个工作区切换

 alt+v 打开命令行面板(workbench.action.terminal.focus)

 alt+c 运动到编辑器 (Focus First Editor Grop)

 alt+f 打开文件夹列表 alt+u 替代向上箭头（list.focusUp） alt+n(代替 线下箭头 list.focusDown)

 ### 最常用的几个快捷键

 alt+s 替代保存快捷键 ctrl+s 
 alt+w  abbreviation 用来添加emmet的封装标签

 alt+a 运行Code ranner插件的调试模式，并在插件中，设置为运行调试时同时保存文件，可以马上看到调试结果 

 alt+d 来取代esc（包含hideSuggestWidget 隐藏建议面板）

 alt+p(替代ctrl+p)调出打开的文件 俺 tab向下跳转，继续往下跳转按 alt+n（Getting started Next）alt+up向上（getting started： preview）

 

### **添加内容扩选与缩选** 

   expand selection = alt+= shrink select =  alt+_

### **文字大小写切换 大写** 

alt+shift+u  小写 alt+shift+l (说明，原来是ctrl+shift+u，因这个快捷键无法设置，做个调整，需要修改时，搜索关键词： transform，能很快定位到设置大小写的选项)

### 显示参数提示 Parameter Hints

ctrl+shift+space

### trigger suggets 触发提示

需要替换关键词时，点 ctrl+i 跳出相关的可选项，很实用

###  Leaper 插件 按tab一键离开刮号
