# ClearSweep

Windows 软件管理与卸载工具 · 深色玻璃界面 · 单文件免安装

## 下载

**[下载最新版 ClearSweep.exe](https://github.com/AirYang-1/ClearSweep/releases/latest/download/ClearSweep.exe)**

[全部版本与更新说明](https://github.com/AirYang-1/ClearSweep/releases) · [SHA-256 校验](https://github.com/AirYang-1/ClearSweep/releases/latest/download/SHA256SUMS.txt)

当前版本：**v2.0.6**，Windows 10/11 x64，约 46.6 MiB。

下载 EXE 后双击运行，无需安装 Python、Qt SDK，也不需要把源码放在旁边。首次打开会出现 Windows 管理员权限提示。
依赖 Windows 的 .NET Framework 4.8。单文件启动会先解包运行组件，随后显示软件清单。

## 功能

- 显示软件图标、版本、发布者、估算体积及安装/维护日期，支持搜索、分类和清单导出。
- 确认后启动软件自带的卸载器；卸载成功后询问是否查看关联残留。
- 残留逐项审阅、默认不勾选；文件移入回收站，孤立卸载登记单独确认并备份。
- 当前用户启动项可备份禁用和恢复，系统范围启动项仅供查看。
- 六套深色主题，可调整透明度、光效颜色、动效与紧凑列表；启动界面同步主题。

## 使用说明

1. 下载上方的 **ClearSweep.exe**，选择要管理的软件。
2. 点击“卸载软件”，确认目标与卸载命令，再完成原卸载器的步骤。
3. 出现残留提示后，先检查完整路径，再选择需要处理的项目。

文件可从 Windows 回收站恢复。注册表备份保存在 `%LocalAppData%\ClearSweep\Backups`；
启动项恢复数据保存在 `%LocalAppData%\ClearSweep\DisabledStartupV2`，请保留。

日期带 `*` 表示卸载登记更新时间参考，不等同于首次安装时间。
本版本不提供系统服务/计划任务清理、商店应用强制删除或无提示批量卸载。

## 校验下载

在 PowerShell 中运行：

```powershell
Get-FileHash .\ClearSweep.exe -Algorithm SHA256
```

将结果与同一 Release 的 `SHA256SUMS.txt` 对照。

## 关于此仓库

此公开仓库用于程序下载、更新说明和问题反馈。ClearSweep 应用源码保存在私有仓库，没有在此公开。
Qt/PySide6、Python 等第三方组件的许可继续适用，详见 [第三方声明](THIRD_PARTY_NOTICES.md) 和 Release 的 `ThirdPartyNotices.txt`。

程序由独立代码实现，不包含商业卸载器的代码或素材。
