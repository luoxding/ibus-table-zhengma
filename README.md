＃＃ 配置指南

```shell
# 安装依赖，似乎不用，仅装iubs
apt install ibus-table

# 转换码表ibus-table-createdb -s zhengma.txt, 同目录下会生成zhengma.db
ibus-table-createdb -s zhengma.txt

# 复制码表文件到码表目录
cp zhengma.db /usr/share/ibus-table/tables

＃ 复制图标文件到图标目录
cp zhengma.svg /usr/share/ibus-table/icons
```

＊＊配置＊＊：在 ibus 里配置添加郑码，在系统设置－区域与语言，设置添加郑码。
root 用户好像只在 ibus 里添加郑码就行了。然后郑码就出现在 ibus 输入法列表里了。

等有空了我将对目前的码表扩展词库。
