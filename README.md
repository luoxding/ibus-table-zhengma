## 配置指南

```shell
# 安装依赖，似乎不用，仅装iubs
apt install ibus-table

# 转换码表ibus-table-createdb -s zhengma.txt, 同目录下会生成zhengma.db
ibus-table-createdb -s zhengma.txt

# 复制码表文件到码表目录
cp zhengma.db /usr/share/ibus-table/tables

# 复制图标文件到图标目录
cp zhengma.svg /usr/share/ibus-table/icons
```

**配置**：在 ibus 里配置添加郑码，在系统设置－区域与语言，设置添加郑码。
root 用户好像只在 ibus 里添加郑码就行了。然后郑码就出现在 ibus 输入法列表里了。



---

- **词条数**：
    - zhengma: 135779
    - zhengma-premium: 431483
    - 构词字: 21002

---

作为郑码十多年的用户，在linux系统上输入中文，ibus郑码已不在软件源，网上找的词库又老旧，只好将在用rime的词库修改转换成ibus格式。