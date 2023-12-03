# To reader

[Quick Start](../index)

# To contributor

知识部分对不同课程进行分类（例如数学类、交通工程类等等）组织架构如下:

```
├── knowledge.md
└── KnowledgeContent
    ├── attachments
    ├── Content1.md
    ├── ...
    ├── ContentN.md
    └── README.md
```

* `knowledge.md` 文件：整个知识模块的索引，包括不同课程类型的介绍等
* `KnowledgeContent` 文件夹：存储知识分享相关的内容
* `attachments` 文件夹：存储知识分享用到的图片等资源文件
* `Content.md`文件：每个文件为一个课程分类，大家针对自己想投稿的课程选择对应的课程类别进行修改。

下面，我们以 `Content1` 大类下 `Course X` 为例，展示整个流程

## Step 1

`knowledge.md` 文件内容结构组织如下：

```markdown
# Content1
## Course X
课程内容介绍，并提供链接指向具体的位置
## ...
# Content2
# ...
```

在 `knowledge.md` 文件中的一级标题 `Content1` 下新建二级标题，二级标题名称即 `Course X`

二级标题 `Course X` 下，简单介绍一下 `Course X`（分享内容可以帮助到哪些人群等），并提供链接指向 `KnowledgeContent` 文件夹下 `Course X` 内容所在位置，即：

````markdown
[Course X](KnowledgeContent/Content1#Course X)
````

> Note: 如果分享的观点并不属于已有课程类别，可以根据项目结构新建一个课程类

对于每一个具体课程的介绍，请参考如下模板：
```markdown
1. 标准课程：
- 介绍
    1. 课程学期
    2. 先修课程、衔接课程等
    3. 课程工具、软件、编程语言等
    4. 课程简介：课程目标、课程难度、重点分析、考核方式
- 资源
    1. 课程PPT
    2. 课程作业
    3. 课程试卷
    4. 课程参考网站
2. 思政课程：
- 介绍
    1. 课程学期
    2. 考核方式
    3. 难度
- 资源
    1. 课程PPT
    2. 课程作业
    3. 课程试卷
```
## Step 2

`Content 1.md` 文件内容结构组织如下：

```markdown
# Course1
# Course2
# ...
```

在 `Content 1.md` 文件中新建一级标题 `Course X`，内容部分自行组织即可

内容可以是自己的总结，也可以给出相关链接或者资源

其中，将文件中插入的图片等显示相关的内容，放在 `attachments` 文件夹中，统一命名`Tool X-fig`；其他资源文件请在正文部分用 *TODO: Source Name* 标注清楚希望该资源链接插入的位置，并将资源文件发送到seu_tcctt@163.com，主题为 Content1-Course X-Source Name，我们将统一存储管理

## Step 3

具体投稿流程请见[投稿](../contribute)

