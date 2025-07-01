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

> ⚠️ **MAC地址修改警告**
> 
> Mac用户请注意: 本脚本包含MAC地址修改功能，将会:
> - 修改您的网络接口MAC地址
> - 在修改前备份原始MAC地址
> - 此修改可能会暂时影响网络连接
> - 执行过程中可以选择跳过此步骤

---

### 📝 问题描述

> 当您遇到以下任何消息时：

#### 问题 1: 试用账号限制 <p align="right"><a href="#solution1"><img src="https://img.shields.io/badge/跳转到解决方案-Blue?style=plastic" alt="跳转到顶部"></a></p>

```text
Too many free trial accounts used on this machine.
Please upgrade to pro. We have this limit in place
to prevent abuse. Please let us know if you believe
this is a mistake.
```

#### 问题 2: API密钥限制 <p align="right"><a href="#solution2"><img src="https://img.shields.io/badge/跳转到解决方案-green?style=plastic" alt="跳转到顶部"></a></p>

```text
[New Issue]

Composer relies on custom models that cannot be billed to an API key.
Please disable API keys and use a Pro or Business subscription.
Request ID: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
```

#### 问题 3: 试用请求限制

> 这表明您在VIP免费试用期间已达到使用限制：

```text
You've reached your trial request limit.
```

#### 问题 4: Claude 3.7 高负载 （High Load）  <p align="right"><a href="#solution4"><img src="https://img.shields.io/badge/跳转到解决方案-purple?style=plastic" alt="跳转到顶部"></a></p>

```text
High Load 
We're experiencing high demand for Claude 3.7 Sonnet right now. Please upgrade to Pro, or switch to the
'default' model, Claude 3.5 sonnet, another model, or try again in a few moments.
```

<br>

<p id="solution2"></p>

#### 解决方案：完全卸载Cursor并重新安装（API密钥问题）

