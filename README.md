# pgyvpn-mcp

面向蒲公英 SD-WAN 异地组网场景，覆盖从账号注册、MCP 接入配置、创建虚拟网络、添加软件成员与硬件设备、全平台客户端下载登录，到连通性验证的端到端流程。

支持对等网络、集散网络、自定义网络及公网版四种组网拓扑，适用于远程办公、跨地域内网互通、设备远程运维等场景。

## 安装

将本仓库内容复制到 `~/.workbuddy/skills/pgyvpn-mcp/` 即可。

## 前置要求

需要先配置蒲公英 MCP Server：

1. 登录 [蒲公英管理平台](https://console.sdwan.oray.com/) → MCP → 生成新密钥
2. 将配置写入 `~/.workbuddy/mcp.json`
3. 在 WorkBuddy 连接器管理页面信任该 MCP Server

## 文件说明

- `SKILL.md` — 技能定义文件（7 步完整流程）
- `references/tools_reference.md` — MCP 工具参考文档

## 相关链接

- [蒲公英官网](https://pgy.oray.com/)
- [蒲公英管理平台](https://console.sdwan.oray.com/)
- [客户端下载](https://pgy.oray.com/download/)
- [帮助文档](https://service.oray.com/)
