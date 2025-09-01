# NYCU Deep Learning (Summer 2025)
> National Yang Ming Chiao Tung University — Department of Computer Science

[![Course](https://img.shields.io/badge/Course-Deep%20Learning-blue)]()
[![Semester](https://img.shields.io/badge/Semester-Summer%202025-informational)]()
[![Language](https://img.shields.io/badge/Language-English-lightgrey)]()

---

## Table of Contents

- [Overview](#課程簡介-overview)
- [Instructors & TAs](#授課教師與助教-instructors--tas)
- [Prerequisites](#先修課程-prerequisites)
- [Grading](#評分方式-grading)
- [Schedule](#時程與主題-schedule)
- [Textbooks & References](#教材與參考-textbooks--references)
- [Repo Structure](#專案倉庫建議結構-suggested-repo-structure)

---

## Overview

This course balances **theory** and **practice**, covering:
- Deep feedforward networks, CNNs, RNNs/recursive nets
- Autoencoders, linear factor models, GANs, normalizing flows, diffusion
- Reinforcement learning (value-, policy-, and model-based)
- Final projects are presented in academic-paper style

---

## Instructors & TAs
**Instructors**  
- 彭文孝（Peng）｜wpeng@cs.nctu.edu.tw  
- 陳永昇（Chen）｜yschen@nycu.edu.tw  
- 謝秉均（Hsieh）｜pinghsieh@cs.nycu.edu.tw  

**Teaching Assistants** (alphabetical order)  
- 楊賀弼｜mrrrimge32.cs13@nycu.edu.tw  
- 林于翔｜kingslayer.cs13@nycu.edu.tw  
- 陳敬中｜jingzhongchen.cs13@nycu.edu.tw  
- 何銘哲｜ethan920508.cs13@nycu.edu.tw  
- 劉子齊｜jonathan.tcliu.en11@nycu.edu.tw  
- 洪偉｜hwei1048576.cs08@nycu.edu.tw  
- 溫柏萱｜alison.cs13@nycu.edu.tw  

---

## Grading

**Part I（3 學分）Deep Learning**
- 4 Labs（Lab 0、2、5、6；個別完成）80%
- 期末考 20%

**Part II（3 學分）Deep Learning & Practice**
- 4 Labs（Lab 1、3、4、7）50%
- 論文報告（3 人一組）25%
- 期末專題（3 人一組）25%

---

## Schedule

> Afternoon 為下午課；Evening 為晚間實作／實驗課。Dates in **2025/7–8**.

| Date  | Afternoon Topic                                | Evening / Lab                         |
|------:|------------------------------------------------|---------------------------------------|
| 7/1   | Introduction & ML Basics                       | Warm-up (**Lab 0**)                    |
| 7/3   | Deep Networks (Deep Feedforward Nets)          | Back-Propagation (**Lab 1**)          |
| 7/8   | Convolutional Networks                         | ConvNets & Transformers / (**Lab 2**) |
| 7/10  | Introduction to Reinforcement Learning         | No class                              |
| 7/15  | Recurrent & Recursive Nets                     | MaskGIT (**Lab 3**)                   |
| 7/17  | Linear Factor Models, Autoencoders             | No class                              |
| 7/22  | Generative Adversarial Networks                | CVAE (**Lab 4**)                      |
| 7/24  | Value-Based Reinforcement Learning             | No class                              |
| 7/29  | Policy-Based Reinforcement Learning            | Discrete Control (**Lab 5**)          |
| 7/31  | Diffusion Models                               | No class                              |
| 8/5   | Normalizing Flows                              | Diffusion (**Lab 6**)                 |
| 8/7   | Final Project Proposal                          | Final Project Proposal                 |
| 8/12  | Model-Based Reinforcement Learning             | Continuous Control (**Lab 7**)        |
| 8/14  | No class                                       | No class                              |
| 8/19  | Paper Presentation                             | Paper Presentation                    |
| 8/21  | Paper Presentation                             | Paper Presentation                    |
| 8/26  | Final Exam                                     | —                                     |
| 8/28  | Final Project Demo                              | —                                     |

---

## Textbooks & References

- I. Goodfellow, Y. Bengio, A. Courville, *Deep Learning*, MIT Press, 2016.  
- R. S. Sutton, A. G. Barto, *Reinforcement Learning: An Introduction*, 2020.  
- 課程材料約自編與既有教材各佔 50%（for reference only）

---

## Repo Structure

```
.
├── labs/
│   ├── lab0_warmup/
│   ├── lab1_backprop/
│   ├── lab2_conv_transformers/
│   ├── lab3_maskgit/
│   ├── lab4_cvae/
│   ├── lab5_discrete_rl/
│   ├── lab6_diffusion/
│   └── lab7_continuous_rl/
├── paper_presentation/
│   ├── slides/
│   └── report/
├── final_project/
│   ├── proposal/
│   ├── code/
│   └── paper/
├── docs/              # notes, additional references
├── .gitignore
└── README.md
```

---

