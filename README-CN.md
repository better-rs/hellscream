# hellscream:

> [Grommash Hellscream: "We Will Never Be Slaves"](https://youtu.be/eb3Zo4doFQA)

- 项目名, 取自 魔兽世界 Grommash Hellscream. 为了纪念这句口号.
- 兽人永不为奴. (魔兽世界 - Grommash Hellscream)
- 基于 Rust + Tokio + axum 的 web 框架, 开箱即用. 类似 Python Django.

## 核心目标:

- 目标用户:
  - 个人开发者.
  - 创业者.
- 服务用户规模: 支撑 0 - 1000k 用户规模(百万用户级别).
  - 更大用户规模, 不考虑. (到此阶段, 您应该融资+雇更多人来解决问题)

> 核心理念:

- 微内核+组件化. 兼容微服务模型.
- [From Small To Big](https://youtu.be/Gt_J5wKJ1-k)
  - 允许从初创阶段到中等用户规模, 都可以平滑过渡.
  - 避免出现尴尬:
    - 初始用 Django(Python) / Laravel(PHP) 等方案.
    - 用户暴增后, 使用 Go/Java/Rust 等重写.
- 部署灵活.
  - 支持 `all in one` 模型: 类似 Django.
  - 支持 `微服务矩阵` 模型: RPC + Service Registry/Discovery + API Gateway 模式.
- 完善的 CLI 工具.
  - 项目初始化
  - 项目部署
- 完善的 Admin 系统:
  - 类似 Django Admin, 开箱即用.

## TODO:

- [ ] 微内核. 兼容微服务模型. from tiny to big.
- [ ] 核心组件:
  - [ ] user:
    - account
    - role
    - permission
  - [ ] auth:
    - register/login/logout
    - oAuth:
    - web3 auth:
  - [ ] api rate limit
- [ ] 完善的 CLI 工具.
  - 项目初始化
  - 项目部署
- [ ] 完善的 Admin 系统:
  - 类似 Django Admin, 开箱即用.
  - 基于 Flutter Web 开发.

## QuickStart:

- run:

```ruby
task run

task cli:run

task cli:test

```
