# BIOS

BIOS 用于完成平台初始化、启动设备识别、系统引导以及部分底层硬件配置。不同开发平台的 BIOS 固件、刷写方式和注意事项可能存在差异，实际操作前请确认设备型号、固件版本和目标系统类型。

!!! warning "注意"
    BIOS 刷写属于高风险操作，刷写错误可能导致设备无法启动。请严格按照对应开发平台的官方文档执行，并确认固件来源、设备型号和刷写步骤匹配。

## 适用范围

本章节用于汇总 CIX P1 相关开发平台的 BIOS / 固件刷写入口。

当前涉及平台包括：

- 瑞莎 Orion O6
- 美高铭凡 MS-R1
- 香橙派 OrangePi 6 Plus
- 贝启平台

## 刷写说明

不同平台的 BIOS 刷写流程不完全相同，常见流程通常包括：

1. 下载对应平台和型号的 BIOS 固件。
2. 准备刷写介质或刷写工具。
3. 按官方文档进入 BIOS 刷写流程。
4. 等待刷写完成，期间不要断电。
5. 重启设备并确认 BIOS 版本。

具体刷写步骤请以对应平台官方文档为准。

## 官方资料入口

### 瑞莎 Orion O6

- [瑞莎 Orion O6 平台入口](../开发平台/瑞莎.md)
- [Radxa Orion O6 官方产品页面](https://radxa.com/products/orion/o6/)
- [Radxa Orion O6 下载资源页面](https://docs.radxa.com/en/orion/download)

### 美高铭凡 MS-R1

- [美高铭凡 MS-R1 平台入口](../开发平台/美高.md)
- [MINISFORUM MS-R1 官方资料页面](https://www.minisforum.com/zh/pages/product-info)

### 香橙派 OrangePi 6 Plus

- [香橙派 OrangePi 6 Plus 平台入口](../开发平台/香橙派.md)
- [OrangePi 6 Plus 官方产品页面](http://www.orangepi.cn/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-6-Plus.html)
- [OrangePi 6 Plus 官方资源页面](https://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/service-and-support/Orange-Pi-6-Plus.html)

### 贝启平台

- [贝启平台入口](../开发平台/贝启.md)
