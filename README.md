# Furnace 进度同步（公开镜像）

本仓库提供一个**未登录浏览器可直接打开**的 Furnace 进度页面：

- 进度 issue：https://github.com/FirsryFan/Furnace-Status/issues/1

## 为什么需要这个镜像

- 原仓库 `https://github.com/FirsryFan/Furnace` 未登录可正常打开（HTTP 200）。
- 但原进度 issue `https://github.com/FirsryFan/Furnace/issues/22` 未登录返回 **404**。
- 原因是该 issue 的作者账号 `firsry-agent` 对公众不可见（`https://api.github.com/users/firsry-agent` 未登录 404），GitHub 隐藏了该作者的内容。
- 仓库本身无需修复；本仓库仅作为公开可见的进度快照。

## 数据来源

数字来自原 issue #22 的最后更新（2026-11-17T04:07:01Z），不是重新测量，也不会自动同步。