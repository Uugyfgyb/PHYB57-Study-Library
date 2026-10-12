# PHYB57 Study Library

PHYB57 中文学习资料库。资料先分为 **Tutorial** 和 **上课讲义（Lectures）** 两大类，再在类内按章节或专题分别存放。打开[专题目录](./index.html)选择内容；网页用于阅读，Notebook 可下载后在 Jupyter 中编辑和运行。

## Tutorial

| 专题 | 在线阅读 | 可编辑文件 |
| --- | --- | --- |
| Tutorial 4：算法复杂度与 Big-O 逐行人话版 | [阅读](./tutorials/algorithm-complexity-big-o/index.html) | [Notebook](./tutorials/algorithm-complexity-big-o/PHYB57_Tutorial4_算法复杂度Big-O_逐行人话版.ipynb) |

## 上课讲义（Lectures）

| 章节 | 内容 | 在线阅读 | 可编辑文件 |
| --- | --- | --- | --- |
| C8-1 | 复杂度、Big-O 与性能分析 | [阅读](./lectures/chapter-8-1-complexity/index.html) | [Notebook](./lectures/chapter-8-1-complexity/PHYB57_C8-1.ipynb) |
| C9 | 进制与浮点数表示 | [阅读](./lectures/chapter-9-number-representation/index.html) | [Notebook](./lectures/chapter-9-number-representation/PHYB57_C9.ipynb) |
| C11 | 文件读写逐行人话版 | [阅读](./lectures/chapter-11-file-io/index.html) | [Notebook](./lectures/chapter-11-file-io/PHYB57_C11_文件读写_逐行人话版.ipynb) |

## 仓库结构与分类规则

```text
PHYB57-Study-Library/
├── index.html                  # Tutorial / 上课讲义两大类入口
├── README.md                   # 分类索引与维护规则
├── tutorials/                  # Tutorial、习题课与练习资料
│   └── algorithm-complexity-big-o/
├── lectures/                   # 普通上课讲义，按章节存放
│   ├── chapter-8-1-complexity/
│   ├── chapter-9-number-representation/
│   └── chapter-11-file-io/
└── topics/algorithm-complexity-big-o/  # 旧公开链接兼容入口
```

1. 新的 Tutorial 与习题课资料只放入 `tutorials/`；普通课堂讲义只放入 `lectures/`。
2. 每份资料使用独立的全小写英文短目录名；原 Notebook 文件名保持不变。
3. 每个目录包含 `index.html` 阅读版、可编辑 Notebook 和 `README.md` 使用说明。目录首页和上方索引同时更新。
4. 旧 `topics/algorithm-complexity-big-o/` 仅为此前分享过的链接保留跳转和原 Notebook；它不是第三类资料。

本库用于个人学习资料整理。部分材料包含课程讲义原文或代码；仓库未声明开放再利用许可。静态网页的数学排版可能需要联网加载 MathJax。
