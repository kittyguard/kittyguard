# KittyGuard / DG 桌面安全卫士

纯用户态杀毒软件（Python + C++ 双引擎）官方站点与更新分发仓库。

## 官网

GitHub Pages：https://kittyguard.github.io/kittyguard/

## 最新版本

- 当前版：6.4.0（自启动监控增强 · 扫描 IO 节流补齐 · ClamAV 双库龄）
- 安装包：https://github.com/kittyguard/kittyguard/releases/latest/download/DG-Security_6.4.0.zip
- 源码包：https://github.com/kittyguard/kittyguard/releases/latest/download/DG-Source_6.4.0.zip

## 检查更新

DG 安全内置「检查更新」填此目录即可自动查询最新版本：
https://kittyguard.github.io/kittyguard/version.json

## 免责声明

本软件仅作为技术实验与学习用途，不可将其用于主力杀毒软件；
用户态防护能力弱于内核态（Ring 0）方案，不可用于替代主流杀毒软件。
使用本软件产生的任何后果由使用者自行承担。

## 技术路线

- 纯用户态、零内核驱动、不服务化
- ClamAV 900 万签名 + YARA 规则 + 黑名单哈希 + PE 启发式 + 本地 ML + AI 辅助分析
- 统一裁决层风险评分（0-100）
- 实时防护（文件监控 / EMA 进程监控 / 自启动监控 / 勒索文档守护）
- 洪流冲刷五段流水线、行为链时间线、规则中心、防护中心
