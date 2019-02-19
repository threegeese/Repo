# Sublime Text3

## 安装与配置

1. 安装完成后，将用户目录下的sublime text3文件删除，然后在安装目录新建```Data```文件夹，启动sublime。（备份）
2. 设置环境变量，将安装目录添加到```path```环境下,这样可以使用```subl```命令来打开sublime。(```subl .```)
3. windows输入法问题，将 https://github.com/zcodes/IMESupport.git 克隆```\Data\Packages```文件夹下。
4. 安装Package Control，https://packagecontrol.io/installation 。
5. 在sublime text中将<kbd>TAB</kbd>缩进转化为4个空格。（```"tab_size": 4,"translate_tabs_to_spaces": true```）

## 插件

- **https://packagecontrol.io/**
<br>

- SublimeTextTrans -- 调节透明度 <kbd>Ctrl+Shift+(1-6)</kbd>
- A File Icon -- 文件图标
- Agila -- 主题
- Ayu -- 主题
- Spacegray -- 主题
<br>

- Terminal -- 打开终端 <kbd>Ctrl+Shift+t</kbd>
```Json
{
  "terminal": "D:\\cmder\\Cmder.exe",
  "parameters": ["/START", "%CWD%"]
}
```
- Emmet -- 代码智能缩写
- AutoFileName -- 路径提示
- AdvancedNewFile -- 创建文件 <kbd>Ctrl+Alt+n</kbd>
- SideBarEnhancements -- 侧栏右键功能增强
- SublimeCodeIntel -- 代码提示
- SublimeTmpl -- 代码模板 <kbd>Ctrl+Alt+(h、j、c...)</kbd>

## 快捷键

0. <kbd>F11</kbd> -- 全屏
1. <kbd>F6</kbd> -- 检测拼写
2. <kbd>Shift+F11</kbd> -- 加强版全屏
3. <kbd>Alt</kbd> -- 显示菜单
5. <kbd>Ctrl+p</kbd> -- 搜索文件，可搭配```@、:、#```使用
6. <kbd>Ctrl+Shift+p</kbd> -- 命令面板
7. <kbd>Ctrl+`</kbd> -- 打开控制台
8. <kbd>Alt+Shift+(1-5)</kbd> -- 分屏
9. <kbd>Ctrl(+、-)</kbd> -- 字体放大缩小
10. <kbd>Ctrl+k+b</kbd> -- 开、关侧边栏
<br>

1. <kbd>Ctrl+d</kbd> -- 选中单词
2. <kbd>Ctrl+l</kbd> -- 选中行
3. <kbd>Ctrl+Shift+(↑、↓)</kbd> -- 上下移动，默认当前行
4. <kbd>Ctrl+x</kbd> -- 删除当前行
5. <kbd>Ctrl+Shift+m</kbd> -- 选择当前括号内容
6. <kbd>Ctrl+Shift+Enter</kbd> -- 往上插入行
7. <kbd>Ctrl+/</kbd> -- 注释当前行
8. <kbd>Alt+F3</kbd> -- 选择所有相同的词
9. <kbd>Ctrl+鼠标选取</kbd> -- 选择多个指定位置
10. <kbd>Shift+方向键</kbd> -- 指定选取
11. <kbd>Ctrl+Shift+d</kbd> -- 向下复制
<br>

1. <kbd>Ctrl+f</kbd> -- 查找
2. <kbd>Ctrl+h</kbd> -- 替换
3. <kbd>Ctrl+g+指定数字</kbd> -- 光标跳转到指定行
4. <kbd>Ctrl+j</kbd> -- 行合并
5. <kbd>Ctrl+g</kbd> -- html的id、JavaScript的方法定位
6. <kbd>Ctrl+k+k</kbd> -- 删除光标后的内容
7. <kbd>Ctrl+(←、→)</kbd> -- 单位性的移动光标
8. <kbd>Ctrl+;</kbd> -- 查找变量名、文件名
9. <kbd>Alt+.</kbd> -- 闭合当前标签
10. <kbd>Ctrl+Shift+l</kbd> -- 在选择多行后添加