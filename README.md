# vibeLifelogAI · Releases

本仓库是 [vibeLifelogAI](https://github.com/shearfact/vibeLifelogAI) 的**发布渠道**：只包含 Releases（APK 资产）与发布流水线，不含源码。

- 源码仓库为私有；本仓库的 workflow 会按 tag 拉取私有源码完成「测试 + 构建 + 发布」
- 触发方式：`workflow_dispatch` / `repository_dispatch`（仅维护者），不接受 PR
- 运行记录构建完成后自动清理（Releases 与 APK 资产不受影响）

## 安装与升级

- APK 为**固定 debug 签名**（同一签名可平滑覆盖升级、保留应用数据）
- 从 v2.2.0-b5 及更早的随机签名包升级时，需要**最后一次卸载重装**（应用数据会清空，请先自行备份）
