<div align="center">

# 宋凯 · Kai Song

**AI Product · Model Evaluation · Speech AI**

电子信息工程本科生 @ 深圳大学  
关注大模型与语音模型的选型、评测、Bad Case 分析和产品迭代

[Email](mailto:2150350174@qq.com) ·
[GitHub](https://github.com/kai666-song) ·
[EvalFlow](https://github.com/kai666-song/EvalFlow)

</div>

---

## About Me

我关注大模型和语音模型如何从“能力演示”走向可验证的产品方案，主要实践方向包括：

- 模型能力拆解、选型与效果评测
- Prompt 迭代、结构化输出和异常处理
- Dataset、Evaluator、Report 与 Bad Case 分析
- AI 产品原型设计与工程闭环
- 语音模型部署及推理性能优化

我能够从产品目标出发定义评测口径，也能够通过代码完成原型、验证假设并定位问题。

---

## Featured Project

### [EvalFlow｜大模型质量评估与优化平台](https://github.com/kai666-song/EvalFlow)

面向模型选型、Prompt 优化验证和 Bad Case 定位场景，设计并实现可重复运行的多模型评测流程。

- 通过 `Dataset → EvaluationRun → Task → EvaluationResult → Report` 组织评测实验
- 接入 OpenAI-compatible API，支持 Qwen、GLM 等模型异步执行
- 记录模型回答、执行状态、延迟及 Input、Output、Reasoning、Cache Token
- 实现关键词评测与 LLM-as-a-Judge，支持评测配置版本化和结果追溯
- 通过受控并发、严格 JSON 校验和失败隔离处理接口异常
- 提供模型质量、通过率、覆盖率、延迟、Token 和 Bad Case 对比页面
- 完成 60+ 自动化测试，并使用 10 个样本、20 个真实模型任务验证完整流程

**Tech:** Python · FastAPI · Pydantic · SQLAlchemy Async · Alembic · pytest

---

## Speech AI Practice

### 语音模型评测与数据处理

围绕语音模型的指令遵循、Voice Design 和 Voice Clone 能力，对 MiMo、Qwen、FishAudio、VoxCPM 等模型进行横向体验与分析。

- 将主观听感拆分为指令控制、声音设计和音色复现等可验证维度
- 使用 60 条样本完成 5–6 轮 Prompt 调整，再扩展处理约 40 小时语音数据
- 使用 Qwen3.5-Omni-plus 处理音频与参考文本，并约束结构化 JSON 输出
- 通过一致性检查、规则匹配、原始响应保留和断点续跑处理异常结果
- 根据模型能力边界、失败样本和应用条件形成产品判断

---

## Engineering Project

### [WeNet Windows C++ Deployment](https://github.com/kai666-song/wenet-windows-cpp-deploy)

将 WeNet 语音识别模型部署到 Windows C++ 环境，减少对 Python 运行环境的依赖。

- 适配 Windows 与 MSVC 构建环境
- 使用 ONNX Runtime 完成 ASR 模型推理
- 在项目测试环境中实现单核 CPU `RTF 0.04`
- 梳理模型加载、音频处理、推理和结果输出流程

**Tech:** C++17 · ONNX Runtime · CMake · WeNet

---

## How I Work with AI

我将 AI 作为产品与工程协作者使用：

- **我负责：** 问题定义、需求拆解、架构设计、评测标准、关键取舍和结果验收
- **AI 协助：** 代码草稿、测试补充、界面迭代、重复性修改和问题排查
- **验证方式：** 复核关键逻辑，通过自动化测试、真实模型调用和 Bad Case 分析验证结果

AI 提升了实现效率，但产品判断、评测口径和最终结果由我负责。

---

## Skills

**AI Product & Evaluation**

Model Evaluation · Prompt Iteration · LLM-as-a-Judge · Bad Case Analysis · Product Prototyping

**Engineering**

Python · FastAPI · Pydantic · SQLAlchemy · pytest · C++ · ONNX Runtime · CMake

**Tools**

Git · GitHub · Docker · Linux/WSL2 · OpenAI-compatible API

---

<div align="center">

**Build with evidence. Evaluate before scaling.**

</div>
