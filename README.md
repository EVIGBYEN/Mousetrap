# <img src="Figures/mousetrap_logo.png" alt="icon" width="45"/> A Mousetrap: Fooling Large Reasoning Models for Jailbreak with Chain of Iterative Chaos

### Findings of the Association for Computational Linguistics: ACL 2025  <img src="Figures/acl_logo.png" alt="icon" width="55"/>

**Yang Yao  Xuan Tong  Ruofan Wang  Yixu Wang<br>
Lujundong Li  Liang Liu  Yan Teng  Yingchun Wang**<br>
*Shanghai Artificial Intelligence Laboratory  The University of Hong Kong*<br>
*Fudan University   The Hong Kong University of Science and Technology (Guangzhou)*

---

## 🧠 Abstract

Large Reasoning Models (LRMs) have significantly advanced beyond traditional Large Language Models (LLMs) with their exceptional logical reasoning capabilities, yet these improvements introduce heightened safety risks. When subjected to jailbreak attacks, their ability to generate more targeted and organized content can lead to greater harm. Although some studies claim that reasoning enables safer LRMs against existing LLM attacks, they overlook the inherent flaws within the reasoning process itself. To address this gap, we propose the first jailbreak attack targeting LRMs, exploiting their unique vulnerabilities stemming from the advanced reasoning capabilities. Specifically, we introduce a Chaos Machine, a novel component to transform attack prompts with diverse one-to-one mappings. The chaos mappings iteratively generated by the machine are embedded into the reasoning chain, which strengthens the variability and complexity and also promotes a more robust attack. Based on this, we construct the Mousetrap framework, which makes attacks projected into nonlinear-like low sample spaces with mismatched generalization enhanced. Also, due to the more competing objectives, LRMs gradually maintain the inertia of unpredictable iterative reasoning and fall into our trap. Success rates of the Mousetrap attacking o1-mini, Claude-Sonnet and Gemini-Thinking are as high as 96%, 86% and 98% respectively on our toxic dataset Trotter. On benchmarks such as AdvBench, StrongREJECT, and HarmBench, attacking Claude-Sonnet, well-known for its safety, Mousetrap can astonishingly achieve success rates of 87.5%, 86.58% and 93.13% respectively. Attention: This paper contains inappropriate, offensive and harmful content.

## 🖼️ Poster

<img src="Figures/poster.jpg">

## 🧪 Installation

```
git clone https://github.com/EVIGBYEN/Mousetrap.git
cd Mousetrap
```

## 📚 Citation

```
@article{yao2025mousetrap,
  title={A mousetrap: Fooling large reasoning models for jailbreak with chain of iterative chaos},
  author={Yao, Yang and Tong, Xuan and Wang, Ruofan and Wang, Yixu and Li, Lujundong and Liu, Liang and Teng, Yan and Wang, Yingchun},
  journal={arXiv preprint arXiv:2502.15806},
  year={2025}
}
```