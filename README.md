# 🚀 Cursor 免费试用重置工具

<div align="center">
<img src="https://ai-cursor.com/wp-content/uploads/2024/09/logo-cursor-ai-png.webp" alt="Cursor Logo" width="120"/>
</div>

> ⚠️ **重要提示**
> 
> 本工具当前支持版本：
> - ✅ Windows: 最新的 1.0.x 版本（已支持）
> - ✅ Mac/Linux: 最新的 1.0.x 版本（已支持，欢迎测试并反馈问题）
 
> 使用前请确认您的 Cursor 版本。


⚠️ **Cursor通用解决方案**
> 1.  关闭Cursor、退出账号、官网Setting删除账号(刷新节点IP：日本、新加坡、 美国、香港，低延迟为主不一定需要但是有条件就换，Windows用户建议刷新DNS缓存：`ipconfig /flushdns`)
> 前往Cursor官网删除当前账号
> 步骤：用户头像->Setting-左下角Advanced▼->Delete Account
>
> 2.  刷新机器码脚本，看下面脚本地址，国内可用
> 
> 3.  重新注册账号、登录、打开Cursor，即可恢复正常使用。
>
> 4.  备用方案：如果步骤 [**3**] 后仍不可用，或者遇到注册账号失败、无法删除账号等问题，这通常意味着您的浏览器被目标网站识别或限制（风控）。此时，请尝试更换浏览器，例如：Edge、Google Chrome、Firefox。（或者，可以尝试使用能够修改或随机化浏览器指纹信息的浏览器）。


---

### 🚀 一键解决方案

<details open>
<summary><b>Global Users</b></summary>


**Linux**

```bash
curl -fsSL https://raw.githubusercontent.com/haoze-evolluling/go-cursor-help/master/scripts/run/cursor_linux_id_modifier.sh | sudo bash 
```

> **Note for Linux users:** The script attempts to find your Cursor installation by checking common paths (`/usr/bin`, `/usr/local/bin`, `$HOME/.local/bin`, `/opt/cursor`, `/snap/bin`), using the `which cursor` command, and searching within `/usr`, `/opt`, and `$HOME/.local`. If Cursor is installed elsewhere or not found via these methods, the script may fail. Ensure Cursor is accessible via one of these standard locations or methods.

**Windows**

```powershell
irm https://raw.githubusercontent.com/haoze-evolluling/go-cursor-help/master/scripts/run/cursor_win_id_modifier.ps1 | iex
```

</details>


#### Windows 安装特性:

- 🔍 自动检测并使用 PowerShell 7（如果可用）
- 🛡️ 通过 UAC 提示请求管理员权限
- 📝 如果没有 PS7 则使用 Windows PowerShell
- 💡 如果提权失败会提供手动说明

完成后，脚本将：

1. ✨ 自动安装工具
2. 🔄 立即重置 Cursor 试用期
