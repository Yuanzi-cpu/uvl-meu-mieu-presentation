---
theme: seriph
background: https://images.unsplash.com/photo-1450101499163-c8848c66ca85?auto=format&fit=crop&q=80
class: text-center
highlighter: shiki
lineNumbers: true
info: |
  ## 出口管制清单深度解析
  基于 EAR 第 744 部分：UVL, MEU & MIEU
drawings:
  persist: false
transition: slide-left
title: UVL, MEU & MIEU 核心合规要点解析
---

# UVL, MEU & MIEU 核心合规要点解析
### 最终用途与最终用户管制实务指南

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white/10">
    点击进入深度解析 <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: two-cols
---

# 1. 未经核实清单 (UVL)
**Unverified List**

- <v-click>**定义**：因非归咎于美国政府原因，导致 BIS 无法核实交易真实性的非美国实体。</v-click>
- <v-click>**合规要点**：
  - 依据 **§ 740.2(a)(17)**，禁止适用许可证例外。
  - 依据 **§ 744.15(b)**，必须取得并留存书面 **UVL 声明**。
  - 依据 **§ 758.1(b)(8)**，所有受管辖实物出口均须申报 **AES/EEI**。</v-click>

::right::

<div class="ml-8 mt-10 p-5 bg-blue-50 dark:bg-gray-800 rounded-lg shadow">
  <h3 class="text-blue-600">📋 UVL 声明核心</h3>
  <p class="text-xs">
    1. 实体完整信息与签署人授权<br>
    2. 最终用途/用户/目的地承诺<br>
    3. 配合 BIS 五年内随时的核查承诺
  </p>
</div>

---
layout: default
---

# 2. 军事最终用户 (MEU)
**Military End-User**


- <v-click>**核心性质**：非穷尽列举。清单仅公示已识别主体，未列名不代表豁免。</v-click>
- <v-click>**管控逻辑**：
  - 针对中、缅、柬、尼、委 5 国。境内实体需进行“定义核实”，境外实体以清单为准。</v-click>
- <v-click>**定义范围**：
  - 国家武装部队、警察、情报或侦察机构（符合 § 744.22(f)(2) 除外）。
  - 任何旨在支持“军事最终用途”的个人或实体。</v-click>

---
layout: two-cols
---

# 3. 军事情报最终用户 (MIEU)
**Military Intelligence End-User**

- <v-click>**关联法条**：**§ 744.22**。</v-click>
- <v-click>**适用范围**：白俄、缅、柬、中、俄、委及 E1/E2 类国家。</v-click>
- <v-click>**管控力度**：
  - **物项范围**：所有受 EAR 管辖物项。
  - **审核政策**：推定拒绝。
  - **许可例外**：极度受限，仅允许 **§ 740.11(b)(2)(ii)**。</v-click>

::right::

<div class="ml-8 mt-12 p-4 border-l-4 border-red-500 bg-red-50 dark:bg-red-900/20">
  <h3 class="text-red-600 font-bold">⚠️ 关键差异</h3>
  <p class="text-sm">
    相比 MEU 仅限制附件 2 物项，MIEU 对所有受 EAR 管辖物项实施全维度管控。目前中国仅列明<b>中央军委联合参谋部情报局</b>。
  </p>
</div>

---
layout: center
---

# 4. 核心维度对比总结


| 维度 | UVL | MEU | MIEU |
| :--- | :--- | :--- | :--- |
| **主要法条** | § 744.15 | § 744.21 | § 744.22 |
| **物项范围** | 所有受 EAR 管辖物项 | 附件 2 (如 3A991, 5A992) | 所有受 EAR 管辖物项 |
| **许可例外** | 全面禁止使用例外 | 仅限 GOV (b)(2)(i)&(ii) | 仅限 GOV (b)(2)(ii) |
| **移除/修改** | PLC/PSV 最终用途核查 | ERC 委员会一致表决通过 | 提交申请至 ERC 审议 |

---
layout: center
class: text-center
---

# 演示结束 · 感谢查阅
**合规是业务持续发展的基石**

<div class="mt-8">
  <a href="obsidian://open?vault=Tecent%20Export%20Control" class="text-blue-500 underline">返回 Obsidian 知识库</a>
</div>
