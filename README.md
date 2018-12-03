# scel2txt

搜狗细胞词库到普通文本的转换提取工具

## 使用
将从搜狗官方网站下载的 `.scel` 文件放入 `scel` 文件夹，然后运行

```bash
python ./scel2txt.py
```

将在 `scel` 文件夹得到后缀为 `.txt` 的同名词库。词库格式为一行一词。

## 致谢
绝大部分的转换代码都来自 [zhongxinwang](https://github.com/xwzhong) 的 [small-program](small-https://github.com/xwzhong/small-program) 项目