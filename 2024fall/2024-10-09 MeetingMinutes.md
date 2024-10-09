# 2024-10-09 HZCU-HPCT 第三次例会
## Agenda
- 大一 presentation Asst1, Asst2
- 大一 Asst3
- 大二 PRA24 + 许诺
- 大二 presentation  cmu 15.418 asst1
- 大三 LLM inference

## 大一

谢许诺 盛亚楠 presentation asst1 asst2

下周 presentation asst3

### Asst 1

配置一个本机能够跑C语言程序的 vscode 环境

IDE 选择 vscode extensions.

### Asst 2

注册一个github账户并登录。

使用 vscode ssh remote extension 连接 HPCT_Server IP: 10.61.190.8，具体的账号密码会私发给各位。


### Asst 3 (extra)

完成1BRC挑战

1BRC: [HZCU-HPCT/24fall_1brc: The One Billion Row Challenge using C++ (github.com)](https://github.com/HZCU-HPC-Team/24fall_1brc)

使用上面所提到的若干内容，理解挑战内容，并进行代码优化。

## 大二 CMU 15.418 

### PRA24

赛题进展，以及下一步推进

[1. Slurm简介 — Slurm资源管理与作业调度系统安装配置 2021-12 文档 (ustc.edu.cn)](http://hmli.ustc.edu.cn/doc/linux/slurm-install/slurm-install.html)

Basic Api: [3.2 HIP核函数 · DCU 开发与使用文档 (hpccube.com)](https://developer.hpccube.com/gitbook//dcu_developer/DeveloperGuide/dcu_programming/DCU_programming_chapter3_2.html)

Profiling [3.7 HIP 性能分析 · DCU 开发与使用文档 (hpccube.com)](https://developer.hpccube.com/gitbook//dcu_developer/DeveloperGuide/dcu_programming/DCU_programming_chapter3_7.html#372-hiptx-trace%E5%8A%9F%E8%83%BD)

Example: [3.10 DCU程序优化方法 · DCU 开发与使用文档 (hpccube.com)](https://developer.hpccube.com/gitbook//dcu_developer/DeveloperGuide/dcu_programming/DCU_programming_chapter3_10.html)


pra 赛题分工：

Prefetch: Nuo Xu

访存优化: Zhuhan Bao

算法类优化修改: Zhen Cai

硬件资源dcu 了解: Jiawei Lin

### 科研汇报时间  Wed 10 AM

1. 大致浏览 ZJU ARCLAB 发表的相关论文。
2. 至少选择一篇比较感兴趣的文献并进行精读, 精读前私发给我具体文章。

### Asst 1

Website: [15-418/15-618: Parallel Computer Architecture and Programming, Fall 2024 (cmu.edu)](https://www.cs.cmu.edu/afs/cs/academic/class/15418-f24/www/)

代码仓库: [cmu15418f24/asst1 (github.com)]([HZCU-HPC-Team/24fall_15418 (github.com)](https://github.com/HZCU-HPC-Team/24fall_15418))

两周时间完成

## 大三 AI Inference ASC 25 Preliminary

Base Model: Qwen 2.5 7B [Qwen2.5: 基础模型大派对！ | Qwen (qwenlm.github.io)](https://qwenlm.github.io/zh/blog/qwen2.5/#:~:text=Qwen2.5%20%E6%A8%A1%E5%9E%8B) 

AI Framework: Hugging Face Transformer | vLLM 后端推理加速框架

Qwen2 technical report[Qwen2 technical report](https://arxiv.org/pdf/2407.10671)

Efficient Large Language Model: A Survey: [2312.03863 (arxiv.org)](https://arxiv.org/pdf/2312.03863)

### Report

两周后做技术报告解读 + 推理相关的内容报告

RQ1 Qwen2.5 训练过程中用到了什么加速技术: Nuo Xu

RQ2 vLLM 如何加速当前的LLM推理: Nuo Xu

RQ3 能否在vLLM 框架 用一些其他的加速技术: Chendong shen

RQ4 QWen 2.5 7B 跑起来+ 环境配置: Shenyi Wang 

RQ5 vLLM QWen benchmark infer speed. 你是怎么衡量速度的: Shenyi Wang

RQ6 Hugging Face Transformer 加速比是什么 用一些其他的加速技术 他们有什么其他的加速比:  Chendong Shen

## *下一次例会时间 2024 10 16 18:00 理四 508*
