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
| **[封锁区：零号大厦](https://github.com/mumusama75/LockdownZone)** | 末世办公楼 FPS 搜打撤关卡原型，围绕有限弹药、断电搜索、保险丝恢复供电与撤离组织流程。 | Unreal Engine 5 · 关卡设计 / 阶段性可玩原型 |
| **[AI Hub](https://github.com/mumusama75/ai-platform)** | AI 对话与图像生成应用原型，包含模型接口接入、用户管理与社区相关代码。 | JavaScript · Node.js · Express · SQLite / 应用原型 |
| **[Mini Brotato Plus](https://github.com/mumusama75/mini-brotato9001)** | 俯视角生存射击原型，探索自动索敌、武器、敌人生成与成长系统。 | Python · Pygame / 游戏原型 |

### Current focus

**事件相机引导的低光图像增强 · CS33 Capstone · 进行中**

正在研究事件条件扩散模型在低光图像增强中的应用。项目从 HDRev、Stable Diffusion 与 ControlNet 的迁移实验出发，进一步实现了独立的 EcDiff-inspired 多尺度模型，结合 **FEB 事件特征提取**与**跨模态注意力**。

当前保留的 152,000-step 模型在场景独立的 1,354 帧 SDE indoor 验证集上达到 **19.8825 dB PSNR、0.6096 SSIM、0.2103 LPIPS**。仓库记录了数据划分、训练稳定性、消融实验和可复现评估协议；该实现并非论文作者的官方代码。

[`Repository`](https://github.com/mumusama75/cs33) · [`Experiment tracking`](https://wandb.ai/linshun75-university-of-sydney-union/CS33-Event-LowLight-Diffusion)

`Python` · `PyTorch` · `Diffusion Models` · `Event Cameras` · `GPU Training` · `W&B`

### 游戏关卡作品

**[封锁区：零号大厦](https://github.com/mumusama75/LockdownZone)**

从安全办公室观察玻璃后的感染者，到拾取武器、战斗触发断电，再跨区域寻找保险丝并恢复撤离通路。通过 **初始 3 发弹药、17 发弹匣和 6 格背包**组织搜索与资源取舍，结合灯光、区域地标及中文目标提示引导玩家。

目前为阶段性可玩原型，仍在迭代美术与战斗平衡。仓库提供场景截图、设计说明与运行方法；使用的第三方资产在项目中注明来源。

[场景截图与运行说明](https://github.com/mumusama75/LockdownZone#readme) · [关卡设计说明](https://github.com/mumusama75/LockdownZone/blob/main/DESIGN.md)

---

<p align="center"><sub>AI applications · Computer vision · Interactive experiences</sub></p>
