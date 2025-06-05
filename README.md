# Finding Needles in Images: Can Multi-modal LLMs Locate Fine Details?

Welcome! This repository contains the tech-blog code explanining **NiM-Benchmark** and **Spot-IT** method for evaluating and improving Multi-modal Large Language Models (MLLMs) on fine-grained visual document understanding tasks.

## 🔍 Overview

While Multi-modal Large Language Models have shown impressive capabilities in document understanding, their ability to locate and reason about fine-grained details within complex documents remains understudied. Think about searching a restaurant menu for specific nutritional information or finding a particular warranty clause in a manual – these tasks require precise attention to minute details within larger contexts, much like finding needles in a haystack (or in this case, needles in images).

## 📊 NiM-Benchmark

We introduce **NiM-Benchmark**, a carefully curated benchmark spanning diverse real-world documents including:
- 📰 Newspapers
- 🍽️ Restaurant menus  
- 📚 Lecture slides
- 🌐 Website screenshots

This benchmark is specifically designed to evaluate MLLMs' capabilities in intricate detail-finding tasks.

## 🎯 Spot-IT Method

**Spot-IT** is our simple yet effective approach that enhances MLLM capabilities through:
- Intelligent patch selection
- Gaussian attention mechanisms
- Human-inspired zoom and focus strategies

Our method mimics how humans naturally search documents by zooming in and focusing on relevant areas.

## 🖼️ Sample Images

Check out some examples from our benchmark:

- [Restaurant Menu Example](Sample_imgs/Restaurant.png)
- [Lecture Screenshot Example](Sample_imgs/Lecture%20SS.png)
- [Website Screenshot Example](Sample_imgs/Website_SS.png)

## 🚀 Getting Started

To explore the benchmark and see our method in action, you can:

1. **View the interactive demo**: Open [`index.html`](index.html) in your browser to see sample images and detailed explanations
2. **Access the dataset**: Visit our [Hugging Face dataset](https://huggingface.co/datasets/AST-FRI/needles-in-images)
3. **Read the paper**: Check out our research on [arXiv](https://arxiv.org/abs/your-paper-id) (coming soon)

## 📈 Results

Our extensive experiments reveal both the capabilities and limitations of current MLLMs in handling fine-grained document understanding tasks. Spot-IT achieves significant improvements over baseline methods, particularly in scenarios requiring precise detail extraction from complex layouts.

## 🤝 Contributing

We welcome contributions to improve the benchmark and methodology! Feel free to open issues or submit pull requests.

## 📄 Citation

If you find our work helpful, please consider citing our paper:

```bibtex
@article{needles-in-images-2024,
  title={Finding Needles in Images: Can Multi-modal LLMs Locate Fine Details?},
  author={[Authors]},
  journal={arXiv preprint},
  year={2024}
}
```

## 📞 Contact

For questions or collaborations, please reach out through GitHub issues or contact the research team.

---

© 2024 Research Project | Finding Needles in Images
