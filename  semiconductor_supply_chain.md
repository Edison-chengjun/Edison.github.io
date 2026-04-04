# 半导体核心封装工艺关键供应商图谱

> 整理时间：2026-04-01
> 覆盖工艺：RDL · Bumping · TSV

---

## 一、TSV（硅通孔）— 3D IC 封装

TSV 是实现 3D 堆叠封装的核心工艺，设备链最长、技术壁垒最高。

### 工艺流程与关键供应商

| 工艺步骤 | 主要设备 | 关键供应商 |
|---------|---------|-----------|
| **深硅刻蚀（Deep Si Etch）** | DRIE 刻蚀机 | SPTS（KLA旗下）、 Plasma-Therm、 Oxford Instruments |
| **介电层沉积（SiO₂/SiN）** | PECVD / ALD | Applied Materials、 Lam Research、 Tokyo Electron（TEL） |
| **阻挡层/种子层沉积（Barrier/Seed）** | PVD / ALD | Applied Materials、 Lam Research、 Evatec |
| **电镀铜（Cu Electroplating）** | 电镀设备 | Applied Materials、 Lam Research、 Novellus（KLA） |
| **化学机械抛光（CMP）** | CMP 设备 | Applied Materials、 Ebara、 Revasum |
| **晶圆减薄（Wafer Thinning）** | 减薄机 | Disco、 GKG、 AM Technology |
| **临时键合/解键合** | 键合设备 | Brewer Science、 3M、 EV Group |
| **填孔（Via Fill）** | CVD/电镀 | 参见阻挡层/种子层、电镀环节 |
| **检测/量测** | X-ray、 SAM、 SEM | Nordson DAGE、GE、 Hitachi High-Tech |

### 关键材料供应商

| 材料 | 供应商 |
|-----|-------|
| 临时载片胶（Temporary Bonding Adhesive） | Brewer Science、 3M、 EV Group |
| 电镀液（Plating Chemistry） | MacDermid Enthone、 Uyemura、 MKE |
| 介电材料（Dielectrics） | Fujifilm、 JSR、 Shin-Etsu Chemical |
| 阻挡层材料（Ta/TaN/Ti/TiN） | 参见PVD设备商（设备+材料一体化）|

### 市场格局要点
- **刻蚀设备**：SPTS 占据 DRAM/3D NAND TSV 主导，Lam在先进封装崛起
- **电镀**：Applied Materials 在先进TSV市场最强，Novellus铜填充技术领先
- **减薄**：Disco 在晶圆切割/减薄市场占统治地位
- **完整解决方案**：EV Group 提供从临时键合到解键合的整线方案

---

## 二、Bumping（凸点）— 倒装芯片封装

Bumping 是 FC-BGA、FC-CSP 等先进封装的基础，在成熟制程应用最广。

### 工艺流程与关键供应商

| 工艺步骤 | 主要设备/材料 | 关键供应商 |
|---------|--------------|-----------|
| **UBM 沉积（Under Bump Metallization）** | PVD 设备 | Applied Materials、 ULVAC、 Canon Anelva |
| **光刻/显影** | 涂胶/显影设备 | SCREEN Holdings、 TEL、 Rudolph |
| **焊料沉积（SnPb / SAC / Lead-free）** | 蒸镀/电镀/植球 | 设备：AKM、 Ulvac、 Mattson；材料：Senju、 Alpha Assembly、 Indium Corporation |
| **回流焊（Reflow）** | 回流炉 | BTU International（Amtech）、 Vitronics Soltec、 Heller Industries |
| **底部填充（Underfill）** | 点胶设备 + 材料 | 设备：ASM Pacific、 Kulicke & Soffa；材料：Namics、 Shin-Etsu、 Hysol（MacDermid） |
| **清洗** | 清洗设备 | SCREEN Holdings、 TEL、 Lam |

### 焊料合金主要供应商
- **SnAgCu（SAC）系列**：Senju Metal、 Alpha Assembly、 Nihon Superior
- **高铅焊料**：Indium Corporation、 Alpha Assembly
- **低温焊料（SnBi系）**：Alcan Bond、 Shenzhen Yian Technology

### 市场格局要点
- Bumping 相对成熟，设备商以日美为主
- 植球（Ball Attach）环节 Kulicke & Soffa 全球领先
- 先进封装趋势：无铅化、细间距（Fine Pitch）、铜柱（Copper Pillar）

---

## 三、RDL（再布线层）— 先进封装核心

RDL 是扇出型封装（FOWLP/FOPLP）和 2.5D/3D 封装的核心工艺，连接芯片与基板。

### 工艺流程与关键供应商

