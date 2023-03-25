# projX-la-SIMDe

## 项目名称

SIMDe项目的LoongArch向量指令支持

## 支持单位

龙芯中科技术股份有限公司

## 项目描述

基于开源SIMDe项目，实现x86向量指令SSE与AVX和ARM向量指令NEON到LoongArch向量指令的转换。具体工作内容包括：

1） 阅读分析SIMDe源代码，理解基本思路。
2） 在SIMDe项目中实现SSE/AVX/NEON向量指令到LoongArch向量指令的转换，进行测试和调优，生成相应文档。
3） 有余力可尝试继续实现MIPS中MSA向量指令到LoongArch向量指令的转换。

## 所属赛道

2023全国大学生操作系统比赛的“OS功能挑战”赛道

## 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2023全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师

* 殷时友
    - Email yinshiyou @ loongson.cn

## 难度

中

# License

GPL V3.0.

## 预期目标

* 开源simde项目的LoongArch向量支持。
* 鼓励完成上游提交、合并

## 参考资源

* [SIMDe源码](https://github.com/simd-everywhere/simde)
* [LoongArch docs](https://github.com/loongson/LoongArch-Documentation)。LoongArch相关文档，包括架构手册，ABI, 3A5000 CPU和7A1000桥片手册等。

## 备注

龙芯可免费提供龙芯开发资源。


