<div align="center">

# 🧬 肠动心弦 · 宏基因组工具学习库

**逐个工具学透：工具信息 · 工具概述 · 算法实现 · VibeCoding 实战提示词**

[![Papers](https://img.shields.io/badge/Papers-10-blue?style=flat-square)](https://github.com/Jxuanrui/gut-microbiome-toolkit/tree/main/tutorials)
[![Tools](https://img.shields.io/badge/Tools-8-green?style=flat-square)](https://github.com/Jxuanrui/gut-microbiome-toolkit/tree/main/tutorials)
[![Stars](https://img.shields.io/github/stars/Jxuanrui/gut-microbiome-toolkit?style=flat-square&color=yellow)](https://github.com/Jxuanrui/gut-microbiome-toolkit/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/Jxuanrui/gut-microbiome-toolkit?style=flat-square&color=9CA3AF)](https://github.com/Jxuanrui/gut-microbiome-toolkit/commits/main)
![WeChat](https://img.shields.io/badge/WeChat-%E8%82%A0%E5%8A%A8%E5%BF%83%E5%BC%A6-07C160?style=flat-square&logo=wechat&logoColor=white)

*由微信公众号「肠动心弦」出品 · 持续更新*

</div>

---

## 📚 工具清单 · 按文献维度梳理

| 文献 | 通俗的描述 | 教程 |
|:---|:---|:---:|
| **Deng Z-L, et al.** *Cell* 2026 | 跨域物种注释工具 **Metax**：用全基因组覆盖度统计识破注释里的"假信号"（肿瘤测序污染、试剂 DNA、参考库污染） | [metax.md](tutorials/cell-2026-metax/metax.md) |
| **Fang L, et al.** *Bioinformatics* 2026 | 菌群大队列 × 代谢组小队列"拼接"，推断菌→代谢物→疾病通路的 R 包 **predmetab** | [predmetab.md](tutorials/bioinformatics-2026-predmetab/predmetab.md) |
| **Jundzill M, et al.** *Genome Biol* 2026 | 四款原核注释工具（Prokka / Bakta / EggNOG-mapper / PGAP）156,033 个基因组大评测：没有全能冠军，只有分场景称王 | [benchmark.md](tutorials/genome-biol-2026-annotation-benchmark/benchmark.md) |
| **Naranjani B, et al.** *Gut Microbes* 2026 | **BiotaPredictor**：输入分子结构，预测药物被肠道菌群"耗竭"的风险（含真实环境实测记录） | [biotapredictor.md](tutorials/gutmicrobes-2026-biotapredictor/biotapredictor.md) |
| **Zelik L, et al.** *Nat Microbiol* 2026 | 抗生素"经菌群 vs 直接作用"拆解：解耦工具 **CompoRes** + 论文全套分析代码复现（含双仓库真实环境实测） | [composres.md](tutorials/natmicrobiol-2026-antibiotics/composres.md) · [reproduction.md](tutorials/natmicrobiol-2026-antibiotics/reproduction.md) |
| **Chen C, et al.** *Nat Med* 2026 | 激素治疗改写菌群：主要不在肠道——356 人精准 MHT 框架（含流水线复现路径与模拟数据实测） | [reproduction.md](tutorials/natmed-2026-mht/reproduction.md) |
| **Wirbel J, et al.** *Nat Med* 2026 | 移植菌群首支随机 3 期试验：植入时多样性不影响生存、基线才预测，PTCy 方案抑制菌群更猛（MIT 代码 + CC BY 数据，复现路径含元数据申请指引） | [reproduction.md](tutorials/natmed-2026-bmtctn1801/reproduction.md) |
| **Nagata N, et al.** *Nat Med* 2026 | 生活方式与健康的菌群桥梁——6,803 人队列的两条对立介导轴（复现路径指引式：元数据受伦理限制，含申请通道与文件名对照要点） | [reproduction.md](tutorials/natmed-2026-lifestyle-axes/reproduction.md) |
| **Brown CL, et al.** *Nat Commun* 2026 | 污水里的耐药信号：肠杆菌同步、假单胞菌滞后 1–3 个月（demo 合成数据本站实测跑通 + 真实管线缺口说明） | [reproduction.md](tutorials/natcomm-2026-wbs-resistance/reproduction.md) |
| **Han J, et al.** *Nat Commun* 2026 | 法医菌群时钟 mHolmes：Transformer 迁移学习把死亡时间推断误差缩到 2 天内（`mhm` CLI 七模式复现路径 + 钉版环境要点） | [reproduction.md](tutorials/natcomm-2026-mholmes/reproduction.md) |

## 📖 每篇教程的读法

五段式结构，从"这仓库靠谱吗"一路读到"怎么用 AI 跑起来"：

| 段落 | 你会看到什么 |
|:---|:---|
| 🔍 仓库评估 | 纳入前对官方代码库的实地核验：完整度 / 可执行性 / 维护 / 许可评分卡 |
| ℹ️ 工具信息 | 源码、论文、输入输出、资源需求（内存 / 数据库体积 / CPU）速查表 |
| 🎯 工具概述 | 解决什么问题、什么场景选它、在同类工具中的位置 |
| ⚙️ 算法实现 | 方法原理与关键数字，口径与论文一致，配原文图表 |
| 🤖 VibeCoding 提示词 | 安装 → 建库 → 运行 → 解读的分块提示词，每步附"怎么确认 AI 做对了"的校验点 |

---

<div align="center">

### 💬 关注公众号

**微信搜索「肠动心弦」**

微生物组 × 临床医学科研解读持续更新，每篇工具解读均首发于公众号

⭐ 如果这个仓库对你有帮助，欢迎 Star 支持一下

</div>
