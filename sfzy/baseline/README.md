# lead-3 baseline
本代码使用LEAD策略生成摘要。

其中，LEAD针对数据分布特征做了简要改进。

## 运行说明
``python main.py``

## 输入输出文件
输入（测试集）：``../stage_1/evaluate.jsonl``
输出（摘要结果文件）：``data/result.jsonl``

数据均包含若干行，每行数据为jsonl格式，测试集包含若干字段：

| 字段名     |     说明 |
| :---------- | --------:|
| id          |   文档唯一标识符 |
| text    |   原文 |
| url      |   数据来源 |

输出摘要文件格式：
| 字段名     |     说明 |
| :---------- | --------:|
| id          |   文档唯一标识符 |
| summary    |   摘要 |