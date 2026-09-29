# 来源与改编说明

这份文件用于了解方法出处和维护文档，不是运行 More Than Yes 时的必读项。日常使用所需的解释和案例已包含在包内，不要求联网取得它们。

## 第一性原理的思想来源

- Aristotle, Posterior Analytics，第一卷第二节；G. R. G. Mure 英译，[MIT Internet Classics Archive 原文](https://classics.mit.edu/Aristotle/posterior.1.i.html)。
- 原文讨论论证的前提、原因与知识之间的关系。这里只借鉴“结论需要适用且可靠的基础”这一思想，不将整个古典知识理论当作现代产品或工程的执行手册。
- 本项目将其应用为：区分目标、事实、约束、假设和沿用做法，检查关键前提，再选择和验证实现路径。这是本项目的实践性改编，不是原文逐字翻译，也不是已验证能提高所有模型表现的算法。

## 钢人论证与忠实理解

- Chris van Merwijk, “Straw-Steelmanning”, 2022-07-13，[作者原文](https://www.lesswrong.com/posts/Fph8Z4BoMtZkxxdB5/straw-steelmanning)。
- 该文区分为原主张寻找更有力的理由，与偷偷将原主张换成另一主张。它是作者的方法讨论，不是统一行业标准，也不是有关本 Skill 效果的实验证明。
- 本项目据此要求区分原意、补充理由与替代方案，并把公平比较同样用于 Agent 的首选方案；同时保留事实核验、用户偏好和权限边界。

## Skill 文件组织

- OpenAI, [Build skills](https://developers.openai.com/plugins/build/skills)：入口说明与参考材料的分工，以及说明何时读取支持文件。
- OpenAI, Eric Provencher, [Rethinking skills and prompts for GPT-6 Astra](https://developers.openai.com/blog/rethinking-skills-and-prompts-for-gpt-6-astra), 2026-09-11：渐进披露与避免无关指令的设计讨论。
- 本包采用完整文件夹交付、执行时按任务读取的方式。不要求使用文中提到的特定模型，不据模型名称推定判断能力，也不把某个宿主的发现、继承或上下文管理方式当作所有宿主的保证。

以上链接的相关正文于 2026-09-29 核对。外部页面之后可能变化；需要核查原文时再访问，不以来源名称代替证据。

## 案例与许可

方法详解和跨场景案例由本项目为教学编写，案例明确标为虚构，不包含开发对话的私人记录、本机目录、账号凭据或用户项目素材。案例用来解释判断，不表示示例方案已在真实项目验证。

本仓库原创说明和案例沿用 [MIT 许可证](LICENSE)。外部链接仅用于归属与追溯，没有将第三方文章整篇复制进包；第三方原文的权利不因链接或本仓库许可证而改变。
