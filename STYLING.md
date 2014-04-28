# 文件格式规范

整理在这里的字幕会被计算机程序自动处理。您必须严格遵守文件格式与命名规范，
以避免程序不能识别。

## 字幕文件

不论出现在什么位置，字幕文件统一使用以下格式：

*   Subrip 文本字幕格式
*   UTF-8 文件编码
*   UNIX 换行格式

这一统一格式其实对于 Windows 稍有不便，但这是自动处理脚本的要求，因此还是麻烦了
谢谢配合。

## 根目录

根目录包含未翻译的原版字幕、翻译完成的字幕和分片目录。

### 原版字幕文件

文件名统一格式：

    Liv.And.Maddie.SxxExx.original.srt

### 分片目录结构

目录结构统一使用如下格式：

    SxxExx.original
    SxxExx.checked

例如：

    S01E17.original
    S01E12.checked

SxxExx 部分表示第几季第几集，集数以 Wikipedia 为准。

*.original 包含未翻译的原版字幕分片，*.checked 包含翻译完成的字幕分片。

各个分片文件名统一格式：

    Liv.And.Maddie.SxxExx.partnn.srt

例如：

    Liv.And.Maddie.S01E14.part07.srt

### 翻译完成的字幕文件

文件名统一格式：

    Liv.And.Maddie.SxxExx.checked.srt

