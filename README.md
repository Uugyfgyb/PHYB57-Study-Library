# PHYB57 Study Library

PHYB57 中文学习资料库。按课程主题分类，每份资料放在独立的 `topics/` 目录下。打开[专题目录](./index.html)选择内容；网页可直接阅读，Notebook 可下载后在 Jupyter 中编辑和运行。

## 专题

| 分类 | 专题 | 在线阅读 | 可编辑文件 |
| --- | --- | --- | --- |
| 算法与复杂度 | Tutorial 4：算法复杂度与 Big-O 逐行人话版 | [阅读](./topics/algorithm-complexity-big-o/index.html) | [Notebook](./topics/algorithm-complexity-big-o/PHYB57_Tutorial4_算法复杂度Big-O_逐行人话版.ipynb) |

## 仓库结构

```text
PHYB57-Study-Library/
├── index.html                             # 按主题分类的入口
├── README.md                              # 索引与维护规则
└── topics/
    └── algorithm-complexity-big-o/
        ├── index.html                     # Notebook 的静态阅读版
        ├── README.md                      # 内容、来源和使用说明
        └── PHYB57_Tutorial4_算法复杂度Big-O_逐行人话版.ipynb
```

## 新增资料的分类规则

1. 按知识主题分类，如“算法与复杂度”“Python 基础”“数值方法”“数据处理”。课程 Tutorial 编号保留在标题中，方便对应课件。
2. 每份资料使用一个全小写英文短目录名，放在 `topics/` 下；同主题新资料仍建立独立目录。
3. 每个专题提供 `index.html` 阅读入口和 `README.md`，说明来源、适用范围、运行方式与已知限制。可编辑原文件保存在同一目录。
4. 根目录 `index.html` 和此表同时加入对应分类的专题入口。测量结果、理论复杂度与示意例子在内容中明确区分。

本库用于个人学习资料整理。所收录资料涉及课程 Tutorial 的原文和代码；未声明开放再利用许可。
