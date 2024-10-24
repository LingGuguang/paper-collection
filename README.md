# paper-collection
分门别类地收集一些读过的论文，并附上不靠谱的简单review。

## 角色扮演 
1. **From Persona to Personalization: A Survey on Role-Playing Language Agents**  
[paper](https://arxiv.org/pdf/2404.18231)
2. **Two Tales of Persona in LLMs: A Survey of Role-Playing and Personalization**
   [paper](https://arxiv.org/abs/2406.01171)


## game agent
1. **A Survey on Large Language Model-Based Game Agents（2024综述）**  
   [paper](https://arxiv.org/pdf/2404.02039)

## RAG
1. **Speculative RAG: Enhancing Retrieval Augmented Generation through Drafting**  
  通过多个drafter‘赌’的方式解决知识密集型rag问答里chunk过多引发的一系列问题。  
   [paper](https://arxiv.org/abs/2407.08223)
   
2. **MEMORAG: MOVING TOWARDS NEXT-GEN RAG VIA MEMORY-INSPIRED KNOWLEDGE DISCOVERY**  
  通过memory model把长文本压缩，以求解决涉及全文的模糊问题，可以说是GraphRAG目标的便宜实现。落地实不实用就是另外的话题了。  
  [paper](https://arxiv.org/pdf/2409.05591)  

4. **LightRAG: Simple and Fast Retrieval-Augmented Generation**  
  GraphRAG更快速、便宜的改良，效果更好。  
   [paper](https://arxiv.org/abs/2410.05779)

5. **HybridRAG: Integrating Knowledge Graphs and Vector Retrieval Augmented Generation for Efficient Information Extraction**
   合并GraphRAG和VectorRAG的方法。  
   [paper](https://arxiv.org/abs/2408.04948) [解析](https://www.53ai.com/news/RAG/2024081509752.html)

   
## dpo相关
1. **dpo**  
  经典。  
   [paper](https://arxiv.org/abs/2305.18290)

2. **Step-DPO: Step-wise Preference Optimization for Long-chain Reasoning of LLMs**  
   希望稳定长句dpo训练的稳定性，说白了，一句切成多句。  
   [paper](https://arxiv.org/abs/2406.18629)

3. **IPO:A General Theoretical Paradigm to Understand Learning from Human Preferences**  
   先找到ΨPO，dpo是它的特例，然后找到另一个特例，就是IPO。  
   [paper](https://arxiv.org/pdf/2310.12036v2.pdf)

4. **A note on DPO with noisy preferences & relationship to IPO**  
   文章通过一个label-smoothing版本的dpo(conservative DPO, cDPO)，解释了dpo和ipo的关系.  
   [paper](https://ericmitchell.ai/cdpo.pdf)



