# Coogle

让国行版ColorOS更加Google，仅适配ColorOS17。

## 功能

- **Hey Google**：补全国行系统的 Google 语音唤醒支持。
- **Google 智能镜头**：补全Google智能镜头功能入口。
- **系统导航方式**：补全设置中的导航选项，支持圈定即搜和左/右下角向内滑动呼出数字助理。
- **Google 搜索框**：启用桌面底部 Google 搜索框。
- **移除 GMS 对国行的使用限制**。
- **设置底部显示 Google服务**。

## Coogle 附属模块

整合 Google 系统应用固化、Hotword 注册组件和 DSP 唤醒支持。

开启 Hey Google 时自动检查附属模块。

## 使用说明

1. 安装 `Coogle-1.0.apk`，在 LSPosed 中启用模块并勾选推荐作用域。
2. 使用 Hey Google 需安装 `Coogle-Companion-1.0.zip`，通过 KernelSU 安装后重启设备。
3. 在 Google 中开启 Hey Google，并完成 Voice Match。
4. 更改功能开关后重启对应作用域；涉及系统框架时需重启设备。

Google 智能镜头入口已在 Google App 17.65.17 上验证，其他版本的兼容情况以实际使用为准。Hey Google 和 DSP 支持取决于设备音频实现及 Google 服务状态。

## 致谢

部分代码参考 [ONextBox](https://github.com/MiToverG422/ONextBox) 和 [LuckyTool](https://github.com/luckyzyx/LuckyTool)。

UI 参考 [KernelSU](https://github.com/tiann/KernelSU) 和 [LSPosed](https://github.com/LSPosed/LSPosed)。

感谢以上项目的开发者与贡献者。

作者：**zopulus**\
开源协议：**GPL-3.0**
