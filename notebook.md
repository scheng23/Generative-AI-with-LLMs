## Week1
1. Transformers
    1) encoder, decoder
2. generative config:
    1) greedy vs. random sampling
       1) greedy: word/token with highest probability is selected
       2) random sampling
    2) max new tokens
       输入（Prompt）+ 输出（Completion）= 总 Token 数
你提供的输入（Prompt）会占用 token。
模型生成的输出（Completion）也会占用 token。
这两部分的 token 总和不能超过模型的最大 token 限制（例如 10,000 tokens）。
    3) top-k and top-p sampling
    4) temperature: cooler(<1,strongly peaked probability distriution),higher (>1,borader, flatter)
    5) softmax 多分类任务，计算每个类别的概率
3. generative AI project life cycle
     1) scope: define the use case
     2) select: choose an existing model/pretrain your own
![IMG_8659](https://github.com/user-attachments/assets/216091e6-6fd0-46be-bf2b-9668e25a56ce)
