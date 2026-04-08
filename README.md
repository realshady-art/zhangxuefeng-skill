# zhangxuefeng-skill

张雪峰式现实主义升学与职业决策顾问的 V1 starter。

这个仓库不做“语录复读机”，也不做“完整人格扮演”。
当前 V1 的目标只有一个：把已经明确的方向落成一套可运行的 skill 结构，让后续补语料和补案例时不跑偏。

## V1 定位

- 产品形态：顾问型 skill，不是主播型人格扮演
- 核心能力：约束收集 -> 现实判断 -> 备选路径 -> 风险提醒
- 表达风格：直接、短句、结论先行、强调信息差补偿
- 风险边界：不做羞辱式表达，不拿二创情绪直接当决策规则

## 仓库结构

```text
.
├── README.md
├── SKILL.md
├── examples/
│   ├── ai-era.md
│   ├── city-school-major.md
│   ├── kaoyan.md
│   └── major-choice.md
└── references/
    └── research/
        ├── boundary-rules.md
        ├── decision-rules.md
        ├── source-tiers.md
        └── style-rules.md
```

## 设计原则

### 1. 先规则，后口气

先把“怎么判断”写死，再叠“怎么说”。
如果顺序反了，skill 很容易退化成只会毒舌和劝退。

### 2. 先蒸馏，后引用

原始语料不是直接塞进 prompt，而是先蒸馏成：

- 决策规则
- 风格规则
- 边界规则

最后只用少量 examples 去校正输出。

### 3. 先中位数，后传奇案例

默认围绕普通家庭、普通分数段、普通毕业生的现实落点做判断。
不拿极端成功者做主要参考。

### 4. 先结构化，后扩语料

V1 先把结构搭稳。
后续真要加更多 B 站、微博、X、小红书和 GitHub 材料，也必须先过 `source-tiers.md` 的证据分层。

## 当前文件用途

- `SKILL.md`
  最终执行协议，定义触发方式、回答骨架、边界和输出顺序。

- `references/research/decision-rules.md`
  写稳定判断逻辑，不写二创口号。

- `references/research/style-rules.md`
  写表达方式、句式节奏、什么能学、什么不能照搬。

- `references/research/boundary-rules.md`
  写红线、失败模式和收口方式。

- `references/research/source-tiers.md`
  规定一手语料、二手传播材料和蒸馏规则的关系，防止污染。

- `examples/`
  用场景而不是金句做 few-shot 校正。

## 建议工作流

1. 先补 `decision-rules.md`
2. 再补 `style-rules.md`
3. 再校对 `boundary-rules.md` 和 `source-tiers.md`
4. 最后补 `examples/`
5. 再回头收紧 `SKILL.md`

## 下一步建议

V1 之后优先做这几件事：

1. 按分数段补 few-shot
2. 按城市层级补判断差异
3. 增加需要联网核实的事实模板
4. 再扩展真实语料样本
