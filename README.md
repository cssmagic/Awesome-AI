# Awesome AI

收集分享 AI 大型语言模型 (LLM)、AI 辅助编程、AI 绘画等领域的常用资料，探索生成式人工智能的应用与开发。

> ### 目录
>
> * [大型语言模型](#llm)
> * [AI 辅助编程](#ai-assisted-programming)
> * [AI 绘画 / 音视频生成](#ai-painting)
> * [常用 AI 网站 / 工具](#ai-tool)
> * [常见问题](#faq)

> 🔍 提醒：善用搜索，按 Ctrl+F 或 ⌘F 定位到你想找的关键词。<br>
> 💡 持续更新中，建议添加到浏览器收藏夹，平常一定会用到。

## 大型语言模型 <a name="llm">&nbsp;</a>

### OpenAI GPT / ChatGPT <a name="gpt">&nbsp;</a>

* 简介：OpenAI 的 GPT-4 模型目前全球最先进的大型语言模型。GPT 的原义是 “生成式预训练变换器”。目前全球最火的 AI 应用产品 ChatGPT 就是基于 GPT 模型实现的。
* 官网：https://openai.com/gpt-4
* Playground：（不是免费的，会消耗你的 API 调用额度）
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
	* 相关教程：
		* [ChatGPT 定制化进阶：四步成为 AI 对话高手](https://www.cssmagic.net/blog/wx/60)
* Web 产品（GPTs）： <a name="gpts">&nbsp;</a>
	* 简介：GPTs 是 ChatGPT 的拓展。它允许用户针对特定场景定制一个特殊的对话机器人，甚至可以附加自己的知识库或调用外部 API，从而实现比常规 ChatGPT 更高效、更精准的对话效果。2024 年 1 月 GPTs 商店上线，开发者分成计划也呼之欲出。
	* GPTs 商店：https://chat.openai.com/gpts
	* 相关教程：
		* GPTs 完全指南：[入门篇](https://www.cssmagic.net/blog/wx/62) | [如何开发](https://www.cssmagic.net/blog/wx/63) | [如何上架](https://www.cssmagic.net/blog/wx/64) | [如何赚钱](https://www.cssmagic.net/blog/wx/65)
		* [GPTs 商店即将开张，坐等赚钱之际，别忘了做好防盗工作](https://www.cssmagic.net/blog/wx/58)
		* [任意 GPTs 资源文件泄露问题探讨](https://mp.weixin.qq.com/s/Bklnu0RhF8bnK1Irx14S5g)
		* [SecurityGPT：提示词安全防护](https://github.com/GPTGeeker/securityGPT)

### Claude

* 简介：Anthropic 公司发布的 AI 模型。最新版 Claude 3 在某些指标上已经超越 GPT-4。
* 官网：https://www.anthropic.com/claude
* Web 产品（Claude）：
	* 入口：https://claude.ai/ （需要验证海外手机号）
	* 定价：有免费版。专业版套餐 $20 / 月。

### Google Gemini <a name="gemini">&nbsp;</a>

* 简介：Google 开发的原生多模态大模型。根据模型规模分为 Ultra、Pro、Nano 三个版本。Ultra 版宣称在多项测评中击败 GPT-4；Pro 1.0 版本于 2023 年 12 月开放免费 API。2024 年 2 月发布 Pro 1.5，需要排队申请。2024 年 2 月通过 [Advanced 付费套餐](https://gemini.google.com/advanced) 开放 Ultra 1.0 的 Web 访问。
* 官网：https://ai.google.dev/
* Playground：
	* Google AI Studio：https://makersuite.google.com/
	* Vertex AI Studio：https://console.cloud.google.com/vertex-ai/generative/multimodal/create/text
* API 文档：https://ai.google.dev/tutorials/rest_quickstart
* Web 产品（原 Bard 已更名为 Gemini）：https://gemini.google.com/app
	* 定价：
		* Gemini Free（Pro 1.0）：免费
		* Gemini Advanced（Ultra 1.0）：$19.99 / 月
* 更多介绍：
	* [这几天刷屏的谷歌 Gemini 大模型又放出免费 API，压力给到奥特曼](https://www.cssmagic.net/blog/wx/55)

### 百度文心大模型 / 文心一言 <a name="wenxinyiyan">&nbsp;</a>

* 简介：文心一言是由百度公司开发的聊天机器人，于 2023 年 3 月 16 日发布。文心一言由文心大模型驱动。
* 官网：https://wenxin.baidu.com/
* API 文档：https://cloud.baidu.com/doc/WENXINWORKSHOP/s/clntwmv7t
* Web 产品（文心一言）：https://yiyan.baidu.com/
	* 定价：
		* 非会员（文心大模型 3.5 + 2000 字输入 + 图片 512x512 + ...）：免费
		* 会员（文心大模型 4.0 + 5000 字输入 + 图片 1024x1024 + ...）：¥59.9 / 月
* Web 产品（飞桨 AI 应用中心）：https://aistudio.baidu.com/application/center

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


### 更多

* 更多国产大模型：
	* [零一万物 / Yi](https://www.lingyiwanwu.com/)：国产开源多模态大模型。30 万字超长上下文。已开放 API。
		* API 文档：https://platform.lingyiwanwu.com/
	* [讯飞星火认知大模型](https://xinghuo.xfyun.cn/)：
		* API 文档：https://www.xfyun.cn/doc/spark/Web.html
		* Web 产品（SparkDesk）：https://xinghuo.xfyun.cn/desk
	* [MiniMax](https://api.minimax.chat/)
		* API 文档：https://api.minimax.chat/document/introduction?id=6433f37594878d408fc82959
	* 开源的中文大型语言模型：https://github.com/HqWu-HITCS/Awesome-Chinese-LLM
* 图片识别 API：
	* GPT-4V：https://platform.openai.com/docs/guides/vision
	* Gemini Pro Vision：https://ai.google.dev/tutorials/rest_quickstart#text-and-image_input



## AI 辅助编程 <a name="ai-assisted-programming">&nbsp;</a>

### GitHub Copilot <a name="gitub-copilot">&nbsp;</a>

* 简介：AI 辅助编程领域的标杆。由 GitHub 和 OpenAI 共同开发，作为编辑器插件集成到开发环境中，支持 VS Code 和 JetBrains IDE 等主流开发工具。通过提供代码建议和自动补全功能，Copilot 能够提高编程效率。此外，它还集成了生成单测、生成注释、转译代码、回答问题等功能。
* 官网：https://github.com/features/copilot
* 定价：个人版：$10 / 月（第一个月免费试用）

### Cursor / Copilot++

* 简介：AI 辅助编程领域的后起之秀。Cursor 是一款编辑器，基于 VS Code 内核，集成了 AI 辅助编程和基于当前代码仓库的 AI 问答功能。相对于其他 AI 辅助编程工具，Cursor 可以执行指令修改代码，而不仅仅是生成新代码。Copilot++ 是其付费功能，可以预测用户的下一步操作并提供代码修改建议。
* 官网：https://cursor.sh/
* 定价：https://cursor.sh/pricing
	* 基础版（基础功能 + 有限的问答次数）：免费
	* 专业版（无限的问答次数 + Copilot++）：$20 / 月
	* ...

### CodeGeeX <a name="codegeex">&nbsp;</a>

* 简介：智谱旗下的一款基于大模型的全能的智能编程助手。支持 20 多种编程语言，适配 VS Code 和 JetBrains IDE 等主流开发工具。它可以实现代码的生成与补全、自动添加注释、代码翻译以及智能问答等功能。面向企业提供私有化部署服务。
* 官网：https://codegeex.cn/
* 定价：CodeGeeX 插件对个人用户完全免费。

### 其他

* [Codeium](https://codeium.com/)：编辑器插件，支持 VS Code 和 JetBrains IDE 等。
	* 定价：个人版（代码建议 + 对话）：免费
* [Tabnine](https://www.tabnine.com/)：编辑器插件，支持 VS Code 和 JetBrains IDE 等。
	* 定价：基础版（基础的代码补全功能）：免费
* [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/)：编辑器插件，支持 VS Code 和 JetBrains IDE 等。
	* 定价：个人版（代码建议 + 参考跟踪 + 安全扫描）：免费
* [通义灵码](https://tongyi.aliyun.com/lingma)：编辑器插件，支持 VS Code 和 JetBrains IDE 等。
	* 定价：个人版：免费


## AI 绘画 / 音视频生成 <a name="ai-painting">&nbsp;</a>

### Midjourney <a name="midjourney">&nbsp;</a>

* 简介：Midjourney 是一款热门的 AI 绘画工具，依托 Discord 平台提供服务。它易于入门，作品风格华丽，适合初学者探索 AI 艺术创作，创造独特的视觉作品。
* 官网：https://www.midjourney.com/home
* 定价：
	* 基础版套餐（3.3h Fast Time）：$10 / 月
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

### Google Imagen 2

* 简介：Google DeepMind 推出的图片生成模型。免费使用。据说效果媲美 DALL·E。
* 官网：https://deepmind.google/technologies/imagen-2/
* Web 产品（ImageFX）：https://aitestkitchen.withgoogle.com/tools/image-fx

### Runway Gen-2

* 简介：视频生成领域的热门产品。它提供了多种 AI 视频生成模型，包括文生视频、图文生成视频、图生视频、风格化渲染、局部叠加渲染、3D 模型渲染等功能。
* 官网：https://research.runwayml.com/gen2
* Web 产品：https://app.runwayml.com/
* 定价：
	* 免费版（125 积分）：免费
	* 标准版（625 积分 / 月）：$15 / 月
	* ...

### Pika

* 简介：视频生成领域的热门产品。典型功能为图生视频。
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

### OpenAI Sora

* 简介：OpenAI 发布的视频生成模型。可实现文生视频、图生视频、视频延长和衔接。生成视频长达一分钟。目前仅面向安全领域和创作领域的专家开放内测，还没有正式开放。
* 官网：https://openai.com/sora
* 更多介绍：
	* [Sora 官网摘要：OpenAI 的视频生成模型 Sora 被捧上天，但他们自己说还有这几个缺陷](https://www.cssmagic.net/blog/wx/66)

### 剪映专业版 / CapCut

* 简介：字节跳动出品的视频编辑工具，支持 Windows/Mac。它集成了大量基于 AI 技术的音视频处理功能，比如生成字幕、生成配音、降噪、变声、数字人、文生视频等等。
* 官网（国内版）：https://www.capcut.cn/
* 官网（海外版）：https://www.capcut.com/ （免充值享高级功能）

### 3D 建模

* [Zero-1-to-3 (zero123)](https://github.com/cvlab-columbia/zero123): Zero-shot 单张图片生成 3D 物体。哥伦比亚大学的开源项目。
* [One-2-3-45](http://one-2-3-45.com/)：“Any Single Image to 3D Mesh in 45 Seconds without Per-Shape Optimization”。开源项目。
* [Wonder3D](https://www.xxlong.site/Wonder3D/)：“Wonder3D produces consistent multi-view normal maps and correpsonding color images, and thus reconstructs high-fidelity textured mesh from a single image in only 2~3 minutes”。开源项目。
* [Stable Zero123](https://stability.ai/stable-3d)：单张图片生成高质量 3D 物体。Stability AI 开源模型，可整合到 ComfyUI 工作流。
* [DreamGaussian](https://dreamgaussian.github.io/)：Generative Gaussian Splatting for Efficient 3D Content Creation。开源项目。
* [Tripo AI](https://vectorizer.ai/)：通过文本或图片生成高质量 3D 模型，可下载。有免费配额。

### 数字人 / 语音驱动视频

* [万兴播爆](https://virbo.wondershare.cn/)：输入文案，一键生成数字人播报视频。
* 剪映：可生成数字人播报视频。
* [HeyGen](https://www.heygen.com/)：生成数字人播报视频，视频翻译，语音克隆。
* [EMO](https://humanaigc.github.io/emote-portrait-alive/)：阿里发布的（图片 + 音频 → 视频）大模型，生成的人物嘴形和表情相当自然。

### 在线 SD 绘画

* [Leonardo.Ai](https://leonardo.ai/)：易用且强大的 AI 绘图平台，底层基于 SD，深度集成 SD 各种插件，提供训练好的模型，可训练模型。有免费配额。
* [eSheep 电子羊](https://www.esheep.com/)：体验在线的 WebUI 和 ComfyUI。新用户获得 100 积分。每 100 积分相当于 ¥1。
* [网易 AI 设计工坊](https://sd.study.163.com/)：在线 WebUI，可训练模型。有免费配额，每天 10 次。
* [LibLib AI](https://www.liblib.art/)：在线 WebUI，可训练模型。有免费配额，每天 300 积分。
* [Cephalon Cloud 端脑云](https://cephalon.cloud/#/share/register-landing?id=Hf7YkG)：云端一键部署自己的 WebUI 和 ComfyUI。新用户获得 2000 积分。每 1000 积分相当于 ¥1。
* [Dreamina](https://www.capcut.cn/ai-tool/platform)：字节跳动出品的在线绘画平台，主打易用和免费。

### 作曲

* [Suno](https://app.suno.ai/)：AI 根据你的要求生成歌曲（作词、作曲、演唱）。

（持续更新中……）


## 常用 AI 网站 / 工具 <a name="ai-tool">&nbsp;</a>

### 综合平台

* [POE](https://poe.com/)：各种知名模型的聚合平台。用户可根据自己的需求通过 Prompt 定制对话机器人，相当于 GPTs 平替。付费用户可无限量使用 GPT-4、Claude 2 等高端模型。
* [FlowGPT](https://flowgpt.com/)：一个 Prompt 分享平台。提供了角色聊天、游戏、创意、生产力等各种类型的对话机器人，是一个学习提示词的好地方。也可以把它当作 GPTs 平替。
* [Character.AI](https://beta.character.ai/)：与各种类型的 AI 虚拟角色对话，包括世界名人、动漫人物、游戏角色等。
* Coze：字节跳动面向海外市场推出的 AI 聊天机器人及 AI 应用开发平台。无论是否具备编程基础，用户都可以快速构建特定功能的聊天机器人，并发布到海外各大社交平台。网友发现，在该平台可以免费使用 GPT-4 和 DALL·E 3。
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
	* 知识库：https://waytoagi.feishu.cn/wiki/QPe5w5g7UisbEkkow8XcDmOpn8e

### 图像处理 / 图形设计 / UI 设计

* [Vectorizer.AI](https://vectorizer.ai/)：基于 AI 的位图转适量图的在线工具。免费。
* [Galileo](https://www.usegalileo.ai/)：通过提示词生成 UI 设计稿，可导出到 Figma。
	* 定价：https://www.usegalileo.ai/pricing
		* 免费版（注册后获得 200 积分 + 3 次导出）：免费
		* 标准版（每月 1200 积分 + 无限导出）：$19 / 月
		* 专业版（每月 3000 积分 + 无限导出 + 私密模式）：$39 / 月
* [Magnific AI](https://magnific.ai/)：图片放大，增强细节。
* 抠图：
	* [四款免费的 AI 抠图工具，最后一个不敢相信！](https://www.cssmagic.net/blog/wx/56)

### 写作

* [Notion AI](https://www.notion.so/product/ai)：Notion 中的 AI 写作助手。增值服务，每月 $10。
* [蛙蛙写作](https://www.wawawriter.com/)：国产写作模型，写长篇小说、视频脚本、论文等。免费试用 3000 字。


### 内容分析、识别、提炼

* [通义听悟](https://tingwu.aliyun.com/u/82xz94v6z6z9m6v7)：语音文件识别为文本，拆分章节，提炼关键信息，识别多人发言，适合处理录间采访、博客、会议记录等内容。
* [万知](https://www.wanzhi01.com/)：长文总结要点、文档生成 PPT 等。
* 剪映：可识别语音生成字幕。


### 定制知识库 / RAG

* [SiteGPT](https://sitegpt.ai/)：基于你的官网内容和上传文档创建客服机器人，解答客户的咨询。
* [Dify](https://docs.dify.ai/v/zh-hans)：LLM 应用开发平台，支持各种大模型，提供 Prompt 编排、RAG、Agent 框架等功能。

### 广告 / 营销

* [AdIntelli](https://adintelli.ai/)：面向 GPTs 生态的广告联盟（可靠性待验证）。

### 其他工具 / 开源项目

* [秘塔AI搜索](https://metaso.cn/)：更友好的搜索引擎，帮你整理信息后更有条理地呈现。有 “全网” 和 “学术” 两种搜索模式，搜索深度可选简洁、深入、研究。
* [PromptPerfect](https://promptperfect.jina.ai/)：帮你优化提示词（Prompt）。比如把你的笼统需求拆解为多步骤的任务，以提高模型输出的准确性；又比如根据给定的文章主题生成大纲并撰写长文。
* [AppAgent](https://appagent-official.github.io/)：腾讯研究团队的开源项目，基于大语言模型的手机端多模态智能代理，帮用户自动执行复杂任务。适用于 Android 手机和模拟器。可粗略类比为手机端的按键精灵。

### 法规 / 公告

* [中华人民共和国人工智能法（学者建议稿）](https://mp.weixin.qq.com/s/Q98mzMXfISURS1vXsxqctg)
* 境内深度合成服务算法备案清单：
	* [2023 年 6 月](https://www.cac.gov.cn/2023-06/20/c_1688910683316256.htm)
	* [2023 年 8 月](https://www.cac.gov.cn/2023-09/01/c_1695224377544009.htm)
	* [2024 年 1 月](https://www.cac.gov.cn/2024-01/05/c_1706119043746644.htm)
	* [2024 年 2 月](https://www.cac.gov.cn/2024-02/18/c_1709925427424332.htm)


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
