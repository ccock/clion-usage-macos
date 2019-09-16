## TODO

- [x]: new c++ project for learn shortcut 
- [x]: project configuration: include, macro, build, test, debug ...
- [x]: legacy code of configuration

## issues

- rename folder but include path not changed?
- only support gtest, boost-test, catch2

## configurations

- ToolChain for windows： https://www.jetbrains.com/help/clion/quick-tutorial-on-configuring-clion-on-windows.html

- plugins
clion->preferences->plugins
    - Rainglow Color Schemes
    - Key Promoter X
    - Makefile support
    - docker : https://www.jetbrains.com/help/clion/docker.html

- Theme
clion->preferences->Appearence&Behavor->Appearence->Theme
clion->preferences->Editor->Color Scheme->General

- 快捷键配置
clion->preferences->Keymap->Keymaps 选择快捷键风格

- Cmake自动更新cache
Settings / Preferences | Build, Execution, Deployment | CMake

- 代码提示的匹配模式
clion->preferences->Editor->Code Completion Case sensitive completion选择First letter

- 代码生成
clion->preferences->Live Templates 默认有for, iter, itit，可以根据自己喜好添加

- 智能提示
写代码的过程成，如果出现问题，此时点击左侧的小灯泡或者按 Alt + Enter，IDE会给出建议的解决方案

- 文件模板
配置->Editor->Code Style->File and Code Template

- include guard
配置->Editor->Code Style->C/C++->Header Guard Style : ${UUID}
| Editor | Code Style | C/C++ | Naming Convention, you can configure the style for Header Guards to be used when creating a new header file

- Unused code
| Preferences | Editor | Inspections | C/C++ | Unused code | Unused include directive


## project

- 通过“CMakeLists.txt”文件配置工程细节
- 通过非cmake配置project：https://www.jetbrains.com/help/clion/compilation-database.html
- makefile project: https://www.jetbrains.com/help/clion/managing-makefile-projects.html


## shortcuts

https://wiki.jikexueyuan.com/project/intellij-idea-tutorial/keymap-introduce.html

### perspective

- ctrl + Alt + N： 创建文件、类
- CMD+Shift+F12 : 切换full mode
- Cmd + E : 切换文件和窗口
- Cmd + F12: Outline current file

### navigation

- forward / backward : Cmd + Shift + left/right
- 转到定义： Cmd + B
- 转到实现类的定义，而非接口： Cmd + Alt + B
- 类层次导航： Ctrl+H
- 打开某个类方法的继承关系列表： Ctrl + Shift + H
- 转到父类接口：Cmd + U
- 转到最后编辑处： Cmd + Shift + delete
- 跳到行： Cmd+L
- 头文件和实现文件切换： Ctrl + CMD + UP
<!-- - UML导航 ： Ctrl+Alt+U -->

### code

- 智能助手： ctrl + shift + space，可以连按两次
- 语句自动完成： Cmd + Shift + Enter
- 重写格式化    CMD+Alt+L    
- 自动行缩进    CMD+Alt+I
- 选取需要重写的方法 Ctrl + O 
- 提示参数： Cmd + P
- 自动插入代码模板：Cmd + J
- 自动生成类内代码： Cmd + N
- 自动生成具有环绕性质的代码，比如：if..else,try..catch, for, synchronized 等等，使用前要先选择好需要环绕的代码块。（常用）： Cmd + Alt + T
- 续接下行代码： Ctrl + Shift + J
- 自动生成类代码： ALT + Enter
- F1: 宏展开提示

### search

- 全局搜索： shift + shift
- 查找class：CMD+ O
- 查找file：CMD+Shift+O
- 查找symbol：CMD+Alt+O
- 查找快捷键和action ： CMD + Shift + A
- 查找引用： ALt+F7
- 查找调用链： Ctrl + ALt + H
- 查找头文件包含关系： Cmd + Ctrl + H
- 多选查找：Cmd + F，随后Ctrl+G

### edit

- word left/right : Alt + left/right
- line left/right : Cmd + left/rifht
- 按照代码块选择： Alt + UP/DOWN
- copy line : Cmd+D
- move up, move down : Cmd+Shift+Up/Down
- 移除整行代码 : Cmd+delete
- 注释： 行： CMD + / ; 块 ： CMD + Shift + /
- 查找和替换 ： CMD+R
- 高亮： Cmd + Shift + F7
- 列选： Cmd + Shift + 8
- 大小写转化： Cmd+Shift+U
- 多选： Ctrl + Cmd + G

### refactoring

- 重构this：Ctrl+T
- 重命名： Shift+F6
- 抽取方法：Cmd+Alt+M
- 抽取变量：Cmd+Alt+V
- 抽取常量：Cmd+Alt+C
- 抽取参数：Cmd+Alt+P
- 抽取定义：Cmd+Alt+D
- 抽取typedef：Cmd+Alt+K
- 内联：Cmd+Alt+N
- 移动：F6

### build & run

- 编译当前project： Cmd+F9
- 编译当前文件： Cmd+Shift+F9
- 编译运行当前工程：Ctrl+R
- 编译运行当前文件：Ctrl+Shift+R


