<p align="center">
  <img height="100px" src="./dzx.png" />
</p>

# [discuzx](https://www.discuz.net/)

中文PC互联网最知名的社区开源软件。

## 部署

本项目基于开源应用中心 [oac](https://app.cloud.tencent.com/) 开发部署，支持一键云端部署


[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-DZX&branch=master)

### 配置

- `DB_HOST`：数据库地址
- `DB_USER`：数据库用户名
- `DB_PASS`：数据库密码
- `DB_NAME`：数据库名
- `BASE_URL`：网站url


### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
