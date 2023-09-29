# 云崽帮助 YunzaiHelp

## 仓库简介
你的plugin插件还没有一个像样的帮助吗？快来克隆本仓库的代码，生成一个精美的帮助吧！

## 使用教程

### 克隆本仓库

```bash
#使用Gitee
git clone https://gitee.com/cunyx/YunzaiHelp.git ./plugins/你的插件名/YunzaiHelp
```

```
#使用GitHub
git clone https://github.com/cunyx-xiaomizhou/YunzaiHelp.git ./plugins/你的插件名/YunzaiHelp
```

### 移动help.js

将`./plugins/你的插件名/YunzaiHelp/help.js`移动至你的`apps`目录下(不同插件名称不同，我相信作为开发者的你是可以正确移动文件的)

### 上传背景图
将帮助背景图上传至`./plugins/你的插件名/YunzaiHelp/HelpBack/`目录下

### 填写插件信息
1. 将你插件的英文名称填入`./plugins/你的插件名/YunzaiHelp/config/PluginName_EN.txt`中
2. 将你插件的版本对应键填入`./plugins/你的插件名/YunzaiHelp/config/PluginFile.txt`中(就是package.json中的哪一项保存的是版本号信息)
3. 将你插件的正式名填入`./plugins/你的插件名/YunzaiHelp/config/PluginName_CN.txt`中

### 撰写帮助内容

#### 设置插件信息
比如设置插件的字体啊，各个部分字号大小啊，图标大小啊之类的
或者是字体颜色，某某某板块为主人触发

# 你让我咕一会吧！