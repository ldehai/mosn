# MOSN

[![Build Status](https://travis-ci.com/sofastack/sofa-mosn.svg?branch=master)](https://travis-ci.com/sofastack/sofa-mosn)
[![codecov](https://codecov.io/gh/alipay/sofa-mosn/branch/master/graph/badge.svg)](https://codecov.io/gh/alipay/sofa-mosn)
[![Go Report Card](https://goreportcard.com/badge/github.com/alipay/sofa-mosn)](https://goreportcard.com/report/github.com/alipay/sofa-mosn)
![license](https://img.shields.io/badge/license-Apache--2.0-green.svg)

[English](README_EN.md)

MOSN 是一款使用 Go 语言开发的网络代理软件，作为云原生的网络数据平面，旨在为服务提供多协议，模块化，智能化，安全的代理能力。MOSN 是 Modular Open Smart Network-proxy 的简称。MOSN 可以与任何支持 xDS API 的 Service Mesh 集成，亦可以作为独立的四、七层负载均衡，API Gateway，云原生 Ingress 等使用。

## 功能

MOSN 作为一款开源的网络代理，具有以下核心功能：

+ 通过 xDS API 对接 Service Mesh，支持全动态资源配置运行
+ 支持 TCP 代理、HTTP 协议、多种 RPC 代理能力
+ 支持丰富的路由特性
+ 支持可靠后端管理，负载均衡能力
+ 支持网络层、协议层的可观察性
+ 支持多种协议基于 TLS 运行，支持 mTLS
+ 支持丰富的扩展能力，提供高度自定义扩展能力
+ 支持无损平滑升级
## 下载安装

使用 `go get -u sofastack.io/sofa-mosn` 命令或者将项目代码克隆到 `$GOPATH/src/sofastack.io/sofa-mosn` 目录中。

**注意事项**

- 如果您想使用 v0.5.0 以前的版本，需要使用 `transfer_path.sh` 命令修复代码包导入问题。

- 如果您使用的是 Linux 系统，需要修改 `transfer_path.sh` 脚本中的 `SED_CMD` 的变量，请参阅脚本中的注释。

## 文档

- [MOSN 文档](https://www.sofastack.tech/projects/sofa-mosn/)

- [MOSN 版本更新日志](CHANGELOG.md)

## 贡献
请参阅[贡献者指南](CONTRIBUTING.md)。

## 社区

请参阅 [SOFAStack community](https://github.com/sofastack/community) 了解社区运行细则和获取社区资源。

使用钉钉扫描下面的二维码加入 MOSN 用户交流群。

![SOFAMosn 用户交流钉钉群二维码](https://gw.alipayobjects.com/mdn/rms_91f3e6/afts/img/A*NyEzRp3Xq28AAAAAAAAAAABkARQnAQ)

