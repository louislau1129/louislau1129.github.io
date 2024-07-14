---
title: "Welcome to my 📕Blog world!"
collection: blog
permalink: /blog/outline
---
![welcome to blog world](/images/welcome_blog.png){: style="float: top; margin-bottom: 20px;"}

![blogs sharing knowledge among peoples](/images/blog_page.png){: style="float: right; width: 200px; margin-left: 20px;"}
Welcome to our blog page! Here, you will find a variety of insightful posts related to paper reading, research ideas, experiment insights, and technical details. We are dedicated to keeping this page updated with the latest information and encourage open communication and discussion. Join us as we explore the exciting world of research!
{: style="text-align: justify"}


### 👓 Technical Details
---

### 📄 Paper Reading
---

### 💎 Research Ideas
---
- LLM-based ASR [2024.06.01]

![sequence compression for llm-asr](/images/llm-asr-idea1.png){: style="margine-top: 20px; margine-bottom: 20px"}
------

a. alignment pretrain + info-preserve subsampling (lowres + qformer) for efficiency 
1. token resolution for asr from 20ms → 200ms →333ms →1s
2. **references:** mini-gemini (patch info mining) + GAMA multi-layer aggregator + VoCo-LLama + DeepStack (inject the high-res info without incresing the context length)

b. speaker-aware modeling\
c. contextual biasing aware training via prompt


### ⚙ Experimental Configs
---
- [Distributed Training Config](https://denim-fog-71c.notion.site/Distributed-Training-Config-4baa14a835424366a336c7edfd389815)  (Deepspeed vs DDP)