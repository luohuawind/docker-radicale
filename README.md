# docker-radicale

基于 Radicale 的 CalDAV/CardDAV 日历和联系人服务器，使用 Docker 一键部署。

## 功能特性

- 支持 CalDAV / CardDAV 协议
- Docker 一键部署
- 多架构支持（amd64 / arm64）
- 环境变量配置
- 只读容器，安全加固

## 快速开始

```bash
# 运行容器
docker run -d --name my-calendar \
    -p 5232:5232 \
    -v ./data:/data \
    my-calendar:latest

# 查看运行状态
docker ps




