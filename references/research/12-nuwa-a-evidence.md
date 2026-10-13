# 伯特兰·罗素：原版女娲独立研究补证

研究补证；不评分，不授予A级，不等于全集完成

2026-10-13。默认中性思想；独立可选表达只在用户明确选择时启用，文游禁文风。未改canonical；未读答题与评分结果。

## 覆盖与未读
- **On Denoting（1905）**：继承R5网页4–68、71–120选读；未读：原刊页影、Gray’s Elegy全部争论。
- **The Problems of Philosophy（1912）**：继承IV末及V全章、VI–VII限定范围；本轮XIII629–644连续段；全书20个30–180词散段逐段查看；未读：散段不等于全书通读；未校原版。
- **The Analysis of Mind / 1955集体声明（1921 / 1955）**：继承序言及第一讲选段、共同声明；本轮未重新读取；未读：1914–1919转变、1918讲演、政治通信及晚期认识论。

标为继承的范围来自已读本地来源目录及10/11记录，不宣称本轮重新阅读所有原作；网页行号为工具当时定位，复核须结合章节/段落指纹。

## 本轮连续原作补证
- [XIII网页629–644连续；另sample p251的错误推理例](https://www.gutenberg.org/files/5827/5827-h/5827-h.htm)：自明判断也可能错误分析事实；融贯可增加或然意见可信度，但不能凭组织一致变成绝对确定。 边界：补强有限判断与表达，不把认识论例子当描述理论跨域新验证。

## 逐项三验证审查（不打分）

### 描述存在与唯一性
- 逻辑语义：[定位](https://humanum.arts.cuhk.edu.hk/humftp/E-text/Russell/denoting.htm) R5既读39–48、97–119；存在、唯一性及谓词区分。
- 第二领域：[定位](https://humanum.arts.cuhk.edu.hk/humftp/E-text/Russell/denoting.htm) 未获；负责人、唯一原因是研究者自拟迁移。
跨域：仍为单领域逻辑程序；人物/国王不同例子不是两个领域。
生成力：可生成描述失败类型；未独立新盲测。 独立测试未完成。
区分度：量化结构与否定作用域具体，不能改写成泛泛澄清用词。
地位：保留有限程序；未完成三重独立验证。

### 信念语境替换限制
- 认知报告：[定位](https://humanum.arts.cuhk.edu.hk/humftp/E-text/Russell/denoting.htm) R5既读62–65、102–108；同指替换与所知差异。
- 第二领域：[定位](https://www.gutenberg.org/files/5827/5827-h/5827-h.htm) 本轮XIII非替换论证；新认识论讨论不能冒作本程序第二域。
跨域：未补第二域，保留单域有区分力启发式。
生成力：可区分事实同一与当事人所知；未独立测试。 独立测试未完成。
区分度：描述的主要/次要出现与否定范围；与一般认识谦逊不同。
地位：保留有限程序；未完成三重独立验证。

### 归纳稳定性前提
- 自然预测：[定位](https://www.gutenberg.org/files/5827/5827-h/5827-h.htm) VI既读268–326；过去观察不能演绎保证未来。
- 未观察的过去：[定位](https://www.gutenberg.org/files/5827/5827-h/5827-h.htm) VI既读302–326；过去事实也需归纳。
跨域：时间方向的两个应用不是清晰不同领域；不凑成跨域通过。
生成力：可揭示概率的材料条件；尚未独立测试。 独立测试未完成。
区分度：区分新一次、普遍规律与原则证成，而非一切都不确定。
地位：保留有限程序；未完成三重独立验证。

### 共同毁灭风险（历史案例，不计程序）
- 核战争：[定位](https://pugwash.org/1955/07/09/statement-manifesto/) 原目录R3集体声明网页119–131；共同署名不分配所有句子给个人。
跨域：没有个人两域复现；保持历史案例。
生成力：研究者可迁移，但无从证明本人必如此回答。 独立测试未完成。
区分度：不能以共同风险抹平责任不对称。
地位：保留历史案例，不纳入三模型计数。

## 可复核表达抽样
见可复跑脚本nuwa_a_research_2_sampler.py：固定种子20261013，HTML p序号从0起，规范化空白后取SHA256。通常仅30–180词段，故不是全文均匀抽样；所有最终选中段已在工具输出逐段实际查看。霍克海默为10个合格段的全取；奥斯汀未建立可靠分段。
实取20段；指标：`{"words": 2117, "sentences": 78, "question_sentences": 2, "first_person_tokens": 15, "contrast_tokens": 20, "mean_words_per_sentence": 27.141, "question_sentence_ratio": 0.02564, "first_person_per_1000_words": 7.085, "contrast_per_1000_words": 9.447}`。类比密度与确定性比例未计算。
逐段来源/HTML定位/指纹/原始计数见[russell-perspective-sample.json](russell-perspective-sample.json)。

可直接用于独立表达附录的高层规则：
- 将一个看似简单的断言拆成少数可单独判断的命题。
- 用普通事物构造精确反例；每次反例只改变一个逻辑条件。
- 清楚说明“可以增加可信度”与“能够证明”的距离，语气不必全面犹疑。

反模式与边界：
- 不滥加符号，不以冷峻短句代替论证。
- 不把1905、1912、1921观点拼为永不修订的理论。
- 不把集体反核宣言当个人私语，不套用当前政治立场。
- Length-restricted sampling (30–180 words), not representative of the full work; Horkheimer uses ten eligible original paragraphs without length filtering.
- Sentence boundary regex splits after punctuation; abbreviations/quoted questions may distort counts.
- First-person and contrast are lexical counts, not manually coded rhetorical intentions.
- Analogy density and certainty ratio not measured.
- Electronic transcription not collated with first-edition page images.
- 中文输出只迁移高层修辞功能，不把英法词长/词频硬套到中文。
- 统计中的第一人称可来自作者构造的示范/虚拟对话，不证明真实自述；所概述的他人观点也不是作者赞同。
- 只用于用户明确选用的独立表达附录；默认中性思想，文游禁文风。

## 两项有原作依据的张力
- 经验知识需从已观察推广到未观察；同时这种推广的原则不能用成功史无循环证明。[原作定位](https://www.gutenberg.org/files/5827/5827-h/5827-h.htm)：VI既读302–326。共同要求之间的张力，非简单自相矛盾。
- 理解命题须有亲知的构成基础；同时描述知识可超出私人直接经验。[原作定位](https://www.gutenberg.org/files/5827/5827-h/5827-h.htm)：V全章既读211–274；11号研究记录。共同要求之间的张力，非简单自相矛盾。

## 尚待完成
- 三个执行程序都未获充分两域复现；不应因表达样本完成而升级心智模型。
- 表达20段偏短且仅1912一书，不代表政治文体或数学技术写作。
- 首版/原刊校勘及长期政治演变未完成。

访问：
- web.open成功；requests只读获取用于段落计数；仅保留SHA256、指标和原创笔记，不保存原作全文。

三道已知立场题均为作者实际讨论的问题；仅设计，不作答、不评分。逐题方向及来源另见proposals同名JSON。
