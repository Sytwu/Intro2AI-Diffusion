# Intro2AI-Diffusion
This repository is for the homework in intro. to AI at NYCU, mainly focusing on diffusion model.

## Introduction
In this homework, you are asked to `train your diffusion model` and `generate optical illusions` with a pretrained text-to-image diffusion.
The goals of this assignment are showing as follows:

1. Understand the architecture and design of U-Net.
2. Implement a diffusion model and train it from scratch.
3. Learn how to evaluate generative models (e.g., FID score).
4. Utilize existing (diffusion) models available on Hugging Face.
5. Explore a training-free method for diffusion.

## Implementation(70%)
### Part 1: Train Your Own Diffusion (45%)

~~Part 1-1: Model Architecture (10%)~~

Part 1-1: Denoising Process (15%)

Part 1-2: 1-2:Result Visualization (10%)

Part 1-3: Evaluation Baseline (20%)

### Part 2: Optical Illusion with Diffusion (25%)

Part 2-1: Prompt Design (5%)

Part 2-2: Viewing Transformation (5%)

Part 2-3: Denoising Operation (10%)

Part 2-4: Evaluation Baseline (5%)


## Report(30%)

* You should write your report following the report template.
* The report should be written in `English`.
* Please save the report as a `.pdf` file. (font size: 12)
* For every parts, please take some screenshots of your code and explain how you implement codes `in detail`.

## Submission
```
{student_id}_hw5.zip
├── Part1
│   ├── generated
│       ├── 1.jpg
│       ├── 2.jpg
│       ├── ...
│       └── 1000.jpg
│   ├── model.pt
│   └── diffusion.ipynb
│
├── Part2
│   ├── result.jpg
│   └── multi-view.ipynb
│
└── report.pdf
```

## Reference
[1] [Machine Learning Material from Hung-yi Lee](https://speech.ee.ntu.edu.tw/~hylee/ml/2023-spring.php)

[2] [Denoising Diffusion Probabilistic Models (NeurIPS 2020)](https://arxiv.org/pdf/2006.11239)

[3] [Denoising diffusion implicit models (ICLR 2021)](https://arxiv.org/pdf/2010.02502)

[4] [DeepFloyd IF on Hugging Face](https://huggingface.co/docs/diffusers/api/pipelines/deepfloyd_if)

[5] [Visual Anagrams: Generating Multi-View Optical Illusions with Diffusion Models (CVPR 2024 oral)](https://arxiv.org/pdf/2311.17919)