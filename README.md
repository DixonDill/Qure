# Qure

![Qure Logo](https://raw.githubusercontent.com/DixonDill/Qure/master/Other/Qure_Logo.png)

## 简介

Qure 是一套为策略组精心设计的图标组，现主要用于 **Loon**（同样适用于 Quantumult X 等支持 `img-url` 的软件）。在这里你可以订阅、下载并更新它们。

图标原作者为 [Koolson](https://github.com/Koolson/Qure)，本仓库为 DixonDill 的合并整理版。

## 本仓库说明（合并版）

- 本仓库由 DixonDill 的 `Qure` 与 `QuantumultX` 两个仓库合并而成，统一命名为 **Qure**，是唯一的图标仓库；原 `QuantumultX` 仓库已在合并后删除。
- 经逐文件比对，两仓库图标内容完全一致，合并未丢失任何图标；`QuantumultX` 独有的 `icon` 文件仅含一个换行符，系误建文件，未并入。

## 图标目录

- `IconSet/`：彩色图标 296 个
- `IconSet/Dark/`：深色图标 296 个，与彩色版同名
- `Other/`：Logo 与效果预览图

图标涵盖默认（Direct、Proxy、Reject 等）、通用、服务（Apple、Google、Microsoft 等）、应用（Telegram、Twitter、Netflix、Spotify 等）、地区（Hong_Kong、Japan、United_States 等）、服务器（AWS、Azure、GCP 等）与媒体等类别，完整名单见下方效果图预览。

## 在 Loon 中使用

在 Loon 配置文件的 `[Proxy Group]` 中，给策略组加上 `img-url` 参数，指向本仓库的图标：

```
香港节点 = url-test, 香港, img-url = https://raw.githubusercontent.com/DixonDill/Qure/master/IconSet/Hong_Kong.png
Telegram = select, 香港节点, 日本节点, img-url = https://raw.githubusercontent.com/DixonDill/Qure/master/IconSet/Telegram.png
```

- 在 [IconSet 页面](https://github.com/DixonDill/Qure/tree/master/IconSet) 找到需要的图标并记下文件名；
- 深色图标把路径换成 `IconSet/Dark/文件名.png`；
- 图标名称中的空格以英文下划线 `_` 代替，并注意字母大小写；
- 保存配置后在 Loon 中重新加载配置即可生效；图标更新后若未刷新，清除 Loon 的图标缓存后重试。

## 补充说明

1. 转载请注明出处，谢谢！
2. 归档图标：部分图标默认不展示，但仍可正常引用，具体见下方归档图标预览图。
3. 需要新增策略图标，请提 Issue 说明图标名称，并附上相关图标资源链接。

## 免责声明

1. Qure 项目内所涉及图标、LOGO 仅为资源共享、学习参考之目的，不保证其合法性、正当性、准确性；切勿使用 Qure 项目做任何商业用途或牟利；
2. 遵循避风港原则，若有图片和内容侵权，请在 Issues 告知，核实后删除，其版权均归原作者及其网站所有；
3. 本人不对任何内容承担任何责任，包括但不限于任何内容错误导致的任何损失、损害；
4. 任何人直接、间接使用 Qure 项目相关资源，均应仔细阅读本声明，一旦使用、转载 Qure 项目任何相关教程或资源，即被视为已接受此免责声明。

## 更新日志

图标集由原作者 Koolson 维护至 v3.1.0，各版本完整更新日志见原仓库：https://github.com/Koolson/Qure

## 效果图预览

彩色版：

![彩色版预览](https://raw.githubusercontent.com/DixonDill/Qure/master/Other/Qure_Preview_All.png)

深色版：

![深色版预览](https://raw.githubusercontent.com/DixonDill/Qure/master/Other/Qure_Dark_Preview_All.png)

归档图标：

![归档图标预览](https://raw.githubusercontent.com/DixonDill/Qure/master/Other/Qure_Preview_Archived.png)
