# VSCodeEnv (for myself)

## 插件

- **Alignment** : 代码对齐
- **ascii-unicode-escape** : ascii 与 unicode 互转
- **Auto-Open Markdown Preview** : markdown 预览
- **Beautify**: 代码美化
- **Better Comments** : 注释美化
- **change-case** : 大小写命名法转换
- **Code Runner** : 代码运行器
- **Color HighLight** : 颜色高亮
- **Color Picker** : 取色器
- **Color Info** : 色码转换
- **Git History** : Git 历史
- **gitignore** : 添加到 .gitignore
- **lua-for-vscode** : lua 支持
- **vscode-luacheck** : vscode lua 语法检查和提示
- **luaide** : 自称在 vscode 上打造最优秀的 lua ide 环境，实际上表现的也很不错，不过就是要付费
- **markdownlint** : Marakdown 语法检测
- **XML Tools** : XML 高效操作
- **To Do Tasks** : 优秀的 todo 文档
- **filesize** : 在底部状态栏显示当前编辑文件的大小
- **其他语言类插件就不列出来了**

## 主题美化

- **Material Icon Theme** : 扁平化图标
- **One Dark Pro** : 黑暗系主题

## Lua Snippet

- 使用 LuaIDE 的代码段提示，使用其 Cocos2D-X 的 API
- 自定义代码段提示，使用 VSCode 提供的用户代码段，手动撸

## To Do Tasks

```TODO
To Do Tasks 的使用方式:
    ☐ 这是非常重要的标记 @critical
    ☐ 这是高优先级的标记 @high 
    ☐ 这是低优先级的标记 @low
    ☐ 这是今天需要的标记 @today
    ☐ 这是用户自定的标记 @user
    ☐ 添加一个任务使用 CMD+Enter
    ✔ 完成一个任务使用 Alt+D @done (2017-9-17 18:01:44)
    ☐ 取消一个完成的任务继续用 Alt+D
    ✘ 删除一个任务使用 Alt+C @cancelled (2017-9-17 18:03:29)
    ☐ 任务可以有子任务，它的子任务可以被折叠
        ☐ 这是一个子任务 @critical 
            ☐ 这又是一个子任务 @high  
                ☐ 这还是一个子任务 @low 
                    ☐ ...
```
这是预览效果：
![](https://ws3.sinaimg.cn/large/006tKfTcgy1fjmqjbxtr2j30s80h6tcn.jpg)

## Better Comment

```lua
--//? question
--//! alert
--//* highlight
--//TODO
--//// remove
--[[
    /*
    ? question
    ! alert
    * highlight
    TODO todo
    //// remove
    */
--/]]
```
这是预览效果：

![](https://ws3.sinaimg.cn/large/006tKfTcgy1fjmxo0ms2jj30l40hwgmt.jpg)
<!-- ![](https://ws3.sinaimg.cn/large/006tKfTcgy1fjmqfz0ujuj30a20i6gmm.jpg) -->
