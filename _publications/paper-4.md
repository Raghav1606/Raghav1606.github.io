---
title: "In-Context Learning with GPT-4 for Medical Summarization"
collection: publications
permalink: /publications/p4
excerpt: 'Yash Mathur^, <b>Raghav Kapoor^</b>, Sanketh Rangreji^, Medha Palavalli^, Amanda Bertsch, Matthew R. Gormley.<br />^ Denotes equal contribution.<br /> ACL ClinicalNLP, Toronto, Canada [2023]'
---

[[paper]](https://drive.google.com/file/d/1m4H8KJxYHddTft0XahhdDxLo9QwvL6fM/view?usp=sharing)

Abstract
======

In this paper, we tackle the task of summarizing medical conversations into structured and concise notes called SOAP notes that capture relevant information for medical professionals. This task is challenging due to the unstructured nature of medical conversations, the variability of language used, and the need to identify and summarize key information. We present a novel system for the Dialogue2Note Medical Summarization tasks in the MEDIQA 2023 Shared Task. Task A involves section-wise summarization, while Task B is for full note summarization. Our approach for Task A is a two-stage process of selecting semantically similar dialogues and using the top-
 similar dialogues as in-context examples for GPT-4. For Task B, we use a similar solution with 
=1. We achieved 3rd place in Task A (2nd among all teams), 4th place in Task B Division Wise Summarization (2nd among all teams), 15th place in Task A Section Header Classification (9th among all teams), and 8th place among all teams in Task B. Our results highlight the effectiveness of few-shot prompting for this task. We compared GPT-4 performance with several finetuned baselines and observed that the generated summaries were more abstractive, shorter, and less detail-oriented.
