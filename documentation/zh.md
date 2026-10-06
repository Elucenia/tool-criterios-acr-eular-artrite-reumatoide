<!-- ELUCENIA technical documentation · criterios-acr-eular-artrite-reumatoide · zh · no clinical/professional/rights approval -->

# ACR/EULAR 2010 类风湿关节炎分类标准

[条件、来源与许可](https://elucenia.org/zh/tools/criterios-acr-eular-artrite-reumatoide)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 关节受累（肿胀或疼痛）

`artic`

- `0` — 1 个大关节
- `1` — 2 至 10 个大关节
- `2` — 1 至 3 个小关节（可伴或不伴大关节）
- `3` — 4 至 10 个小关节（可伴或不伴大关节）
- `5` — \> 10 个关节（至少 1 个小关节）

### 血清学（类风湿因子与 anti-CCP）

`soro`

- `0` — 两者均阴性
- `2` — 任一指标低滴度阳性（≤ 正常上限的 3×）
- `3` — 任一指标高滴度阳性（\> 正常上限的 3×）

### 急性期反应指标（CRP 与 ESR）

`fase`

- `0` — 两者均正常
- `1` — CRP 或 ESR 异常

### 症状持续时间

`duracao`

- `0` — \< 6 周
- `1` — ≥ 6 周

## 方法版本

ACR/EULAR 2010：4领域，总分0–10，阈值≥6；需符合情境和排除条件

## 已记录的公式

四个领域之和（最高10分）：关节0–5、血清学0–3、急性期反应物0–1、症状持续时间0–1。评分≥6=确定的类风湿关节炎。

大关节：肩、肘、髋、膝、踝。小关节：掌指、近端指间、第2–5跖趾、拇指指间及腕关节。

## 限制与适用人群

ACR/EULAR 2010分类要求在应用≥6/10阈值之前，确认至少一个关节存在滑膜炎，且没有能够更好解释该滑膜炎的其他诊断。该标准为新近出现的未分化炎症性滑膜炎情境而制定。缺少这些条件时，单独使用评分并不能重现分类标准。

## 参考文献

- [Aletaha D et al. 2010 Rheumatoid arthritis classification criteria: an American College of Rheumatology/European League Against Rheumatism collaborative initiative. Arthritis Rheum, 2010.](https://doi.org/10.1002/art.27584)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

归类为确诊类风湿关节炎（≥ 6 分）


### 2

归类为确诊类风湿关节炎（≥ 6 分）


### 3

不符合分类标准（< 6 分）

不排除类风湿关节炎：随时间重新评估。

