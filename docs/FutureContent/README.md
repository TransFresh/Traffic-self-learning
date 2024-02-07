# To reader

[Quick Start](../index.md)

# To contributor

未来部分的文件组织结构:

```bash
├── future.md
└── FutureContent
    ├── attachments
    ├── Content1.md
    ├── ...
    ├── ContentN.md
    └── README.md
```

* `future.md` 文件：整个未来模块的索引，请针对自己想分享的内容进行分类并添加简介和链接
* `FutureContent` 文件夹：存储未来相关的内容
* `attachments` 文件夹：存储未来分享用到的图片等资源文件
* `Content.md`文件：每个文件为一个大分类，文件中添加具体的说明信息

下面，我们以 `Content1` 大类下 `Viewpoint X` 工具为例，展示整个流程

## Step 1

`future.md` 文件内容结构组织如下：

```markdown
# Content1
## Viewpoint
分享观点内容简介，并提供链接指向具体的位置
## ...
# Content2
# ...
```

在 `future.md` 文件中的一级标题 `Content1` 下新建二级标题，二级标题名称即 `Viewpoint X`

二级标题 `Viewpoint X` 下，简单介绍一下 `Viewpoint X`（分享内容可以帮助到哪些人群等），并提供链接指向 `FutureContent` 文件夹下 `Viewpoint X` 内容所在位置，即：

````markdown
[Viewpoint X](FutureContent/Content1#Viewpoint X)
````

> Note: 如果分享的观点并不属于已有大类，可以根据项目结构新建一个大类

## Step 2

`Content 1.md` 文件内容结构组织如下：

```markdown
# Viewpoint1
# Viewpoint2
# ...
# (根据自己想分享的内容合理安排即可)
```

在 `Content 1.md` 文件中新建一级标题 `Viewpoint X`，内容部分自行组织即可

内容可以是自己的总结，也可以给出相关链接或者资源

其中，将文件中插入的图片等显示相关的内容，放在 `attachments` 文件夹中，统一命名`Tool X-fig`；其他资源文件请在正文部分用 *TODO: Source Name* 标注清楚希望该资源链接插入的位置，并将资源文件发送到 <seu_tcctt@163.com>，主题为 Content1-Viewpoint X-Source Name，我们将统一存储管理

## Step 3

具体投稿流程请见[投稿](../contribute.md)
