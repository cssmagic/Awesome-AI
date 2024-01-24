# Awesome AI

收集分享 AI 大语言模型 (LLM)、AI 辅助编程、AI 绘画等领域的常用资料，探索生成式 AI 的应用与开发。

> ### 目录
>
> * [大语言模型](#llm)
> * [AI 辅助编程](#ai-assisted-programming)
> * [AI 绘画 / 音视频生成](#ai-painting)
> * [常用 AI 网站 / 工具](#ai-tool)
> * [常见问题](#faq)

> 🔍 提醒：善用搜索，按 Ctrl+F 或 ⌘F 定位到你想找的关键词。
> 💡 持续更新中，建议添加到浏览器收藏夹，平常一定会用到。

## 大语言模型 <a name="llm">&nbsp;</a>

### OpenAI GPT / ChatGPT <a name="gpt">&nbsp;</a>

* 简介：OpenAI 的 GPT-4 模型目前全球最先进的大语言模型。GPT 的原义是 “生成式预训练变换器”。目前全球最火的 AI 应用产品 ChatGPT 就是基于 GPT 模型实现的。
* 官网：https://openai.com/gpt-4
* Playground：
	* Chat 模式：https://platform.openai.com/playground?mode=chat
	* Assistants 模式：https://platform.openai.com/playground?mode=assistant
* API 定价：https://openai.com/pricing
* API 文档：https://platform.openai.com/docs/overview
* Web 产品（ChatGPT）： <a name="chatgpt">&nbsp;</a>
	* 简介：ChatGPT 是目前全球最热门的 AI 应用产品，是一款能以自然语言对话进行交互的 AI 助手。除了对话之外，它还集成了绘画、代码解释器等功能。2022 年 11 月 30 日上线，2023 年 11 月推出 GPTs（自定义 ChatGPT），2024 年 1 月推出 GPTs 商店，持续引领 AI 领域的热潮。
	* 官网：https://openai.com/chatgpt
	* 入口：https://chat.openai.com/
	* 定价：
		* ChatGPT Free（GPT-3.5 + 语音对话）：免费无限量
		* ChatGPT Plus（Free + GPT-4 + 绘图 + GPTs + ...）：$20 / 月
		* ChatGPT Team（Plus + 协作空间 + 数据保护 + ...）：$25 / 月 / 人
* Web 产品（GPTs）： <a name="gpts">&nbsp;</a>
	* 简介：GPTs 是 ChatGPT 的拓展。它允许用户针对特定场景定制一个特殊的对话机器人，甚至可以附加自己的知识库或调用外部 API，从而实现比常规 ChatGPT 更高效、更精准的对话效果。2024 年 1 月 GPTs 商店上线，开发者分成计划也呼之欲出。
	* GPTs 商店：https://chat.openai.com/gpts
	* 更多介绍：
		* https://www.cssmagic.net/blog/wx/58

### 百度文心大模型 / 文心一言 <a name="wenxinyiyan">&nbsp;</a>

* 简介：文心一言是由百度公司开发的聊天机器人，于 2023 年 3 月 16 日发布。文心一言由文心大模型驱动，具备理解、生成、逻辑、记忆四大基础能力。文心大模型最新版是 4.0。
* 官网：https://wenxin.baidu.com/
* API 文档：https://cloud.baidu.com/doc/WENXINWORKSHOP/s/clntwmv7t
* Web 产品（文心一言）：https://yiyan.baidu.com/
	* 定价：
		* 非会员（文心大模型 3.5 + 2000 字输入 + 图片 512x512 + ...）：免费
		* 会员（文心大模型 4.0 + 5000 字输入 + 图片 1024x1024 + ...）：¥59.9 / 月
* Web 产品（飞桨 AI 应用中心）：https://aistudio.baidu.com/application/center

### Google Gemini <a name="gemini">&nbsp;</a>

* 简介：Google 开发的原生多模态大模型。根据模型规模分为 Ultra、Pro、Nano 三个版本。Ultra 版宣称在多项测评中击败 GPT-4；Pro 版本已于 2023 年 12 月开放免费 API。
* 官网：https://ai.google.dev/
* Playground：
	* Google AI Studio：https://makersuite.google.com/
	* Vertex AI Studio：https://console.cloud.google.com/vertex-ai/generative/multimodal/create/text
* API 文档：https://ai.google.dev/tutorials/rest_quickstart
* 更多介绍：
	* https://www.cssmagic.net/blog/wx/55

### 智谱 GLM / ChatGLM <a name="chatglm">&nbsp;</a>

* 官网：https://models.aminer.cn/glm-130b/
* API 文档：https://open.bigmodel.cn/dev/api
* Web 产品（智谱清言）：https://chatglm.cn/main/detail

### 讯飞星火认知大模型

* 官网：https://xinghuo.xfyun.cn/
* API 文档：https://www.xfyun.cn/doc/spark/Web.html
* Web 产品（SparkDesk）：https://xinghuo.xfyun.cn/desk

### MiniMax

* 官网：https://api.minimax.chat/
* API 文档：https://api.minimax.chat/document/introduction?id=6433f37594878d408fc82959

### 更多

* 开源的中文大语言模型：https://github.com/HqWu-HITCS/Awesome-Chinese-LLM
* 图片识别 API：
	* GPT-4V：https://platform.openai.com/docs/guides/vision
	* Gemini Pro Vision：https://ai.google.dev/tutorials/rest_quickstart#text-and-image_input



## AI 辅助编程 <a name="ai-assisted-programming">&nbsp;</a>

### GitHub Copilot <a name="gitub-copilot">&nbsp;</a>

* 简介：一款由 GitHub 和 OpenAI 共同开发的 AI 编程助手，作为编辑器插件集成到开发环境中。通过提供代码建议和自动补全功能，Copilot 能够提高编程效率。此外，它还集成了生成单测、生成注释、转译代码、回答问题等功能。
* 官网：https://github.com/features/copilot
* 定价：个人版：$10 / 月（第一个月免费试用）

### CodeGeeX <a name="codegeex">&nbsp;</a>

* 简介：智谱旗下的一款基于大模型的全能的智能编程助手支持 20 多种编程语言，适配 VS Code 和 JetBrains IDE 等主流开发工具。它可以实现代码的生成与补全、自动添加注释、代码翻译以及智能问答等功能。面向企业提供私有化部署服务。
* 官网：https://codegeex.cn/
* 定价：CodeGeeX 插件对个人用户完全免费。

### Tabnine

* 官网：https://www.tabnine.com/
* 定价：基础版（基础的代码补全功能）：免费

### Amazon CodeWhisperer

* 官网：https://aws.amazon.com/codewhisperer/
* 定价：个人版（代码建议 + 参考跟踪 + 安全扫描）：免费



## AI 绘画 / 音视频生成 <a name="ai-painting">&nbsp;</a>

### Midjourney <a name="midjourney">&nbsp;</a>

* 简介：Midjourney 是一款热门的 AI 绘画工具，依托 Discord 平台提供服务。它易于入门，作品风格华丽，适合初学者探索 AI 艺术创作，创造独特的视觉作品。
* 官网：https://www.midjourney.com/home
* 定价：
	* 基础版套餐（3.3h Fast）：$10 / 月
	* 标准版套餐（15h Fast Time + Unlimited Relax Time）：$30 / 月
	* 专业版套餐（30h Fast Time + Unlimited Relax Time）：$60 / 月
	* 至尊版套餐（60h Fast Time + Unlimited Relax Time）：$120 / 月

### OpenAI DALL·E <a name="dall-e">&nbsp;</a>

* 简介：OpenAI 出品的图片生成工具。对提示词的理解能力极强，与 ChatGPT 的整合也令它极为易用。
* 官网：https://openai.com/dall-e-3
* Web 产品：
	* ChatGPT Plus（GPT-4 + DALL·E 3）：https://chat.openai.com/#pricing
		* 定价：$20 / 月
	* DALL·E 2：https://labs.openai.com/
		* 定价：$15 / 115 点

### Stable Diffusion <a name="sd">&nbsp;</a>

* 简介：Stable Diffusion 是一款先进的人工智能图像生成模型，由 Stability AI 开发。可本地部署。因其开源特性，发展迅速，已经成长为一个庞大的生态，广泛应用于艺术创作、设计和多媒体制作等领域。
* 官网：https://stability.ai/stable-image
* 扩展：
	* ComfyUI：https://github.com/comfyanonymous/ComfyUI
		* 中文学习社区：https://www.comflowy.com/zh-CN

### Runway Gen-2

* 简介：视频生成领域的热门产品。它提供了多种 AI 视频生成模型，包括文生视频、图文生成视频、图生视频、风格化渲染、局部叠加渲染、3D 模型渲染等功能。
* 官网：https://research.runwayml.com/gen2
* Web 产品：https://app.runwayml.com/
* 定价：
	* 免费版（125 积分）：免费
	* 标准版（625 积分 / 月）：$15 / 月
	* ...

### Pika

* 简介：视频生成领域的热门产品。
* 官网：https://pika.art/
* 定价：
	* 免费版（30 积分）：免费
	* 标准版（700 积分 / 月）：$10 / 月
	* ...

### PixVerse

* 简介：目前免费的视频生成工具，效果媲美 Runway 和 Pika。
* 官网：https://pixverse.ai/

### Stable Video Diffusion

* 简介：Stability AI 发布的开源的视频生成模型。可本地部署。
* 官网：https://stability.ai/stable-video
* 更多介绍：
	* 简介：https://mp.weixin.qq.com/s/il3YahMQyw55KdQ7acxIow
	* 教程：https://huggingface.co/docs/diffusers/main/en/using-diffusers/svd

### 剪映专业版 / CapCut

* 简介：字节跳动出品的视频编辑工具，支持 Windows/Mac。它集成了大量基于 AI 技术的音视频处理功能，比如生成字幕、生成配音、降噪、变声、数字人、文生视频等等。
* 官网：
	* 国内版：https://www.capcut.cn/
	* 海外版：https://www.capcut.com/ （免充值享高级功能）

（持续更新中……）


## 常用 AI 网站 / 工具 <a name="ai-tool">&nbsp;</a>

### 综合平台

* POE <a name="poe">&nbsp;</a>
	* 简介：各种知名模型的聚合平台。用户可根据自己的需求通过 Prompt 定制对话机器人，相当于 GPTs 平替。付费用户可无限量使用 GPT-4、Claude 2 等高端模型。
	* 官网：https://poe.com/
* FlowGPT <a name="flowgpt">&nbsp;</a>
	* 简介：一个 Prompt 分享平台。提供了角色聊天、游戏、创意、生产力等各种类型的对话机器人，是一个学习提示词的好地方。也可以把它当作 GPTs 平替。
	* 官网：https://flowgpt.com/
* Character.AI
	* 简介：与各种类型的 AI 虚拟角色对话，包括世界名人、动漫人物、游戏角色等。
	* 官网：https://beta.character.ai/

### 图像处理

（持续更新中……）


### 写作

（持续更新中……）


### 内容分析、识别、提炼

* 通义听悟 <a name="tingwu">&nbsp;</a>
	* 简介：语音文件识别为文本，拆分章节，提炼关键信息，识别多人发言，适合处理录间采访、博客、会议记录等内容。
	* 平台：
		* 网站：[tingwu.aliyun.com](https://tingwu.aliyun.com/u/82xz94v6z6z9m6v7)
		* 微信小程序：(TODO)

（持续更新中……）

---

## 常见问题 <a name="faq">&nbsp;</a>

### AI 生成内容的版权（著作权）属于谁？

简单说一下结论：

* 如果 AI 服务商的用户协议中主张了 AI 生成内容的著作权，则属于 AI 服务商。
* 否则属于使用 AI 服务生成内容的用户。

详细的解释稍后补充吧。

### 有什么简便的方式可以使用 GPT-4 和 GPTs？ <a name="help">&nbsp;</a>

建议先通过 ChatGPT Plus 拼车账号开始体验，即买即用。解锁 GPT-4 + DALL·E 绘图 + GPTs 等高端功能。需自备海外线路。

这里推荐一个老牌的拼车平台，稳定可靠。[点此开始拼车](https://cmcm.link/p/gpt-plus)（还可用九五折优惠码 `ai2024`）。

### 微信群 <a name="wx-group">&nbsp;</a>

加入群，快人一步获取 AI 资讯、与数百名同好交流：

![qun-qr](https://github.com/cssmagic/blog/assets/1231359/356aedff-723a-4b5d-a776-c9cacdcebec8)

---

## License

* Text and graphics: © Creative Commons BY-NC-ND 4.0
* Code: GPLv3
