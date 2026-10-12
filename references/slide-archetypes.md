# Slide Archetypes

These are layout archetypes, not rigid templates.

## A. Minimal Cover

用途：论文组会、单篇论文精读。

默认：极简封面，白底黑字，中文标题、英文标题、作者、来源。不使用装饰图或商业元素。

## B. Dense Full-Width Text

适合：Introduction、Related Work、Background、Motivation、Discussion。

结构：标题 + 2–5 个完整专业段落。

默认 Body：

- x = 0.45–0.55
- y = 1.05
- w ≈ 12.2
- h ≈ 5.9

## C. Text Left / Figure Right

适合：概念 + Figure、背景 + 系统图、方法概述 + architecture。

默认：

- Left text: x = 0.55, y = 1.15, w ≈ 5.75
- Right figure: x ≈ 6.60, y ≈ 1.4–2.1, w ≈ 6.15

图必须保持原始纵横比。

## D. Theory / Definition / Equation

适合：数学定义、CRT、AB-SS、Lemma、probabilistic model、optimization model。

布局可为上文下公式，或左解释右公式。

关键公式不得因“太复杂”而自动删除。

## E. Algorithm

适合：Algorithm、sharing、recovery、iterative procedure。

页面应保留：

- Input
- Output
- Parameters
- Numbered steps
- Random variables
- Acceptance/rejection conditions
- Loop/state relationship
- Core equations

不要改成彩色 Step 卡片。

## F. Large Figure / Numerical Example

适合：Fig.2 类型关键数值实例、重要 architecture、需要逐项讲解的原论文 Figure。

原则：原 Figure 占页面主体，旁边或上方保留必要公式、数值步骤和解释。

## G. Explanation Left / Multi-Figure Right

适合：同一实验下多幅视觉结果。

- 左侧：实验条件 / 解释
- 右侧：多幅论文 Figure 上下排列

## H. 2×2 Evidence Matrix

适合：Figure + Curve + Table + Analysis，例如参数敏感性、多指标视觉质量实验。

强调：一个结论需要多类证据时，证据集中在同一页。

## I. Evidence Left / Explanation Right

适合：baseline comparison、cross influence、qualitative + quantitative evidence。

- 左：论文证据
- 右：机制解释 / 指标解释 / 关键 Table

## J. Figure + Multiple Tables

适合：效率分析、筛选次数、参数比较、综合 Table。

推荐：上方 Figure、右侧小 Table、下方宽 Table。

## K. Academic Conclusion

采用正文式总结。

结构可包括：

1. 论文做了什么
2. 实验和分析说明什么
3. 作者承认的限制与 future work

不要自动生成“三张创新点卡片”。

## Layout selection logic

- IF content is primarily continuous academic discussion → Layout B.
- IF content contains 150–300 words + one important figure → Layout C.
- IF formulas / definitions / lemmas dominate → Layout D.
- IF algorithmic steps dominate → Layout E.
- IF one original figure is central to understanding → Layout F.
- IF several related experiment images must be shown together → Layout G.
- IF one claim requires multiple evidence forms → Layout H.
- IF qualitative evidence needs substantial interpretation → Layout I.
- IF efficiency / comparison requires figure + tables → Layout J.
- IF conclusion → Layout K.

Layout 不是死模板。内容完整性、证据清晰度、图片可读性优先于像素级统一。
