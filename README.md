<p align="center">
  <img src="./profile-header-minimal.svg" alt="Lin Shun — Selected projects" width="100%" />
</p>

<p align="center">
  <strong>林顺 · 悉尼大学计算机科学硕士在读</strong><br />
  Data Science and AI · Master of Computer Science (Advanced Entry)
</p>

<p align="center">
  <a href="https://github.com/mumusama75/cs33">CS33 Capstone</a> &nbsp; / &nbsp;
  <a href="https://github.com/mumusama75/LockdownZone">零号大厦</a> &nbsp; / &nbsp;
  <a href="https://github.com/mumusama75/ai-platform">AI Hub</a> &nbsp; / &nbsp;
  <a href="https://github.com/mumusama75/mini-brotato9001">Mini Brotato Plus</a> &nbsp; / &nbsp;
  <a href="#current-focus">Current Focus</a>
</p>

---

### Selected work

| 项目 | 内容 | 技术 / 状态 |
| :--- | :--- | :--- |
| **[CS33: Event-Conditioned Diffusion](https://github.com/mumusama75/cs33)** | 面向事件相机低光图像增强的 Capstone 项目；包含独立 EcDiff 实现，以及早期 HDRev / Stable Diffusion / ControlNet 实验路线。 | Python · PyTorch · Diffusion · Computer Vision / Active |
| **[封锁区：零号大厦](https://github.com/mumusama75/LockdownZone)** | 医院后勤行政楼的两关逃生原型：声音诱导、双路线、回程捷径与车库自由驾驶；附 10 页关卡设计作品集 V3。 | UE 5.8 · 关卡设计与玩法机制 / 两关可玩原型 |
| **[AI Hub](https://github.com/mumusama75/ai-platform)** | AI 对话与图像生成应用原型，包含模型接口接入、用户管理与社区相关代码。 | JavaScript · Node.js · Express · SQLite / 应用原型 |
| **[Mini Brotato Plus](https://github.com/mumusama75/mini-brotato9001)** | 俯视角生存射击原型，探索自动索敌、武器、敌人生成与成长系统。 | Python · Pygame / 游戏原型 |

### Current focus

**事件相机引导的低光图像增强 · CS33 Capstone · 进行中**

正在研究事件条件扩散模型在低光图像增强中的应用。项目从 HDRev、Stable Diffusion 与 ControlNet 的迁移实验出发，进一步实现了独立的 EcDiff-inspired 多尺度模型，结合 **FEB 事件特征提取**与**跨模态注意力**。

当前保留的 152,000-step 模型在场景独立的 1,354 帧 SDE indoor 验证集上达到 **19.8825 dB PSNR、0.6096 SSIM、0.2103 LPIPS**。仓库记录了数据划分、训练稳定性、消融实验和可复现评估协议；该实现并非论文作者的官方代码。

[`Repository`](https://github.com/mumusama75/cs33) · [`Experiment tracking`](https://wandb.ai/linshun75-university-of-sydney-union/CS33-Event-LowLight-Diffusion)

`Python` · `PyTorch` · `Diffusion Models` · `Event Cameras` · `GPU Training` · `W&B`

### 游戏关卡作品 · 关卡设计与玩法机制

**[封锁区：零号大厦](https://github.com/mumusama75/LockdownZone)** · 两关可玩原型 / 第二关灰盒迭代中

感染暴发后被封锁的医院后勤行政楼。玩家利用撬棍和声音诱导恢复电梯，前往地下车库，驾驶维修皮卡撤离。

- **空间与路线**：B 门投瓶引开感染者、取卡刷门；或从 10 会议室推柜进入风道，抵达 06 档案室。经 D 去配电间，再从 C 门捷径回到电梯。
- **取舍与节奏**：把覆盖全层的风道收束为局部绕行；让手电支持可选回访；用受保护的电梯交互式收尾衔接第二关。
- **策略延续**：车库准备阶段允许试驾和提前挪车，开闸不复位车辆；可以撞倒或绕过 Boss 撤离。

本人负责关卡布局、动线与引导、玩法规则、节奏及迭代决策。代码部分使用 Codex / Gemini 辅助实现；UE / GASP、Kenney CC0 和第三方美术动画注明来源，不作为个人独立编程、建模或动画制作成果。

[**作品集 V3 · 10 页 PDF**](https://github.com/mumusama75/LockdownZone/blob/main/Docs/Portfolio/V3/Portfolio-V3.pdf) · [直接下载](https://github.com/mumusama75/LockdownZone/raw/main/Docs/Portfolio/V3/Portfolio-V3.pdf) · [实机截图与补充影像](https://github.com/mumusama75/LockdownZone/tree/main/Docs/Portfolio/V3) · [项目源码与运行边界](https://github.com/mumusama75/LockdownZone#readme)

作品集分析路线风险、设计取舍和计时规则。现有电梯连续影像无声；核心玩法有声演示、首次玩家测试和驾驶打磨仍待补。

---

<p align="center"><sub>AI applications · Computer vision · Interactive experiences</sub></p>
