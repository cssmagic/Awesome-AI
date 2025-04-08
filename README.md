# Awesome AI

收集分享 AI 大型语言模型 (LLM)、AI 辅助编程、AI 绘画等领域的常用资料，探索生成式人工智能的应用与开发。

> ### 目录
>
> * [大型语言模型](#index--llm)
> * [AI 编程](#index--programming)
> * [AI 绘画 / 音频视频创作](#index--art)
> * [常用 AI 网站 / 工具](#index--tools)
> * [常见问题](#faq)

> 🔍 提醒：善用搜索，按 Ctrl+F 或 ⌘F 定位到你想找的关键词。<br>
> 💡 持续更新中，建议添加到浏览器收藏夹，平常一定会用到。

[![Book](https://github.com/user-attachments/assets/70f861e5-cc82-4663-9014-77502de8df9f)](https://u.jd.com/MDPrbVr)

## 大型语言模型 <a name="index--llm">&nbsp;</a>

### OpenAI GPT / o1 / ChatGPT <a name="gpt">&nbsp;</a>

* 简介：OpenAI 的 GPT 系列和 o 系列模型目前全球最先进的大型语言模型。GPT 的原义是 “生成式预训练变换器”。目前全球最火的 AI 应用产品 ChatGPT 就是基于 GPT 模型实现的。
* 官网：https://openai.com/api/
* Playground：（不是免费的，会消耗你的 API 调用额度）
	* Chat 模式：https://platform.openai.com/playground?mode=chat
	* Assistants 模式：https://platform.openai.com/playground?mode=assistant
* API：
	* 定价：https://openai.com/pricing
	* 官方文档：https://platform.openai.com/docs/overview
	* 其他资料：
		* [GPT-4o API 实测解析：开发者的福音还是挑战？](https://mp.weixin.qq.com/s/Muf2nFrgKdEeGoRAIlub0w)
		* [扒一扒 OpenAI o1 系列模型：为什么这么强？](https://mp.weixin.qq.com/s/mXVTFTepl8D98hcK9-jPGg) | [对开发者有何影响？](https://mp.weixin.qq.com/s/DXdirHmXgBPVxzCsc9XNMQ)
* Web 产品（ChatGPT）： <a name="chatgpt">&nbsp;</a>
	* 简介：ChatGPT 是目前全球最热门的 AI 应用产品，是一款能以自然语言对话进行交互的 AI 助手。除了对话之外，它还集成了绘画、代码解释器等功能。2022 年 11 月 30 日上线，2023 年 11 月推出 GPTs（自定义 ChatGPT），2024 年 1 月推出 GPTs 商店，持续引领 AI 领域的热潮。
	* 入口：https://chatgpt.com/
	* 定价：
		* ChatGPT Free（GPT-3.5 + 语音对话）：免费无限量
		* ChatGPT Plus（Free + GPT-4 + 绘图 + GPTs + ...）：$20 / 月
		* ChatGPT Team（Plus + 协作空间 + 数据保护 + ...）：$25 / 月 / 人
	* 相关资料：
		* [ChatGPT 定制化进阶：四步成为 AI 对话高手](https://www.cssmagic.net/blog/wx/60)
		* [买了 ChatGPT 会员却没用过 “代码解释器”？亏了，快看这三个案例](https://www.cssmagic.net/blog/wx/72)
		* [全面升级！GPT-4o 第一时间体验、疑问解答、福利揭秘](https://mp.weixin.qq.com/s/tkEuVXoJuaRN-TQZeTqXiQ)
* Web 产品（GPTs）： <a name="gpts">&nbsp;</a>
	* 简介：GPTs 是 ChatGPT 的拓展。它允许用户针对特定场景定制一个特殊的对话机器人，甚至可以附加自己的知识库或调用外部 API，从而实现比常规 ChatGPT 更高效、更精准的对话效果。2024 年 1 月 GPTs 商店上线，开发者分成计划也呼之欲出。
	* GPTs 商店：https://chat.openai.com/gpts
	* 相关资料：
		* GPTs 完全指南：[入门篇](https://www.cssmagic.net/blog/wx/62) | [如何开发](https://www.cssmagic.net/blog/wx/63) | [如何上架](https://www.cssmagic.net/blog/wx/64) | [如何赚钱](https://www.cssmagic.net/blog/wx/65)
		* [GPTs 商店即将开张，坐等赚钱之际，别忘了做好防盗工作](https://www.cssmagic.net/blog/wx/58)
		* [任意 GPTs 资源文件泄露问题探讨](https://mp.weixin.qq.com/s/Bklnu0RhF8bnK1Irx14S5g)
		* [SecurityGPT：提示词安全防护](https://github.com/GPTGeeker/securityGPT)

### Claude

* 简介：Anthropic 公司发布的多模态 AI 模型。Claude 的模型规模从小到大分别有 Haiku、Sonnet、Opus 三个版本。
* 官网：https://www.anthropic.com/claude
* Web 产品（Claude）：
	* 入口：https://claude.ai/ （需要验证海外手机号）
	* 定价：有免费版。专业版套餐 $20 / 月。
* 相关资料：
	* [API 文档](https://docs.anthropic.com/en/api/getting-started)
	* [anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook)：Anthropic 官方提供的案例演示

### Google Gemini <a name="gemini">&nbsp;</a>

* 简介：Google 开发的原生多模态大模型。根据模型规模分为 Ultra、Pro、Nano 三个版本。
* 官网：https://ai.google.dev/
* Playground：
	* Google AI Studio：https://makersuite.google.com/
	* Vertex AI Studio：https://console.cloud.google.com/vertex-ai/generative/multimodal/create/text
* API 文档：https://ai.google.dev/tutorials/rest_quickstart
* Web 产品（原 Bard 已更名为 Gemini）：https://gemini.google.com/app

### 深度求索 / DeepSeek <a name="deepseek">&nbsp;</a>

* 简介：国产开源大模型。其推理模型 R1 性能比肩 OpenAI o1。已开放 API，定价极为低廉。
* 官网：https://www.deepseek.com/
* API 文档：https://platform.deepseek.com/docs
* Web 产品：https://chat.deepseek.com/
* 更多介绍：
	* [国产大模型又出黑马！DeepSeek 初体验，价格屠夫大杀四方](https://mp.weixin.qq.com/s/TY4nap6sR71bImaD8-NFKw)
	* [两种方法免费使用 DeepSeek API，建议收藏备用](https://mp.weixin.qq.com/s/UydlR9HVu2UYoBgtufMARg)
	* [DeepSeek 这三种进阶玩法你一定要知道](https://mp.weixin.qq.com/s/nP3CIwZbueY-Mhfh06QbGw)

### 智谱 GLM / ChatGLM（智谱清言） <a name="chatglm">&nbsp;</a>

* 简介：清华智谱团队推出的大模型。有开源版本，可私有化部署。
* 官网：https://models.aminer.cn/glm-130b/
* API 文档：https://open.bigmodel.cn/dev/api
* Web 产品（智谱清言）：https://chatglm.cn/main/detail
* Web 产品（GLMs）：https://chatglm.cn/glms

### Moonshot AI / Kimi

* 简介：月之暗面推出的大模型。其特点为支持 20 万字的超长上下文。已开放 API。
* 官网：https://www.moonshot.cn/
* API 文档：https://platform.moonshot.cn/
	* 定价：https://platform.moonshot.cn/pricing
* Web 产品（Kimi 智能助手，原 Kimi Chat）：https://kimi.moonshot.cn/
* 更多介绍：
	* [性能超出预期！神秘的国产大模型 Kimi 开放 API](https://www.cssmagic.net/blog/wx/68)
	* [解答 Kimi API 常见问题，顺便探讨 AI 应用开发的那些事儿](https://www.cssmagic.net/blog/wx/69)
	* [Kimi API 还没用起来？请看这篇无门槛快速入门指南](https://www.cssmagic.net/blog/wx/70)

### 更多

* 更多国产大模型：
	* [通义千问 / Qwen](https://tongyi.aliyun.com/)：阿里云出品的大模型，有开源版本。
		* Web 产品：https://tongyi.aliyun.com/qianwen/
		* App 产品：通义千问 App 提供了问答助手、AI 工具等常规功能外，还提供了通义舞王、涂鸦作画等特色功能。
		* API 文档：https://help.aliyun.com/zh/dashscope/developer-reference/api-details
	* [百度文心大模型 / 文心一言](https://wenxin.baidu.com/)：文心一言是由百度公司开发的聊天机器人，于 2023 年 3 月 16 日发布。文心一言由文心大模型驱动。
		* API 文档：https://cloud.baidu.com/doc/WENXINWORKSHOP/s/clntwmv7t
		* Web 产品（文心一言）：https://yiyan.baidu.com/
		* Web 产品（飞桨 AI 应用中心）：https://aistudio.baidu.com/application/center
	* [零一万物 / Yi](https://www.lingyiwanwu.com/)：国产开源多模态大模型。30 万字超长上下文。已开放 API。
		* Web 产品（万知）：https://www.wanzhi.com/ （长文总结要点、文档生成 PPT 等）
		* API 文档：https://platform.lingyiwanwu.com/
	* [讯飞星火认知大模型](https://xinghuo.xfyun.cn/)：
		* Web 产品（SparkDesk）：https://xinghuo.xfyun.cn/desk
		* API 文档：https://www.xfyun.cn/doc/spark/Web.html
	* [MiniMax](https://api.minimax.chat/)
		* Web 产品（海螺 AI）：https://hailuoai.com/
		* API 文档：https://api.minimax.chat/document/introduction?id=6433f37594878d408fc82959
	* [阶跃星辰](https://www.stepfun.com/)：宣称在图像理解、多轮指令跟随、数学能力、逻辑推理、文本创作等方面性能达到业界领先水平。
		* Web 产品（跃问）：https://stepchat.cn/chats/new
		* API 文档：https://platform.stepfun.com/docs/overview/concept
	* [面壁智能 / MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V/blob/main/README_zh.md)：面壁智能出品的端侧多模态大模型系列，接受图像和文本输入，提供高质量的文本输出。可运行于手机、平板等智能终端进行推理。MiniCPM-V 2.6 以极小的参数量实现了 GPT-4V 级别的性能。
		* 体验地址：https://huggingface.co/spaces/openbmb/MiniCPM-V-2_6
	* 开源的中文 LLM：https://github.com/HqWu-HITCS/Awesome-Chinese-LLM
* 图片识别 API：
	* GPT-4V：https://platform.openai.com/docs/guides/vision
	* Gemini Pro Vision：https://ai.google.dev/tutorials/rest_quickstart#text-and-image_input
* 人性化的聊天机器人：
	* [Pi](https://pi.ai/)：人性化的 AI 对话助手。
	* [Hume AI](https://www.hume.ai/)：能识别语音情绪的 AI 模型，提供 API。提供了一个 [在线演示](https://demo.hume.ai/)，可以与 AI 机器人语音对话。
* [Artificial Analysis](https://artificialanalysis.ai/)：大模型性能多维度测评排行榜。



## AI 编程 <a name="index--programming">&nbsp;</a>

### GitHub Copilot <a name="gitub-copilot">&nbsp;</a>

* 简介：AI 辅助编程领域的标杆。由 GitHub 和 OpenAI 共同开发，作为编辑器插件集成到开发环境中，支持 VS Code 和 JetBrains IDE 等主流开发工具。它提供代码补全、智能对话、多文件编辑等功能。2024 年底开放免费套餐。
* 官网：https://github.com/features/copilot
* 定价：https://github.com/features/copilot/plans
	* 免费套餐：功能几乎没有限制，只限制调用次数。
	* 专业版：$10 / 月（第一个月免费试用）
* 推荐书籍：
	* [《AI 辅助编程入门：使用 GitHub Copilot 零基础开发 LLM 应用》](https://github.com/cssmagic/AI-Assisted-LLM-Dev-Book)

### Cursor

* 简介：AI 辅助编程领域的后起之秀。Cursor 是一款编辑器，基于 VS Code 内核。除了基础的代码补全功能以外，它还提供了批量补全、预测下一步操作、智能对话、多文件编辑等高级功能。
* 官网：https://cursor.com/
* 定价：https://cursor.com/pricing
	* 免费版（两周的专业版试用期 + 2000 次补全 + 有限次对话请求）：免费
	* 专业版（无限次补全 + 每月 500 次快速对话请求 + 无限次慢速对话请求）：$20 / 月

### 其他

* AI 编辑器 / 编辑器插件：
	* [Augment Code](https://www.augmentcode.com/product)：AI 编程插件，支持 VS Code 和 JetBrains IDE 等主流开发工具，更强的上下文感知能力。付费套餐 $30 / 月；有免费套餐，含无限次补全、3000 次聊天和 50 次代理调用。
	* [Windsurf](https://codeium.com/windsurf)：Codeium 出品的一款代码编辑器，基于 VS Code 内核，集成了 Agent 能力，支持各种高级的 AI 辅助编程功能。新用户可获得 2 周的专业版套餐试用期。
	* [Cline（原名 Claude Dev）](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev)：VS Code 插件，融合了 Agent 思维，通过对话生成（或修改）项目代码。需自备 LLM API。[已开源](https://github.com/cline/cline)。
	* [Trae](https://www.trae.ai/)：字节跳动出品的 AI 代码编辑器，产品形态类似 Cursor 和 Windsurf，面向海外市场。目前完全免费。暂时只支持 Mac 系统。
	* [CodeGeeX](https://codegeex.cn/)：智谱旗下的智能编程助手。支持 20 多种编程语言，适配 VS Code 和 JetBrains IDE 等主流开发工具。个人用户免费。企业用户可选择私有化部署服务。
	* [MarsCode](https://www.marscode.cn/)：字节跳动豆包大模型旗下的智能编程助手。提供智能补全、智能预测、智能问答等能力，适配 VS Code 和 JetBrains IDE 等主流开发工具。个人用户免费。
	* [通义灵码](https://tongyi.aliyun.com/lingma)：阿里云出品的编辑器插件，支持 VS Code 和 JetBrains IDE 等。个人用户免费。
	* [腾讯云 AI 代码助手](https://cloud.tencent.com/product/acc)：腾讯云出品的编辑器插件。个人用户免费。
	* [文心快码](https://comate.baidu.com/zh)：百度出品的编辑器插件。个人用户免费。
	* [CodeFuse](https://codefuse.alipay.com/welcome/download)：蚂蚁集团出品的编辑器插件。个人用户免费。
	* [Codeium](https://codeium.com/)：编辑器插件，支持 VS Code 和 JetBrains IDE 等。
		* 定价：个人版（代码建议 + 对话）：免费
	* [Tabnine](https://www.tabnine.com/)：编辑器插件，支持 VS Code 和 JetBrains IDE 等。
		* 定价：基础版（基础的代码补全功能）：免费
	* [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/)：编辑器插件，支持 VS Code 和 JetBrains IDE 等。
		* 定价：个人版（代码建议 + 参考跟踪 + 安全扫描）：免费
* 网页设计与生成工具：
	* [Bolt.new](https://bolt.new/)：StackBlitz 出品的 AI 编程工具，可在线生成、编辑、运行、部署全栈网站，一站式解决网站开发需求。支持多种基于 JS 的前后端技术栈。
	* [v0.dev](https://v0.dev/)：Vercel 出品的 AI 网页设计开发工具。通过对话生成网页，可一键发布。主力支持 shadcn/ui (React) + Tailwind 技术栈，后续会支持更多前端技术栈。有免费配额。
	* [Wegic](https://wegic.ai/)：AI 驱动的网页 UI 设计和开发工具。通过自然对话快速生成网站，可通过对话持续修改，可一键发布。
	* [OpenUI](https://github.com/wandb/openui)：开源项目，AI 自动生成前端代码。可根据描述生成 UI 界面，且可以持续输入描述进行修改，可输出 HTML、React、Vue 组件等格式。支持输入中文描述。[在线演示](https://openui.fly.dev/)。
* 其他工具：
	* [CopyCoder](https://copycoder.ai/)：把网页设计稿、原型图转换成适合 AI 编程工具处理的提示词，适合与 Cursor、Windsurf、Bolt.new、v0.dev 等工具配合使用。
	* [Devin](https://www.cognition-labs.com/introducing-devin)：Cognition Labs 推出的 AI 编程机器人，有很强的自主学习和工作能力。内测申请排队中，还未正式开放。
	* [Gru.ai](https://gru.ai/)：一款在线的编程助手 AI Agent，根据用户的任务生成代码，支持 Python 和 TS 语言。
* 推荐书籍：
	* [新书《AI 辅助编程 Python 实战》在翻译了，不容错过！](https://www.cssmagic.net/blog/wx/67)


## AI 绘画 / 音频视频创作 <a name="index--art">&nbsp;</a>

### AI 绘画

* [Midjourney](https://www.midjourney.com/home)<a name="midjourney">&nbsp;</a>：是一款热门的 AI 绘画工具，早期依托 Discord 平台提供服务，现已推出独立网页版应用。它易于入门，作品风格华丽，适合初学者探索 AI 艺术创作，创造独特的视觉作品。
	* 定价：
		* 基础版套餐（3.3h Fast Time）：$10 / 月
		* 标准版套餐（15h Fast Time + Unlimited Relax Time）：$30 / 月
		* 专业版套餐（30h Fast Time + Unlimited Relax Time）：$60 / 月
		* 至尊版套餐（60h Fast Time + Unlimited Relax Time）：$120 / 月

* [OpenAI DALL·E](https://openai.com/dall-e-3)<a name="dall-e">&nbsp;</a>：OpenAI 出品的图片生成工具。对提示词的理解能力极强，与 ChatGPT 的整合也令它极为易用。
	* Web 产品：
		* ChatGPT Plus（GPT-4 + DALL·E 3）：https://chat.openai.com/#pricing
			* 定价：$20 / 月
		* DALL·E 2：https://labs.openai.com/
			* 定价：$15 / 115 点

* [Stable Diffusion](https://stability.ai/stable-image)<a name="sd">&nbsp;</a>：是一款先进的人工智能图像生成模型，由 Stability AI 开发。可本地部署。因其开源特性，发展迅速，已经成长为一个庞大的生态，广泛应用于艺术创作、设计和多媒体制作等领域。
	* 扩展：
		* ComfyUI：https://github.com/comfyanonymous/ComfyUI
			* 中文学习社区：https://www.comflowy.com/zh-CN

* [FLUX.1](https://www.basedlabs.ai/tools/flux1)：是一个全新的开源图像生成模型。它由 Black Forest Labs 开发，该团队也是 Stable Diffusion 的幕后团队。

### AI 视频生成

* [Runway Gen-2](https://app.runwayml.com/)：视频生成领域的热门产品。它提供了多种 AI 视频生成模型，包括文生视频、图文生成视频、图生视频、风格化渲染、局部叠加渲染、3D 模型渲染等功能。有免费额度。[官网](https://research.runwayml.com/gen2)
* [Pika](https://pika.art/)：视频生成领域的热门产品，典型功能为图生视频。新版本主打趣味视频生成功能。有免费额度。
* [PixVerse](https://pixverse.ai/)：视频生成工具，支持文生视频、图生视频、人物生成视频等。有免费额度。
* [Stable Video Diffusion](https://stability.ai/stable-video)：Stability AI 发布的开源的视频生成模型。可本地部署。
	* 简介：https://mp.weixin.qq.com/s/il3YahMQyw55KdQ7acxIow
	* 教程：https://huggingface.co/docs/diffusers/main/en/using-diffusers/svd
* [OpenAI Sora](https://openai.com/sora)：OpenAI 发布的视频生成模型。可实现文生视频、图生视频、视频延长和衔接。生成视频长达一分钟。目前仅面向安全领域和创作领域的专家开放内测，还没有正式开放。
* [可灵大模型](https://kling.kuaishou.com/) / [可灵AI](https://klingai.kuaishou.com/)：快手出品的视频生成大模型，支持文生视频、图生视频、视频续写等能力。支持最长 3 分钟高清视频生成，堪称 “中国版 Sora”。
* [智谱清影](https://chatglm.cn/video)：智谱 AI 推出的视频生成工具，支持文生视频、图生视频等功能，比如 “老照片动起来” 等应用。可生成 10 秒、4K 分辨率、60 帧高清视频。目前免费开放，支持 API 调用。
* [Vidu](https://www.vidu.studio/)：Vidu 是由清华大学朱军教授团队研发的 AI 视频生成器。支持生成高逼真度的 4 秒或 8 秒 1080p 高清视频。亮点包括生成速度快、角色一致性、支持写实和动漫风格、生成效果连续流畅等，可应用于游戏、影视、教育等领域。
* [Luma Dream Machine](https://lumalabs.ai/dream-machine)：Luma AI 出品的视频生成模型。支持文生视频、图生视频，可生成 5 秒长度的视频。有免费额度。
* [剪映专业版（国内版）](https://www.capcut.cn/) / [CapCut（海外版）](https://www.capcut.com/)：字节跳动出品的视频编辑工具，支持 Windows/Mac。它集成了大量基于 AI 技术的音视频处理功能，比如生成字幕、生成配音、降噪、变声、数字人、文生视频等等。

### 3D 建模

* [Zero-1-to-3 (zero123)](https://github.com/cvlab-columbia/zero123): Zero-shot 单张图片生成 3D 物体。哥伦比亚大学的开源项目。
* [One-2-3-45](http://one-2-3-45.com/)：“Any Single Image to 3D Mesh in 45 Seconds without Per-Shape Optimization”。开源项目。
* [Wonder3D](https://www.xxlong.site/Wonder3D/)：“Wonder3D produces consistent multi-view normal maps and corresponding color images, and thus reconstructs high-fidelity textured mesh from a single image in only 2~3 minutes”。开源项目。
* [Stable Zero123](https://stability.ai/stable-3d)：单张图片生成高质量 3D 物体。Stability AI 开源模型，可整合到 ComfyUI 工作流。
* [DreamGaussian](https://dreamgaussian.github.io/)：Generative Gaussian Splatting for Efficient 3D Content Creation。开源项目。
* [Tripo AI](https://vectorizer.ai/)：通过文本或图片生成高质量 3D 模型，可下载。有免费配额。
* [Genie](https://lumalabs.ai/genie)：Luma AI 出品的一款通过文本生成 3D 模型的 AI 工具。目前依托 Discord 提供服务。
* [Luma AI](https://lumalabs.ai/dashboard/captures)：通过视频来重建 3D 场景。你只需要有一台手持拍摄设备，按要求对物体进行 360°旋转拍摄。有网页版和 iOS App。

### 数字人 / 语音驱动视频 / TTS

> TTS：Text to Speech，文本生成语音。

* [Fish Audio](https://fish.audio/zh-CN/)：多功能 AI 音频工具，支持中英等语言，提供文本转语音（TTS）和 语音转文本（ASR）等功能。
* [万兴播爆](https://virbo.wondershare.cn/)：输入文案，一键生成数字人播报视频。
* 剪映：可生成数字人播报视频。
* [HeyGen](https://www.heygen.com/)：生成数字人播报视频，视频翻译，语音克隆。
* [Eleven Labs](https://elevenlabs.io/)：文本转语音（TTS），通过文字描述生成音效，语音克隆，视频翻译配音。有 API。
* [EMO](https://humanaigc.github.io/emote-portrait-alive/)：阿里发布的（图片 + 音频 → 视频）大模型，生成的人物嘴形和表情相当自然。
* [ChatTTS](https://github.com/2noise/ChatTTS/blob/main/docs/cn/README.md)：开源的文本转语音（TTS）模型，支持中文和英文。可以控制停顿和笑声等人性化特征，生成结果自然流畅。
* [ChatTTS webUI](https://github.com/jianchang512/ChatTTS-ui)：一个简单的本地网页界面，使用 ChatTTS 将文字合成为语音，同时支持对外提供 API 接口。已开源。
* [Seed-TTS](https://bytedancespeech.github.io/seedtts_tech_report/)：字节跳动发布的高质量、多功能语音生成模型，未开源，似乎也没有发布可用的产品。支持音色微调、带情绪的 TTS、音色转换、情绪转换、基于原语音生成新语音、语音内容编辑、调速等能力。可应用于有声读物、翻译视频等场景。
* 剪映：已上线 AI 克隆音色的功能，只能克隆自己的音色。
* [微软 Azure AI 语音](https://azure.microsoft.com/zh-cn/products/ai-services/ai-speech/)：微软的云服务，支持语音转文本、文本转语音、语音翻译和说话人辨识等功能。
* [LivePortrait](https://github.com/KwaiVGI/LivePortrait)：快手开源的人物肖像控制模型，可通过五官视频驱动图片生成视频，或修改其他视频。[在线体验](https://huggingface.co/spaces/KwaiVGI/LivePortrait)。
* [ReSyncer](https://guanjz20.github.io/projects/ReSyncer/)：一个研究项目，通过语音和视频模板素材，生成更自然的唇形视频。可应用于数字人场景。目前只有研究论文，还没有公开可用的产品。
* [MaskGCT](https://maskgct.github.io/)：香港中文大学（深圳）与趣丸科技合力打造的最新一代语音克隆模型，已开源，具备零样本 TTS 能力（只需 1 秒声音样本即可克隆）。[在线试用](https://huggingface.co/spaces/amphion/maskgct)。
* [Ultralight-Digital-Human](https://github.com/anliyuan/Ultralight-Digital-Human)：一个超轻量级、可以在移动端实时运行的数字人模型，已开源。
* [clone-voice](https://github.com/jianchang512/clone-voice)：一个带 web 界面的声音克隆工具，使用你的音色或任意声音来录制音频。支持 Windows、Mac 和 Linux。已开源。

### 在线 SD 绘画

* [Leonardo.Ai](https://leonardo.ai/)：易用且强大的 AI 绘图平台，底层基于 SD，深度集成 SD 各种插件，提供训练好的模型，可训练模型。有免费配额。
* [eSheep 电子羊](https://www.esheep.com/)：体验在线的 WebUI 和 ComfyUI。新用户获得 100 积分。每 100 积分相当于 ¥1。
* [网易 AI 设计工坊](https://sd.study.163.com/)：在线 WebUI，可训练模型。有免费配额，每天 10 次。
* [LibLib AI](https://www.liblib.art/)：在线 WebUI，可训练模型。有免费配额，每天 300 积分。
* [Cephalon Cloud 端脑云](https://cephalon.cloud/#/share/register-landing?id=Hf7YkG)：云端一键部署自己的 WebUI 和 ComfyUI。新用户获得 2000 积分。每 1000 积分相当于 ¥1。
* [即梦 AI](https://jimeng.jianying.com/ai-tool/home)：字节跳动出品的在线绘画平台，主打易用和免费。原名 “Dreamina”。

### 音乐歌曲创作

* [Suno](https://suno.com/)：AI 根据你的要求生成歌曲（作词、作曲、演唱）。
* [天工 AI 音乐](https://www.tiangong.cn/music)：根据歌名、歌词、参考音频创作音乐，可由 AI 帮写歌词。

### 音频视频处理

* [vocal-separate](https://github.com/jianchang512/vocal-separate)：一个极简的人声和背景音乐分离工具，本地化网页操作，无需连接外网。已开源。
* [pyVideoTrans](https://pyvideotrans.com/)：开源视频翻译软件，一键字幕生成 + 字幕翻译 + 创建配音 + 合成 = 带字幕和配音的新视频。
* [GVS 硬字幕提取](https://pyvideotrans.com/aiocr)：智能识别视频硬字幕，快速提取，支持中英文。

### 其他创作工具

* [神采 / PromeAI](https://www.ishencai.com/)：图片生成和编辑工具，包括草图渲染、照片转线稿、局部重绘、抠图去背景、换背景、扩图、重打光、高清放大、文字融合、AI 写真、图生视频等。有免费配额。
* [DomoAI](https://domoai.app/)：视频风格转绘，比如把一段现有视频转换为二次元日漫、像素风、油画、3D 皮克斯动画等风格。此外还有文生图、图生图、图生视频等功能。有免费配额。
* [Comic AI](https://comicai.ai/)：AI 漫画制作工具。有免费配额。
* [Logo Diffusion](https://logodiffusion.com/)：AI 设计 Logo 工具，主要功能有：提示词生成 Logo、图片转 Logo、用提示词修改 Logo、手绘草稿美化、2D 转 3D。有免费配额。
* [AutoPod](https://www.autopod.fm/)：Premiere Pro 插件，自动完成多机位剪辑、停顿切除。
* [Canva 可画](https://www.canva.cn/)：老牌的在线设计工具，提供了大量模板和设计元素，支持 AI 设计。
* [FaceSwap](https://faceswap.so/)：多功能的在线换脸工具。支持图片换脸、多人换脸、视频换脸等功能。有免费配额。
* [Remaker - Face Swap Online Free](https://remaker.ai/face-swap-free/)：免费的在线换脸工具，支持图片换脸。
* [绘蛙](https://www.ihuiwa.com/)：面向电商领域的 AI 模特换装生图工具。阿里出品。
* [OOTDiffusion](https://github.com/levihsu/OOTDiffusion)：一个开源的 “试衣” 模型。[在线演示](https://huggingface.co/spaces/levihsu/OOTDiffusion)。
* [TryOffDiff](https://github.com/rizavelioglu/tryoffdiff)：一个开源的 “脱衣” 模型，从图片中提取服装标准图。[在线演示](https://huggingface.co/spaces/rizavelioglu/tryoffdiff)。

（持续更新中……）



## 常用 AI 网站 / 工具 <a name="index--tools">&nbsp;</a>

### 综合平台

* [POE](https://poe.com/)：各种知名模型的聚合平台。用户可根据自己的需求通过 Prompt 定制对话机器人，相当于 GPTs 平替。付费用户可无限量使用 GPT-4、Claude 2 等高端模型。
* [FlowGPT](https://flowgpt.com/)：一个 Prompt 分享平台。提供了角色聊天、游戏、创意、生产力等各种类型的对话机器人，是一个学习提示词的好地方。也可以把它当作 GPTs 平替。
* [Character.AI](https://beta.character.ai/)：与各种类型的 AI 虚拟角色对话，包括世界名人、动漫人物、游戏角色等。
* Coze：字节跳动推出的 AI 聊天机器人及 AI 应用开发平台。无论是否具备编程基础，用户都可以快速构建特定功能的聊天机器人，并发布到各大社交平台。
	* 官网（海外版）：https://www.coze.com/
	* 官网（国内版）：https://www.coze.cn/
	* 中文文档（海外版）：https://www.coze.com/docs/zh_cn/welcome.html
	* 中文文档（国内版）：https://www.coze.cn/docs/guides/welcome
* [GPTsCopilot](https://chat.openai-now.com/)：第三方 GPTs 商店，提供 GPTs 中转访问服务。在 GPTs 的网址中，把 `openai.com` 改成 `openai-now.com` 就可以切换到 GPTsCopilot 提供的中转访问服务，无需成为 ChatGPT Plus 会员即可使用 GPTs。
	* 定价：https://gptscopilot.ai/pricing
		* 基础版（每天 5 积分）：免费
		* 专业版（每月 1500 积分）：$9.99 / 月
		* 按需付费方案：$5.99 / 500 积分 或 $9.99 / 1000 积分
* [Toolify.ai](https://www.toolify.ai/)：AI 工具分类导航目录。
* [There's An AI For That (TAAFT)](https://theresanaiforthat.com/)：提问我的需求可以用哪些 AI 工具来实现。
* [通往 AGI 之路 / WayToAGI](https://www.waytoagi.com/)：AI 工具（包含网站和 GPTs）分类导航目录，也可搜索。
* [ChandlerAi](https://chandler.bet/)：国内可用的 AI 助手，可调用 GPT-4、Claude 3 Opus、Gemini、DALL·E 等先进模型。需要付费。

### 图像处理 / 图形设计 / UI 设计

* [Vectorizer.AI](https://vectorizer.ai/)：基于 AI 的位图转矢量图的在线工具，比如 PNG → SVG。已经不可免费使用，需要订阅（$10 / 月）。
* [Galileo](https://www.usegalileo.ai/)：通过提示词生成 UI 设计稿，可导出到 Figma。
* [Magnific AI](https://magnific.ai/)：图片放大，增强细节。
* [Photoroom](https://www.photoroom.com/zh)：在线 AI 图片处理工具。免费用户可使用抠图、擦除、照片优化功能。
* 抠图：
	* [四款免费的 AI 抠图工具，最后一个不敢相信！](https://www.cssmagic.net/blog/wx/56)

### 写作 / PPT 幻灯片

* [Notion AI](https://www.notion.so/product/ai)：Notion 中的 AI 写作助手。增值服务，每月 $10。
* [蛙蛙写作](https://www.wawawriter.com/)：国产写作模型，写长篇小说、视频脚本、论文等。免费试用 3000 字。
* [讯飞智文](https://zhiwen.xfyun.cn/)：Word、PPT 一键生成、AI 撰写助手、多语种互译、AI 自动配图、PPT 转演讲稿等。
* [腾讯文档](https://docs.qq.com/desktop)：AI 助手提供生成 PPT、生成文档、生成表格、生成思维导图、生成收集表等功能。
* [Gamma](https://gamma.app/)：AI 设计助手，生成 PPT、文档和网页，优化现有 PPT 和文档。
* [AiPPT.cn](https://www.aippt.cn/)：AI 一键生成 PPT。支持自动生成 PPT 大纲文案，文档秒变 PPT，支持多种模板，兼容 pptx 格式。
* [ProcessOn](https://cmcm.link/p/processon)：老牌在线图表绘制工具，支持流程图、泳道图、思维导图、架构图、建筑平面图等等形式。支持 AI 自动生成图表。

### 内容分析、识别、提炼

* [通义听悟](https://tingwu.aliyun.com/u/82xz94v6z6z9m6v7)：语音文件识别为文本，拆分章节，提炼关键信息，识别多人发言，适合处理录音采访、播客、会议记录等内容。
* [MinerU](https://github.com/opendatalab/MinerU/blob/master/README_zh-CN.md)：一站式、开源、高质量的数据提取工具，包含 PDF 文档、网页与电子书的内容提取并转换等 Markdown 等功能。[在线体验](https://opendatalab.com/OpenSourceTools/Extractor/PDF)
* [Elicit](https://elicit.com/)：以超人速度分析论文。自动化耗时的研究任务，如总结论文、提取数据和汇总结论。
* [Monica](https://monica.im/)：多功能 AI 工具箱，有浏览器插件、桌面应用和移动 App。最为人熟知的功能是基于网页内容的总结和问答。
* 剪映：可识别语音生成字幕。

### 定制知识库 / RAG

> RAG：Retrieval-Augmented Generation，检索增强生成。是目前基于 LLM 实现 “外挂知识库” 的主流技术方案。

* [SiteGPT](https://sitegpt.ai/)：基于你的官网内容和上传文档创建客服机器人，解答客户的咨询。
* [Dify](https://docs.dify.ai/v/zh-hans)：LLM 应用开发平台，支持各种大模型，提供 Prompt 编排、RAG、Agent 框架、工作流编排等功能。
* [RAGFlow](https://github.com/infiniflow/ragflow/blob/main/README_zh.md)：一款基于深度文档理解构建的开源 RAG 引擎。
* [MaxKB](https://github.com/1Panel-dev/MaxKB)：基于 LLM 大语言模型的知识库问答系统。开箱即用，支持快速嵌入到第三方业务系统。

### 广告 / 营销

* [AdIntelli](https://adintelli.ai/)：面向 GPTs 生态的广告联盟（可靠性待验证）。
* [GPT Wallets](https://gptwallets.co/)：为 GPTs 提供支付和数据分析解决方案。

### API 聚合平台

* [硅基流动](https://cmcm.link/p/siliconflow)：国内的 LLM API 聚合平台，提供 DeepSeek、Qwen 等系列模型的 API 服务。[相关攻略](https://mp.weixin.qq.com/s/UydlR9HVu2UYoBgtufMARg)
* [GitHub Models](https://github.com/marketplace/models)：GitHub 提供的免费 LLM API，包含 GPT-4o、Meta Llama 3、Cohere 等模型，调用频率有限制。[相关攻略](https://mp.weixin.qq.com/s/Jzytik-ZnhsG8pBRG8TU9Q)
* [API2D](https://cmcm.link/p/api2d)：提供 GPT 系列、Claude、嵌入、绘图等 API，高速稳定，支付便捷。
* [OpenRouter](https://openrouter.ai/)：提供 GPT、Claude、Gemini、Llama、Qwen 等系列模型的 API 服务。

### 其他工具 / 开源项目

* [Perplexity](https://www.perplexity.ai/)：AI 搜索。
* [秘塔 AI 搜索](https://metaso.cn/)：更友好的搜索引擎，帮你整理信息后更有条理地呈现。有 “全网” 和 “学术” 两种搜索模式，搜索深度可选简洁、深入、研究。
* [天工 AI](https://www.tiangong.cn/)：AI 搜索、对话助手等。
* [Devv.AI](https://devv.ai/)：一款面向程序员的 AI 搜索引擎，为编程问题提供快速准确的答案。
* [PromptPerfect](https://promptperfect.jina.ai/)：帮你优化提示词（Prompt）。比如把你的笼统需求拆解为多步骤的任务，以提高模型输出的准确性；又比如根据给定的文章主题生成大纲并撰写长文。
* [AppAgent](https://appagent-official.github.io/)：腾讯研究团队的开源项目，基于大语言模型的手机端多模态智能代理，帮用户自动执行复杂任务。适用于 Android 手机和模拟器。可粗略类比为手机端的按键精灵。
* [ProctorAI](https://github.com/jam3scampbell/ProctorAI)：AI 监工，号称 “拖延症终结者”。开源项目，本地应用程序，通过定时截图来检查你是否在摸鱼，并发出警告，支持语音提醒。可以设置详细的监督规则。底层调用了 GPT-4o 等多模态模型。
* [llm_aided_ocr](https://github.com/Dicklesworthstone/llm_aided_ocr)：LLM 辅助 OCR，通过大模型来提升 OCR 的准确性。

### 教程

* [提示工程指南](https://www.promptingguide.ai/zh)
* [通往 AGI 之路 / WayToAGI 的知识库](https://waytoagi.feishu.cn/wiki/QPe5w5g7UisbEkkow8XcDmOpn8e)

### 法规 / 公告

* [中华人民共和国人工智能法（学者建议稿）](https://mp.weixin.qq.com/s/Q98mzMXfISURS1vXsxqctg)
* 算法备案：
	* 境内深度合成服务算法备案清单：
		* [2023 年 6 月](https://www.cac.gov.cn/2023-06/20/c_1688910683316256.htm)
		* [2023 年 8 月](https://www.cac.gov.cn/2023-09/01/c_1695224377544009.htm)
		* [2024 年 1 月](https://www.cac.gov.cn/2024-01/05/c_1706119043746644.htm)
		* [2024 年 2 月](https://www.cac.gov.cn/2024-02/18/c_1709925427424332.htm)
		* [2024 年 4 月](https://www.cac.gov.cn/2024-04/11/c_1714509267496697.htm)
	* [互联网信息服务算法备案系统](https://beian.cac.gov.cn/#/index)

（持续更新中……）

---

## 常见问题 <a name="faq">&nbsp;</a>

### 有什么简便的方式可以使用 GPT-4 和 GPTs？ <a name="help">&nbsp;</a>

建议先通过 ChatGPT Plus 拼车账号开始体验，即买即用。解锁 GPT-4 + DALL·E 绘图 + GPTs 等高端功能。需自备海外线路。

这里推荐一个老牌的拼车平台，稳定可靠。[点此开始拼车](https://cmcm.link/p/gpt-plus)（还可用九五折优惠码 `ai2024`）。

### AI 生成内容的版权（著作权）属于谁？

简单说一下结论：

* 如果 AI 服务商的用户协议中主张了 AI 生成内容的著作权，则属于 AI 服务商。
* 否则属于使用 AI 服务生成内容的用户。

详细解释：[你用 AI 生成的作品，版权归你吗？](https://www.cssmagic.net/blog/wx/59)

### 微信群 <a name="wx-group">&nbsp;</a>

加入群，快人一步获取 AI 资讯、与数百名同好交流：

![qun-qr](https://github.com/cssmagic/blog/assets/1231359/356aedff-723a-4b5d-a776-c9cacdcebec8)

---

## License

* Text and graphics: © Creative Commons BY-NC-ND 4.0
* Code: GPLv3
