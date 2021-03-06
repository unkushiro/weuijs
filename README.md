WeUI 为微信 Web 服务量身设计 [![Build Status](https://travis-ci.org/progrape/weui.js.svg?branch=master)](https://travis-ci.org/progrape/weui.js)
====

## 概述

WeUI是一套同微信原生视觉体验一致的基础样式库，由微信官方设计团队为微信 Web 开发量身设计，可以令用户的使用感知更加统一。包含`button`、`cell`、`dialog`、 `progress`、 `toast`、`article`、`actionsheet`、`icon`等各式元素。

<img src="http://77flz7.com1.z0.glb.clouddn.com/2016/weui.png" width="400">

## WeUI.js

WeUI 本身只包含样式，不包含 `javascript` 功能。为了方便使用，需要根据所使用的框架进行封装。

如果应用只是使用 `jquery/zepto` 库，那么就需要一个更轻量的封装，使之符合 `jquery/zepto` 的调用习惯。

主要封装了以下组件

- 弹出层 包含 dialog toast offcanvas loading actions 
- 消息提示：notification
- 选项卡：tabs
- 折叠面板：accordion
- 搜索：searchbar
- 表单验证：validator
- 图片上传：imguploader

## 开始上手

[使用文档](http://git-lt.github.io/weuijs/index.html)

## License

The MIT License(http://opensource.org/licenses/MIT)