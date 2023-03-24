# 🐖pig_zero

Fine-tuned LLaMA model on both English and Chinese

Pig_zero is a research project similar to the Stanford Alpaca Project, but supporting both English and Chinese. This project is for research purposes only and should not be used for commercial or business purposes.

### Project Overview

Pig_zero is a machine learning project that has been trained using both public data and instruction-following data from the Stanford Alpaca Project. This project is in beta and may contain misleading information. The main purpose of this project is to explore the capabilities of machine learning algorithms and their potential use in natural language processing.

Currently, I am training my model in a way similar to ecjwg, using low-rank adaptation with the peft package. However, I am facing significant limitations due to a lack of computational power and high-quality Chinese data samples available on the internet. As a result, the performance of the model is greatly restricted. 


### Playground
[Colab](https://colab.research.google.com/drive/1SClKxoSKvYeUpiilF7TtTZs-tHp6eucf?usp=sharing) 


**Update: March 24, 2023 - Version 0.1 has much better response rates in both languages.**

---

```
Instruction: write an email to thank you the help from peter

Response: Dear Peter,

Thank you so much for your help with my project. I really appreciate all the time and effort you put in to make sure it was completed on time. I couldn't have done it without you!

Sincerely,
[Your Name]
```

```
Instruction: 幫我計劃去巴黎旅行

Response: 計劃一個至少一周的舊城際行程,包括訪見藝術博物館、吸引人心的建築和觀察各種文化表演。還可以參加一些免費活動,如吐魯番公園和聖羅伯特廟,以及購買一些特殊的食物,如葡萄酒和蛋糕。
```

```
Instruction: how can i use AI to imporve my liviing

Response: AI can be used to improve your living in a variety of ways. For example, AI-powered virtual assistants can help you manage your schedule, remind you of important tasks, and provide you with personalized recommendations based on your preferences. AI can also be used for health monitoring, such as detecting early signs of illness and providing personalized nutrition and fitness advice. Additionally, chatbots can provide customer service, answer questions, and help you find the information you need.


```


---