| 工艺步骤 | 主要设备/材料 | 关键供应商 |
|---------|--------------|-----------|
| **介电层沉积（Dielectric）** | PECVD / 旋涂 | Applied Materials、 TOK（Tokyo Ohka Kogyo）、 Taiyo Yuden |
| **金属层沉积（Metallization）** | PVD / 电镀 | Applied Materials、 泛林（Lam）、 SPTS |
| **光刻/显影** | 涂胶/曝光/显影 | SCREEN Holdings、 Canon、 Rudolph |
| **蚀刻（Etch）** | 干法刻蚀 | SPTS、 Lam Research、 Plasma-Therm |
| **化学机械抛光（CMP）** | CMP 设备 | Applied Materials、 Ebara |
| **重建封装（RDL Formatting）** | 载板、塑封 | 长电科技（JCET）、 通富微电（TFME）、 华天科技（HUADA）|

### 关键材料供应商

| 材料 | 供应商 |
|-----|-------|
| 聚酰亚胺（PI）/ 聚酰胺（PA）光敏树脂 | Hitachi Chemical、 Taiyo Yuden、 长春集团 |
| 环氧塑封料（EMC） | Chang-Chun（长春）、 Sumitomo Bakelite、 Hitachi Chemical |
| 感光介质（Photosensitive Dielectric） | TOK、 JSR、 Fujifilm |
| 电镀液 | MacDermid Enthone、 Uyemura、 BASF |

### 市场格局要点
- RDL 是 FOWLP 的核心，扇出封装厂商（台积电InFO、日月光FOCoS）自制 RDL
- 材料端：Ajinomoto 强力增长（build-up film），日韩美厂商主导
- 2.5D 封装（CoWoS、Intel EMIB）RDL精度要求极高，设备壁垒显著提升

---

## 四、跨工艺关键综合供应商

以下厂商同时覆盖多种封装工艺：

| 公司 | 业务覆盖 |
|-----|---------|
| **Applied Materials** | PVD、CVD、CMP、刻蚀、的电镀 — TSV+RDL+Bumping |
| **Lam Research（泛林）** | 刻蚀、沉积、电镀 — TSV+RDL |
| **KLA** | SPTS（刻蚀）、KLA（检测）— TSV+RDL |
| **SCREEN Holdings** | 清洗、涂胶显影 — Bumping+RDL |
| **Tokyo Electron（TEL）** | 涂胶显影、沉积、刻蚀 — TSV+RDL |
| **Disco** | 切割、减薄 — TSV+Bumping |
| **Kulicke & Soffa** | 植球、倒装 — Bumping |
| **ASM Pacific** | 封装设备全线 — Bumping+测试 |

---

## 五、"存储墙" 与 CMC 存算合封 — Interposer / High-end Substrate 需求暴增

### 背景逻辑

**"存储墙"问题**：存储带宽远落后于算力需求，HBM（High Bandwidth Memory）与 Logic 之间的互联瓶颈倒逼 2.5D/3D 堆叠方案加速落地。

**CMC（Compute-Memory Complex）存算合封**：将 Memory 与 Compute 在同一封装内近距离互联，是打破存储墙的核心路径，典型代表为 HBM+Logic 的 2.5D 方案（CoWoS、Intel Foveros）。

### 直接受益环节

| 环节 | 受益逻辑 | 稀缺供应商 |
|-----|---------|-----------|
| **Silicon Interposer（硅转接板）** | 2.5D 封装核心，HBM 与 Logic 高密度互连 | Foundry 自产（台积电 CoWoS）、英特尔的 EMIB（三维异构集成）|
| **Glass Interposer（玻璃转接板）** | 低损耗、低 CTE，可大尺寸化 | Schott（德国）、Corning（美国）、LPKF（激光加工）|
| **High-end Substrate（高阶封装基板）** | 超高层数、超细线宽 ABF 基板 | 揖斐电（Ibiden）、新光电气（Shinko）、三星电机（SEMCO）、欣兴电子（Unimicron）|
| **Interposer 加工设备** | 2.5X nm 级曝光机、矽穿孔加工 | 参见本文 TSV/RDL 章节 |
| **嵌入式多层电容（eMLCC/嵌入式被动）** | 电源完整性，靠近 Die 放置 | 三星电机（SEMCO）、村田（Murata）、Taiyo Yuden |

### High-end Substrate 供应商产能现状（2026年）

