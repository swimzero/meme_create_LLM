# meme_create_LLM (2024.7.14-2024.8.10)

### Tech Stack: pytorch / Colab
This project was developed using PyTorch and submitted for the 미래내일 일경험 프로젝트형 program.

### Problems & Solutions

One of the main challenges in this project was collecting linguistic meme data, as there was little existing research or readily available datasets on the subject. Initially, we hypothesized that popular YouTube comments could help us identify current memes. However, the comments were often too specific to the content of the videos, making it difficult to extract widely recognized memes. Additionally, meme-related comments were not frequent enough to build a large dataset.

This experience highlighted the limitations of using platforms like YouTube to gather meme data. We realized that while linguistic memes are memorable, they are not as common as expected, which underscored the importance of our project.

To address this issue, we analyzed trend research methods used by other services targeting people in their 10s to 30s and adopted a direct survey approach. However, using surveys to collect large-scale data posed financial constraints. To overcome this, we utilized GPT-4 to generate a variety of memes based on the survey results. This allowed us to effectively train our model on the linguistic memes used by this demographic.

<hr/>
One question that arose during the final stages of the project was: “Is our approach similar to what professionals in the AI industry do?” To resolve this, we consulted with Byeong-woo Jeon, a PhD candidate at KAIST. Through this discussion, we gained clarity on how AI models are typically structured in the industry.

One major concern we had was around the process of constructing our dataset. Mr. Jeon explained that it’s common practice to feed a model’s output back into the input during training, which helped us feel confident in our approach. This expert consultation reinforced our belief that our methods were aligned with real-world AI practices, particularly in dataset creation and model training.

### Reflections & Future Goals
