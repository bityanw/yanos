- 1.我们在提示工程的优势
- ![Image.png](../assets/Image_1711033006087_0.png)
- 2.提示模拟器
- 3.Prompt调优
- 不知道训练数据怎么办？
- 3.1 问他
- OpenAI GPT对markdown格式更友好，
- 官方Prompt Engineering教程，示例
- 3.2 试是常用方法，有运气因素，所以门槛低，天花板高
- 高质量prompt核心要点：
- **具体、丰富、少歧义**
- **群聊天习惯全是短句，口语，歧义**
- **群发邮件是习惯**
- **篇篇都是小作文**
- **发出的每一条消息都是prompt，锻炼能力,Prompt写的好的人，沟通能力提升了**
-
- ![Image.png](../assets/Image_1711033035734_0.png)
- **大模型对开头和结尾内容更敏感**
-
- ![Image.png](../assets/Image_1711033064087_0.png)
-
- **给例子最好**
- **增加约束，提示词NO COMMENTS. NO ACKNOWLEDGEMENTS.**
- **用例子实现统一口径；**
- **大模型没有记忆，4k个token，历史对话留多少**
- **我们发给大模型的prompt，不会改变大模型的参数；**
- **若把对话历史训练大模型，就会改变；**
- **用代码更可控，纯OpenAI方案更方便，更省钱**
- **思维****链****：Let's think step by step.**
- **投票方式：自洽型；**
- **思维树****：**
-
- ![Image.png](../assets/Image_1711033090698_0.png)
-
- **例子+思维链+找相关度高的例子+多次跑比较**
- **奶奶漏洞，如何防范**
- **系统的固有提示**
- **给他刷价值观**
-
- ![Image.png](../assets/Image_1711033105448_0.png)
-
- ![Image.png](../assets/Image_1711033111656_0.png)
-
- **Chat API是主流**
- **temperature=1,          # 生成结果的多样性 0~2之间，越大越随机，越小越固定**
- **        seed=None,              # 随机数种子。指定具体值后，temperature 为 0 时，每次生成的结果都一样**
- **        stream=False,           # 数据流模式，一个字一个字地接收**
- **        top_p=1,                # 随机采样时，只考虑概率前百分之多少的 token。不建议和 temperature 一起使用**
- **        n=1,                    # 一次返回 n 条结果**
- **        max_tokens=100,         # 每条结果最多几个 token（超过截断）**
- **        presence_penalty=0,     # 对出现过的 token 的概率进行降权**
- **        frequency_penalty=0,    # 对出现过的 token 根据其出现过的频次，对其的概率进行降权**
- **        logit_bias={},          # 对指定 token 的采样概率手工加/降权，不常用**
-
- ![Image.png](../assets/Image_1711033132607_0.png)
- **用prompt调试prompt**
- ```
  
  1. I want you to become my Expert Prompt Creator. Your goal is to help me craft the best possible prompt for my needs. The prompt you provide should be written from the perspective of me making the request to ChatGPT. Consider in your prompt creation that this prompt will be entered into an interface for ChatGpT. The process is as follows:1. You will generate the following sections:
  
  Prompt: {provide the best possible prompt according to my request)
  Critique: {provide a concise paragraph on how to improve the prompt. Be very critical in your response}
  Questions:
  {ask any questions pertaining to what additional information is needed from me toimprove the prompt (max of 3). lf the prompt needs more clarification or details incertain areas, ask questions to get more information to include in the prompt}
  
  2. I will provide my answers to your response which you will then incorporate into your next response using the same format. We will continue this iterative process with me providing additional information to you and you updating the prompt until the prompt is perfected.Remember, the prompt we are creating should be written from the perspective of me making a request to ChatGPT. Think carefully and use your imagination to create an amazing prompt for me.
  You're first response should only be a greeting to the user and to ask what the prompt should be about
  
  ```
-
- **先用** GPTs ([https://chat.openai.com/gpts/discovery](https://chat.openai.com/gpts/discovery)) 扩写
- **扩写后的****遗传算法，**