| 供应商 | 核心能力 | 产能稀缺性 |
|-------|---------|-----------|
| **Ibiden（揖斐电）** | FC-BGA 全球第一，AI 芯片基板主力 | 极度紧张，优先供货英伟达/AMD |
| **Shinko（新光电气）** | 日本品质，FC-BGA + 散热方案 | 产能有限 |
| **SEMCO（三星电机）** | 三星内部供应为主，AI 基板外供受限 | 内部优先 |
| **Unimicron（欣兴）** | ABF 载板快速扩产，台系 AI 芯片主要配套 | 扩产中，2026-2027 逐步释放 |
| **Kinsus（景硕）** | ABF 载板，日月光体系主力供应商 | 跟随日月光扩产 |
| **Nanya PCB（南亚 PCB）** | 成熟制程 ABF，AI 相关在爬坡 | 量产初期 |

> ⚠️ **战略提示**：ABF 载板从产能建设到大规模量产需 3-5 年，当前 AI 芯片需求激增已导致 2025-2027 年产能持续紧绷。台系载板厂（欣兴、景硕、南亚）扩产节奏需密切跟踪。

---

## 六、2.5D/3D 堆叠的 CTE 匹配与可靠性实验室考察

### CTE 热膨胀系数 — 核心挑战

2.5D/3D 堆叠涉及多种材料（Si、Glass、Organic substrate、Ceramic、Copper pillar、Underfill）的热膨胀系数精确匹配：

| 材料 | CTE (ppm/°C) |
|-----|-------------|
| 硅（Si） | ~2.6 |
| 铜（Cu） | ~17 |
| 陶瓷（Ceramic） | ~6-9 |
| 玻璃（Glass） | ~3-8（依类型） |
| 有机基板（Organic Substrate） | ~15-25 |
| 环氧塑封料（EMC） | ~10-15 |
| 底部填充胶（Underfill） | ~25-45 |
| 焊料（SnAgCu） | ~20-25 |

**CTE 失配 → 热机械应力 → 界面分层 / 焊点开裂 / TSV 损伤**

### RDL/Interposer/Substrate 层的热应力设计

- 界面层材料 CTE 梯度设计（渐变层 vs 突变层）
- Underfill 弹性模量与 CTE 的平衡（应力缓冲 vs 固化后硬度）
- 热循环测试（Thermal Cycle Test, TCT）标准：-55°C~125°C，商规；-40°C~125°C，车规
- 可靠性测试的加速老化模型：Arrhenius 方程 / Coffin-Manson 模型

### Reliability Lab 考察维度（供应商审核要点）

寻源供应商时，以下实验室能力是必考项：

| 考察维度 | 具体内容 | 参考标准/设备 |
|---------|---------|-------------|
| **热循环测试（TCT）** | 评估材料/界面在反复温度变化下的可靠性 | JEDEC JESD22-A104、IPC-9701 |
| **HAST / PCT** | 高加速温湿度测试，检验湿敏可靠性 | JEDEC JESD22-A110 / A118 |
| **功率循环（Power Cycling）** | 模拟实际工作条件的开关机应力 | 专用功率循环设备 |
| **SEM / CSAM 失效分析** | TSV/焊点/界面缺陷的无损检测 | Nordson DAGE、Sonix、Hitachi |
| **DPA（破坏性物理分析）** | 截面分析、脱层检测 | 精雕机 + SEM |
| **X-ray / CT-Scan** | 内部结构 3D 重构 | 3D X-ray CT（Zeiss、Bruker）|
| **热机械仿真（FEA）** | 设计阶段预测 CTE 失配风险 | Ansys、ABAQUS |
| **WLP / FOWLP 专用测试** | 晶圆级封装的可靠性评估 | 特定于 WLP 的测试夹具 |
| **车规（AEC-Q100/Q101）** | 汽车电子的可靠性认证体系 | AEC 标准全套 |
| **失效分析能力** | 失效定位→根因分析→改善闭环 | EMMI、OBIRCH、Delvotec |

### 可靠性强的头部供应商特征

- 拥有 **内部 Reliability Lab**（不依赖第三方送检）
- 可提供 **加速模型数据**（Acceleration Factor Report）
- 具备 **客户定制化可靠性方案**（而非仅执行标准测试）
- 有 **AI / HBM / 先进封装** 领域的已量产记录
- 通过 **ISO 17025** 实验室认证

---

## 七、备注

- 本图谱聚焦 **前道后端（Front-end Packaging）** 的关键供应商，略去基板（Substrate）、封装测试（OSAT）等环节
- 部分厂商兼营设备+材料，分类以其核心设备业务为准
- 供应商名录随技术迭代持续变化，仅供参考
- 新增第五章、第六章为 2026-04-01 最新补充

---

*整理：拉克 ✨ | 最后更新：2026-04-01*
