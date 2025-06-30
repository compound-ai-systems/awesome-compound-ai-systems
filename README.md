# Awesome Compound AI Systems

> A curated list of awesome [Compound AI Systems](https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/)

## 🎓 Research Systems / Academic Results 
🏆 _denotes systems that improve the state-of-the-art_

* **[WangLab](https://www.wanglab.ai/)'s winning entries to the 2024 MEDIQA Clinical NLP competition** - 🏆  
_outperforms next runner-up by over 19%_  
📢 https://x.com/lateinteraction/status/1783990747257360779  
by [@augustintoma](https://github.com/augustintoma) et al.  

* **[FrugalGPT](https://github.com/stanford-futuredata/FrugalGPT), strategies for combining multiple LLMs to save money, but keep SOTA accuracy** - 🏆  
_reached the same accuracy as GPT-4 at a cost reduction of 59-98%_  
📢 https://x.com/james_y_zou/status/1656285537185980417  
📰 https://portkey.ai/blog/implementing-frugalgpt-smarter-llm-usage-for-lower-costs/  
📖 https://arxiv.org/pdf/2305.05176.pdf  
by [@lchen001](https://github.com/lchen001) et al.  
_Components:_ many different LLMs

* **[Are More LLM Calls All You Need](https://arxiv.org/abs/2403.02419), discerning scaling dynamics governing how many calls to make in ensemble-based Compound AI Systems** - 🏆
  _discovered non-monotonic dynamics in quality improvement as you scale the number of ensemble members (or calls). Attributes this to **query difficulty** variance_
  📢 [https://x.com/ChenLingjiao/status/1798849142288245071](https://x.com/ChenLingjiao/status/1798849142288245071)
  📖 [https://arxiv.org/pdf/2305.05176.pdf](https://arxiv.org/abs/2403.02419)
  _Components:_ many calls to an LLM, where the number of calls (and the mix of LLMs) is parameterizable

* **[AlphaGeometry](https://github.com/google-deepmind/alphageometry), iteratively suggests constructions in a geometry problem via LLM and checks deduced facts produced by symbolic engine** - 🏆  
_scores between silver and gold International Math Olympiad medalists_  
📢 https://x.com/GoogleDeepMind/status/1747651817461125352  
📰 https://deepmind.google/discover/blog/alphageometry-an-olympiad-level-ai-system-for-geometry/  
📖 https://www.nature.com/articles/s41586-023-06747-5  
by [@thtrieu](https://github.com/thtrieu) et al.  
_Components:_ fine-tuned LLM; symbolic math engine

* **[InferCept](https://github.com/WukLab/InferCept), a high-throughput serving system for augmented LLMs** - 🏆  
_serves 1.6x-2x more requests than vLLM at the same low latency_  
📢 https://x.com/yiying__zhang/status/1797495152979898835  
📰 https://mlsys.wuklab.io/posts/infercept/  
📖 https://arxiv.org/pdf/2402.01869  
by [@reyna-abhyankar](https://github.com/reyna-abhyankar) et al.  
_Components:_ augmented LLM serving

* **[Cognify](https://github.com/GenseeAI/cognify/), an automated multi-faceted optimizer for compound AI systems** - 🏆  
_improves quality of compound AI systems by up to 48% and reduces cost by up to 9x_  
📢 https://x.com/yiying__zhang/status/1861222646408503374  
📰 https://mlsys.wuklab.io/posts/cognify/  
by [@gensee-ai](https://www.gensee.ai/)
_Components:_ compound AI optimization

* Help us by adding more entries here!

## 🏭 Products / Real-world Systems
🟢 _denotes publicly available product_  
🟡 _denotes announced but currently unreleased product_  
🔴 _denotes an internal system not available to the public_

* **ChatGPT Plus** - 🟢  
_The paid ChatGPT offering by OpenAI which supports external web browsing, and other plugins_  
🔗 https://openai.com/chatgpt/pricing  
by [@openai](https://github.com/openai)  
_Components:_ LLM; web Browser plugin for retrieving timely content; code interpreter plugin for executing python; DALL-E image generator 

* **Microsoft Copilot (formerly Bing Chat)** - 🟢  
_The ad-supported/paid chatbot offering from Microsoft which supports external web browsing, image generation, and more_  
🔗 https://www.microsoft.com/en-us/store/b/copilotpro  
by [@microsoft](https://github.com/microsoft)  
_Components:_ LLM; web Browser plugin for retrieving timely content; code interpreter plugin for executing python; image generator 

* **Replit Code Repair** - 🟡  
_An in-development product at Replit aimed at automatically suggesting patches for codebases based on detected language-server protocol (LSP) error events_  
📢 https://blog.replit.com/code-repair  
by [@replit](https://github.com/replit)  
_Components:_ LLM with a few-shot prompt pipeline (DSPy); supervised fine-tuning 

* Help us by adding more entries here!

<br />


# Working list of known Compound AI Systems
_We are migrating these systems to the top portion of the document! ⌛_

## 2014
* [Learning Deep Structured Models](https://arxiv.org/pdf/1407.2538)

## 2017
* [DrQA*](https://arxiv.org/abs/1704.00051)

## 2019
* [GoldEn](https://arxiv.org/abs/1910.07000)
* [DecompRC](https://arxiv.org/abs/1906.02916)
* ORQA
* Learning to Retrieve Reasoning Paths over Wikipedia Graph

## 2020
* REALM
* DPR
* ColBERT*
* RAG
* ColBERT-QA
* IRRR

## 2021
* Baleen
* Hindsight

## 2022
* MRKL
* LM Cascades
* RARR
* Self-Ask
* ReAct
* IRCoT
* Demonstrate-Search-Predict

## 2023
* DIN-SQL
* Reflexion
* DSPy
* FrugalGPT ✅
* AlphaCode 2

## 2024
* IReRa
* AlphaCodium
* DSPy Assertions
* STORM
* HaizeLab Red Teaming with DSPy
* WangLab at MEDIQA with DSPy ✅
* Gemini
* [Replit Code Repair](https://blog.replit.com/code-repair)
* InferCept ✅
* AlphaGeometry ✅
* Cognify