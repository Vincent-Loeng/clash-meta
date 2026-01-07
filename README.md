**This repo may not be maintained anymore. The tool is enough to speed up some websites, e.g., OpenAI**

精力有限，可能不再维护，目前足以加速某些网站，比如 OpenAI

**Currently, only release versions are supported**

目前，仅更新 release 版

---

# mihomo for FreeBSD (with tun support)

![build workflow](https://github.com/Vincent-Loeng/mihomo/actions/workflows/run.yml/badge.svg)

Automatically build the latest version with patches

自动使用补丁构建最新的版本

## Other tools 其他工具

1. [**sing-box for FreeBSD/OpenBSD**](https://github.com/Vincent-Loeng/sing-box)
2. [**NaïveProxy for FreeBSD**](https://github.com/Vincent-Loeng/naiveproxy)

## Enhancements 增强功能

1. Tun interface Tun 网卡

2. Match process 匹配进程


## Examples 示例

Please refer to the given [template](template.yaml) 

请参考提供的[模板](template.yaml)


## Notes 注意事项

1. Please configure DNS servers manually when using automatic routing on OPNsense

   在 OPNsense 上使用自动路由时，请手动配置 DNS 服务器

2. Please allow packets to pass when using `system` stack on pfSense/OPNsense

   在 pfSense/OPNsense 上使用`system`栈时，请允许数据包通过'

3. The support for `riscv64` is experimental

   对`riscv64`支持仍处于实验阶段
