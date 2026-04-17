**This repo may not be maintained anymore. The tool is enough to speed up some websites, e.g., OpenAI**

精力有限，可能不再维护，目前足以加速某些网站，比如 OpenAI

**Currently, only release versions are supported**

目前，仅更新 release 版

---

# clash-meta for FreeBSD (with tun support)

![build workflow](https://github.com/Vincent-Loeng/clash-meta/actions/workflows/run.yml/badge.svg)

This ***self-use repo*** automatically build the latest version with patches

此***自用仓库***自动使用补丁构建最新的版本

## Other tools 其他工具

1. [**bsd-box**](https://github.com/Vincent-Loeng/bsd-box)
2. [**NaiveProxy for FreeBSD/OpenBSD**](https://github.com/Vincent-Loeng/naiveproxy)

## Enhancements 增强功能

1. Tun interface Tun 网卡

2. Match process 匹配进程

3. Redirect (since `1.19.24-vincent`)

## Examples 示例

Please refer to the given [template](template.yaml) 

请参考提供的[模板](template.yaml)


## Notes 注意事项

1. Please configure DNS servers manually when using automatic routing on OPNsense

   在 OPNsense 上使用自动路由时，请手动配置 DNS 服务器

2. Please allow packets to pass when using `system` stack on pfSense/OPNsense

   在 pfSense/OPNsense 上使用`system`栈时，请允许数据包通过'

3. Please add port forwarding rules when using `redirect` (higher performance)

   使用 `redirect`（性能更好）时，请添加端口转发规则

4. The support for `riscv64` is experimental

   对`riscv64`支持仍处于实验阶段