1. 下载 [Geek.exe 卸载工具[免费]](https://geekuninstaller.com/download)
2. 完全卸载Cursor应用
3. 重新安装Cursor应用
4. 继续执行解决方案1

<br>

<p id="solution1"></p>

> 临时解决方案：

#### 解决方案 1: 快速重置（推荐）

1. 关闭Cursor应用
2. 运行机器码重置脚本（见下方安装说明）
3. 重新打开Cursor继续使用

#### 解决方案 2: 切换账号

1. 文件 -> Cursor设置 -> 退出登录
2. 关闭Cursor
3. 运行机器码重置脚本
4. 使用新账号登录

#### 解决方案 3: 网络优化

如果上述解决方案不起作用，请尝试：

- 切换到低延迟节点（推荐区域：日本、新加坡、美国、香港）
- 确保网络稳定性
- 清除浏览器缓存并重试

<p id="solution4"></p>

#### 解决方案 4: Claude 3.7 访问问题（High Load ）

如果您看到Claude 3.7 Sonnet的"High Load"（高负载）消息，这表明Cursor在一天中某些时段限制免费试用账号使用3.7模型。请尝试：

1. 使用Gmail邮箱创建新账号，可能需要通过不同IP地址连接
2. 尝试在非高峰时段访问（通常在早上5-10点或下午3-7点之间限制较少）
3. 考虑升级到Pro版本获取保证访问权限
4. 使用Claude 3.5 Sonnet作为备选方案

> 注意：随着Cursor调整资源分配策略，这些访问模式可能会发生变化。

### 🚀 系统支持

<table>
<tr>
<td>

**Windows** ✅

- x64 & x86

</td>
<td>

**macOS** ✅

- Intel & M-series

</td>
<td>

**Linux** ✅

- x64 & ARM64

</td>
</tr>
</table>



### 🚀 一键解决方案





#### Windows 安装特性:

- 🔍 自动检测并使用 PowerShell 7（如果可用）
- 🛡️ 通过 UAC 提示请求管理员权限
- 📝 如果没有 PS7 则使用 Windows PowerShell
- 💡 如果提权失败会提供手动说明

完成后，脚本将：

1. ✨ 自动安装工具
2. 🔄 立即重置 Cursor 试用期

### 📦 手动安装

> 从 [releases](https://github.com/yuaotian/go-cursor-help/releases/latest) 下载适合您系统的文件

<details>
<summary>Windows 安装包</summary>

- 64 位: `cursor-id-modifier_windows_x64.exe`
- 32 位: `cursor-id-modifier_windows_x86.exe`
</details>

<details>
<summary>macOS 安装包</summary>

- Intel: `cursor-id-modifier_darwin_x64_intel`
- M1/M2: `cursor-id-modifier_darwin_arm64_apple_silicon`
</details>

<details>
<summary>Linux 安装包</summary>

- 64 位: `cursor-id-modifier_linux_x64`
- 32 位: `cursor-id-modifier_linux_x86`
- ARM64: `cursor-id-modifier_linux_arm64`
</details>

### 🔧 技术细节

<details>
<summary><b>注册表修改说明</b></summary>

> ⚠️ **重要提示：本工具会修改系统注册表**

#### 修改内容
- 路径：`计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Cryptography`
- 项目：`MachineGuid`

#### 潜在影响
修改此注册表项可能会影响：
- Windows 系统对设备的唯一标识
- 某些软件的设备识别和授权状态
- 基于硬件标识的系统功能

#### 安全措施
1. 自动备份
   - 每次修改前会自动备份原始值
   - 备份保存在：`%APPDATA%\Cursor\User\globalStorage\backups`
   - 备份文件格式：`MachineGuid.backup_YYYYMMDD_HHMMSS`

2. 手动恢复方法
   - 打开注册表编辑器（regedit）
   - 定位到：`计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Cryptography`
   - 右键点击 `MachineGuid`
   - 选择"修改"
   - 粘贴备份文件中的值

#### 注意事项
- 建议在修改前先确认备份文件的存在
- 如遇问题可通过备份文件恢复原始值
- 必须以管理员权限运行才能修改注册表
</details>

<details>
<summary><b>配置文件</b></summary>

程序修改 Cursor 的`storage.json`配置文件，位于：

- Windows: `%APPDATA%\Cursor\User\globalStorage\`
- macOS: `~/Library/Application Support/Cursor/User/globalStorage/`
- Linux: `~/.config/Cursor/User/globalStorage/`
</details>

<details>
<summary><b>修改字段</b></summary>

工具会生成新的唯一标识符：

- `telemetry.machineId`
- `telemetry.macMachineId`
- `telemetry.devDeviceId`
- `telemetry.sqmId`
</details>

<details>
<summary><b>手动禁用自动更新</b></summary>

Windows 用户可以手动禁用自动更新功能：

1. 关闭所有 Cursor 进程
2. 删除目录：`C:\Users\用户名\AppData\Local\cursor-updater`
3. 创建同名文件：`cursor-updater`（不带扩展名）

Linux用户可以尝试在系统中找到类似的`cursor-updater`目录进行相同操作。

MacOS用户按照以下步骤操作：

```bash
# 注意：经测试，此方法仅适用于0.45.11及以下版本，不支持0.46.*版本
# 关闭所有 Cursor 进程
pkill -f "Cursor"

# 备份app-update.yml并创建空的只读文件代替原文件
cd /Applications/Cursor.app/Contents/Resources
mv app-update.yml app-update.yml.bak
touch app-update.yml
chmod 444 app-update.yml

# 打开Cursor设置，将更新模式设置为"无"，该步骤必须执行，否则Cursor依然会自动检查更新
# 步骤：Settings -> Application -> Update, 将Mode设置为none

# 注意: cursor-updater修改方法可能已失效。但为了以防万一，还是删除更新目录并创建阻止文件
rm -rf ~/Library/Application\ Support/Caches/cursor-updater
touch ~/Library/Application\ Support/Caches/cursor-updater
```
</details>

<details>
<summary><b>安全特性</b></summary>

- ✅ 安全的进程终止
- ✅ 原子文件操作
- ✅ 错误处理和恢复
</details>

<details>
<summary><b>重置 Cursor 免费试用</b></summary>

### 使用 `cursor_free_trial_reset.sh` 脚本

#### macOS

```bash
curl -fsSL https://raw.githubusercontent.com/yuaotian/go-cursor-help/refs/heads/master/scripts/run/cursor_free_trial_reset.sh -o ./cursor_free_trial_reset.sh && sudo bash ./cursor_free_trial_reset.sh && rm ./cursor_free_trial_reset.sh
```

#### Linux

```bash
curl -fsSL https://raw.githubusercontent.com/yuaotian/go-cursor-help/refs/heads/master/scripts/run/cursor_free_trial_reset.sh | sudo bash
```

#### Windows

```powershell
irm https://raw.githubusercontent.com/yuaotian/go-cursor-help/refs/heads/master/scripts/run/cursor_free_trial_reset.sh | iex
```

</details>


### 📚 推荐阅读

- [Cursor 异常问题收集和解决方案](https://mp.weixin.qq.com/s/pnJrH7Ifx4WZvseeP1fcEA)
- [AI 通用开发助手提示词指南](https://mp.weixin.qq.com/s/PRPz-qVkFJSgkuEKkTdzwg)

---



## 📄 许可证

<details>
<summary><b>MIT 许可证</b></summary>

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

</details>