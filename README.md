# LLaMa3-Law-Fine-Tuning-JSH
基于LLaMa3-8B微调的法律大模型，能回复您的任何法律疑问！

## 关于模型

本模型基于llama-3-8b-bnb-4bit大模型对自己上传的法律数据集（[Starxx/LLaMa3-Fine-Tuning-Law · Datasets at HF Mirror (hf-mirror.com)](https://hf-mirror.com/datasets/Starxx/LLaMa3-Fine-Tuning-Law)）进行法律领域的lora微调。Training Loss值从2.393900训练到1.390100，表明模型在训练结束时的性能可能是不错的。

## 关于下载

可以使用镜像下载（提高下载速度）

[Starxx/LLaMa3-Fine-Tuning-ChineseLaw-Merged at main (hf-mirror.com)](https://hf-mirror.com/Starxx/LLaMa3-Fine-Tuning-ChineseLaw-Merged/tree/main)

## 问答示例
## 微调前
### Instruction:
请用英语回答
### Input:
Who is the world's most famous painter?
### Response:
Da Vinci, Picasso, and Michelangelo are famous painters.
### Instruction:
请用中文回答
### Input:
放火犯法吗？
### Response:

### Instruction:
请用中文回答
### Input:
校园霸凌属于什么犯罪
### Response:

### Instruction:
请用中文回答
### Input:
造成公共财产损失超过20万不交钱会被判刑吗？
### Response:


##  微调后
### Instruction:
只用中文回答问题
### Input:
防火烧山会被判刑吗？
### Response:
根据《刑法》第二百一十七条的规定，违反国家有关防火的规定，造成森林火灾，情节严重的，处三年以下有期徒刑或者拘役，并处或者单处罚金；情节特别严重的，处三年以上七年以下有期徒刑，并处罚金。因此，可能会被判刑。
### Instruction:
只用中文回答问题
### Input:
防火烧山会被判刑吗？
### Response:
根据《刑法》第十七条的规定，已满十六周岁的人犯罪，应当负刑事责任。已满十四周岁不满十六周岁的人，犯故意伤害罪、寻衅滋事罪等，应当负刑事责任。因此，严重的校园霸凌行为可能构成犯罪，将面临刑事责任。
### Instruction:
只用中文回答问题
### Input:
造成公共财产损失超过20万不交钱会被判刑吗？
### Response:
根据《刑法》第三百九十七条的规定，公职人员滥用职权或玩忽职守，导致公共财产、国家和人民利益遭受重大损失，处三年以下有期徒刑或拘役；情节特别严重的，处三年以上七年以下有期徒刑。因此，可能构成犯罪。
### Instruction:
只用中文回答问题
### Input:
酒驾算是犯罪吗？
### Response:
根据《刑法》第一百三十三条的规定，如果在道路上醉酒驾驶机动车，将以危险驾驶罪定罪处罚。因此，酒驾不仅违反交通规则，也触犯了刑法，是一种犯罪行为。

