<img src="./assets/hero.png" />

<p align="center">
  <img src="https://img.shields.io/badge/Go_Together-FRONT-Fe9a00?style=for-the-badge" alt="Front">
  <a href=""><img src="https://img.shields.io/badge/Go_Together-BACKEND-FFFFFF?style=for-the-badge" alt="Backend"></a>
  <a href=""><img src="https://img.shields.io/badge/Go_Together-AI-2ECD72?style=for-the-badge" alt="ai"></a>
  <a href="http://docs.creteper.xyz"><img src="https://img.shields.io/badge/About_305-Document-A6AFFD?style=for-the-badge" alt="Documentation"></a>
</p>

# Go Together

<p align="center">
  <img src="https://img.shields.io/badge/Go_Together-Document-Fe9a00?style=for-the-badge" alt="Documentation">
  <a href="http://docs.creteper.xyz"><img src="https://img.shields.io/badge/About 305-Document-A6AFFD?style=for-the-badge" alt="Documentation"></a>
  <a href="#"><img src="https://img.shields.io/badge/BACKEND_BY-ALBamKin-FFFFFF?style=for-the-badge" alt="Documentation"></a>
  <a href="#"><img src="https://img.shields.io/badge/FRONT_BY-Creteper-000000?style=for-the-badge" alt="Documentation"></a>
  <a href="#"><img src="https://img.shields.io/badge/AI_BY-PPGuai-2ECD72?style=for-the-badge" alt="Documentation"></a>
</p>

*我随便的 FreeStyle 他们发疯的记*

Go Together 是一个以 **"AI + 真实旅行经验"** 为核心引擎的智能旅行平台，构建从行前决策到行中服务的**全流程陪伴体验**。它不是又一个旅游 APP，而是您的 AI 旅行伙伴。

<a href="./LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-A6AFFD?style=for-the-badge" alt="LICENSE"></a>

当前旅游行业正面临"信息海啸"的困境——**信息过载却知识匮乏**：

- 用户被海量攻略淹没，筛选效率低下
- 到了景点后却只能看到冰冷的文字介绍，缺少深度讲解
- 个性化行程规划成本高，突发状况应对能力弱
- 弱网/离线环境下地图无法使用

Go Together 应运而生，贯彻《"十四五"旅游业发展规划》，以人工智能技术驱动智慧旅游升级。

| 功能               | 描述                                     |
| ---------------- | -------------------------------------- |
| **AI 导游「小游同学」**  | 景点故事讲解、精准路径规划、实时问答，支持多国语言              |
| **智能行程规划**       | 输入目的地、预算、天数，AI 自动生成详细行程（含交通方式、耗时、预算控制） |
| **智能避堵 & 动态规划**  | 实时交通数据 + 自研路径重算算法，遇突发状况自动调整路线          |
| **AreoMap 地图引擎** | 基于 Leaflet 二次开发，1000 标记点下性能提升约 2 倍     |
| **离线地图缓存**       | 全国地图瓦片缓存（10GB+），弱网/离线环境依然可用            |
| **全部景点聚合**       | 吃、住、行、游一站式信息聚合，覆盖全国 485+ 景点            |
| 🤖 **实体机器人「小游」** | 搭载视觉识别 + 语音交互的实体导游，可为文旅机构提供服务 |

---

## 🛠️ 技术栈

### 前端

| 技术                      | 用途                      |
| ----------------------- | ----------------------- |
| **Next.js** (Turbopack) | 全栈框架，SSR + ISR，SEO 友好   |
| **Leaflet → AreoMap**   | 自研地图引擎，双指针聚合算法，性能提升 2x  |
| **地图瓦片缓存**              | Express.js 瓦片服务器，支持离线导航 |
| **扣子 AI**               | 原型到代码加速（视觉框架生成，逻辑手工重构）  |
### 后端

| 技术 | 用途 |
|------|------|
| **Rust + Actix** | 高性能后端，杜绝内存泄漏，响应速度比行业平均快 3 倍 |
| **MySQL** | 51 万+条真实路径数据存储 |
| **Reqwest** | 轻量级爬虫，速度提升 40%，严格遵循 Robots 协议 |
| **API 网关** | 请求路由、日志记录、系统自优化 |

### AI 引擎

| 技术                   | 用途                                           |
| -------------------- | -------------------------------------------- |
| **RAG Pro 架构**       | 文档切块 → 向量索引 → 相似度检索 → AI 预处理 → LLM 生成，彻底杀死幻觉 |
| **DeepSeek R1**      | 复杂推理 & 深度行程规划                                |
| **BAAI/中科大向量模型**     | 多语言支持，8k tokens 上下文                          |
| **Phantom Eye 视觉系统** | OpenCV 增强 → YOLO 定位 → VLM 语义理解，三级流水线         |
| **NCNN**             | 模型移动端部署，体积压缩 2/3，保留 95% 准确率                  |
| **VBC 降噪技术**         | FFMPEG 预处理 + 频谱分析 + AI 智能滤波，广场舞中也能听清         |
| **火山引擎 TTS**         | 云端语音合成，多国语言，4.8/5 语音评分                       |
| **Vosk**             | 本地语音识别，云端+本地混合识别策略                           |
| **PyTorch-CUDA**     | 模型蒸馏 + 量化 + 微调                               |

### 基础设施

| 技术 | 用途 |
|------|------|
| **GitHub** | 版本控制、分支管理、Issues 追踪 |
| **Apifox** | API 文档 & 接口同步 |
| **LM Studio** | 本地向量索引模型运行 |

关于源码的问题，请咨询我们！


---

## License

MIT — see [LICENSE](LICENSE).

Built by [Nous Research](https://nousresearch.com).
