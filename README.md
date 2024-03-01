# proj312--Xvisor
# 基于飞腾派适配Xvisor并实现Linux＋RTOS双系统支持

## 项目描述

Xvisor是一款type-1的hypervisor的开源软件, 支持ARMv8-A架构，社区中有树莓派(ARM架构)运行Xvisor的参考。飞腾派开发板是飞腾公司针对教育行业推出的一款国产开源硬件平台，兼容 ARMv8-A 处理器架构，符合Xvisor的支持范围。

本项目要求参赛队伍深入理解Hypervisor和Guest OS的紧密交互，理解Hyperviso对硬件资源的模拟，在飞腾派开发板上适配Xvisor，在guest OS中运行Linux系统和RTOS系统， 至少两个系统串口可以访问。

## 预期目标

1. 完成Xvisor移植到飞腾派开发板。
2. 在guest OS中运行Linux系统和RTOS系统， 至少两个系统串口可以访问

## 特征

- 熟悉Xvisor代码和文档
- 深入理解Hypervisor和Guest OS的交互，在guest OS中运行Linux系统和RTOS系统， 至少实现两个系统串口可以访问。
- 适配硬件
	- 飞腾派开发板

## 已有参考资料

- xvisor官方资料
	- https://xhypervisor.org/
	- https://github.com/xvisor/xvisor
	- https://github.com/xvisor/xvisor/blob/master/docs/arm/bcm2838-raspi4.txt
- 飞腾开源项目资料
	- https://gitee.com/phytium_embedded/phytium-linux-kernel
	- https://gitee.com/phytium_embedded/phytium-free-rtos-sdk
	- https://gitee.com/phytium_embedded/phytium-embedded-docs
	- https://gitee.com/phytium_embedded/phytium-pi-os/wikis/%E9%9D%9E%E9%A3%9E%E8%85%BE%E6%B4%BEOS%E7%9A%84SD%E5%8D%A1%E9%95%9C%E5%83%8F%E5%88%B6%E4%BD%9C
- 飞腾派开发资料
	- [操作系统大赛飞腾赛道交流社区](https://edu.phytium.com.cn/group/10)
	- [飞腾派开发板电子发烧友社区](https://bbs.elecfans.com/group_1708)
	-  [赛题资料汇总](https://edu.phytium.com.cn/group/10/thread/21579)
## 赛题分类
虚拟化

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

高等

## License

- GNU General Public License Version 2

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

**赛事支持导师**
- 姓名：郭丁丁
- 单位：飞腾信息技术有限公司
- email：[guodingding1657@phytium.com.cn](mailto:guodingding1657@phytium.com.cn)

**飞腾技术支持导师**
- 姓名：朱鸿雷
- 单位：飞腾信息技术有限公司
- email：[zhuhonglei1714@phytium.com.cn](mailto:zhuhonglei1714@phytium.com.cn)

**飞腾派支持导师**
- 姓名：连宇飞
- 单位：飞腾信息技术有限公司
- email：[lianyufei@phytium.com.cn](mailto:lianyufei@phytium.com.cn)
