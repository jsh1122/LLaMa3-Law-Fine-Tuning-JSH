# LLaMa3-Law-Fine-Tuning-JSH
基于LLaMa3-8B微调的法律大模型，能回复您的任何法律疑问！

## 关于模型

本模型基于llama-3-8b-bnb-4bit大模型对自己上传的法律数据集（[Starxx/LLaMa3-Fine-Tuning-Law · Datasets at HF Mirror (hf-mirror.com)](https://hf-mirror.com/datasets/Starxx/LLaMa3-Fine-Tuning-Law)）进行法律领域的lora微调。Training Loss值从2.393900训练到1.390100，表明模型在训练结束时的性能可能是不错的。

## 关于下载

可以使用镜像下载（提高下载速度）

[Starxx/LLaMa3-Fine-Tuning-ChineseLaw-Merged at main (hf-mirror.com)](https://hf-mirror.com/Starxx/LLaMa3-Fine-Tuning-ChineseLaw-Merged/tree/main)

## 问答示例

### Instruction:
只用中文回答问题
### Input:
防火烧山会被判刑吗？
### Response:
根据《刑法》第三百二十五条的规定，故意纵火或者放火，致人死亡、重伤、失踪、失踪后死亡、重大财产损失的，处三年以上十年以下有期徒刑，并处罚金；情节特别严重的，处十年以上有期徒刑，并处罚金。因此，防火烧山会被判刑。<|end_of_text|>
