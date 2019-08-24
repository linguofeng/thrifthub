# ThriftHub

## 简介

ThriftHub 是一套结合 Maven 与 NPM 管理与编译 Thrift IDL 的系统，主要是解决前端 Node 作为客户端调用 Thrift 服务时需要进行一系列比较麻烦的操作。

核心功能就是把 Thrift IDL 当作一个 Maven 的包进行版本化管理，Thrift Hub 从 Maven 中拉取 IDL 文件进行语法解析和编译成 js + tsd 文件然后进行打包 NPM 并 publish 至 NPM 仓库，Node 端只需要 npm install 安装即可使用，摆脱了手动管理和编译的麻烦

## 生态

TBD