此Repo对TeleAI-AI-Flow-Ruyi涉嫌学术不端进行记录


## 之前直接进行询问是否存在学术不端行为的[issue](https://github.com/TeleAI-AI-Flow/AI-Flow-Ruyi/issues/1)被[安泓郡](https://scholar.google.com/citations?user=Q7mHacIAAAAJ&hl=zh-CN)删除了

# 并且安泓郡直接搬出来导师李学龙教授，以一种“我爸是李刚的”姿态对严肃的学术问题进行官腔式地回复。当然，西工大的李学龙教授的影响力确实也足够大。

简单复述一下事件经过，本人发现来自西北工业大学的Hongjun An安泓郡在发表的[文章](AI Flow: Perspectives, Scenarios, and Approaches)中存在疑似学术不端的行为：安泓郡提出的EESB算法与ICLR文章[Anytime Dense Prediction with Confidence Adaptivity](https://arxiv.org/abs/2104.00749)提出的ADP-C算法高度相似，于是我在issue（很不幸已经被安泓郡删除）中提出了质疑，安泓郡同学明显红温并回复到：
> 感谢关注我们的研究工作。这个Issue非常有意思：
> 
> 1. Issue中提到的ADP-C方法是2022年提出的，用于处理计算机视觉任务。稍有研究基础的学生都知道，计算机视觉任务和以LLM为代表的自然语言处理本质上是不同的领域。
> 
> 2. 关于【TL; DR】。欢迎完整读完我们的工作，我们在文章 AI Flow: Perspectives, Scenarios, and Approaches https://arxiv.org/abs/2506.12479 给出了更详细的内容。如果需要更多学术支持，欢迎与ai-flow@chinatelecom.cn联系。
> 
> 3. 中国电信人工智能研究院(TeleAI)由中国电信集团CTO、首席科学家李学龙教授牵头组建，于2024年5月正式成立，同年7月正式揭牌。在李学龙教授的带领下，TeleAI 正在加速推进“智传网(AI Flow)”的研究工作，并与 AI 治理、智能体、智能光电(包括具身智能)，形成“一治+三智”的完整科研布局。 欢迎与我们开展更紧密的合作。链接：https://www.teleai.com.cn/product/AboutTeleAI

ADP-C的作者 [OscarXZQ](https://github.com/OscarXZQ) 也注意到了这个issue并含蓄地表达了“算法相似”、“未恰当引用相关文章”的观点

> 各位好，我是ADP-C的作者之一。感谢@Jiutian-lzy 关注我们的工作：我读了一下AI flow这篇工作的EESB部分，可以肯定没有抄袭嫌疑。感谢作者对于early exit在LLM上的探索～和我们工作最相关的部分应该是在early exit的branch network（在我们的paper里对应的是redesigned head）都有设计比单线性层更复杂的结构以处理intermediate features。
>
> 不过我也注意到，白皮书目前还没提到 CV 领域在 early-exit / anytime inference 方面的一些工作（比如 MSDNet、我们的 ADP-C 等）。虽然任务不同，但“规定budget，中间层加分支”这一设计思路是共通的。如果后续版本能补充相关引用并简要对比，相信能让读者更清晰地看到 AI-Flow 在 LLM 场景的创新点，也让技术脉络更完整。

OscarXZQ的回复直接指出了安泓郡的学术不端行为：安泓郡的EESB与ICML的文章[Early exit LLM](https://arxiv.org/pdf/2312.04916)高度一致，算法设计基本相同
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/4df64d20-84c6-4029-9ac0-b622d867cdf5" />
<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/9870abac-8311-4e91-81b2-b92394563de5" />

## 附上Github邮件截图，以便读者更好地了解被删除issue原貌
<img width="2493" height="1251" alt="image" src="https://github.com/user-attachments/assets/31849d18-16ed-4829-ae6c-b106b860d994" />
<img width="2470" height="1260" alt="image" src="https://github.com/user-attachments/assets/993bbab7-9f63-498a-aee9-5a39b15899b8" />

# 最后，祝安泓郡同学学术事业一帆风顺
