# To reader

[Quick Start](../index.html)

# To contributor

工具部分的文件组织结构:

```
├── tools.md
└── ToolsContent
    ├── Attachments
    ├── content1.md
    ├── ...
    ├── contentn.md
    └── README.md
```

* `tools.md` 文件：整个工具模块的索引，其中需要为每个工具分类并添加简介和链接
* `ToolsConent` 文件夹：存储工具相关的内容
* `Attachments` 文件夹：存储工具模块用到的图片等资源文件
* `content.md`文件：每个文件为一个大分类，文件中添加具体的工具信息

下面，我们以 `content1` 大类下 `tool x` 工具为例，展示整个流程

## Step 1

`tools.md` 文件内容结构组织如下：

```markdown
# content1
## tool 1
tool简介，并提供链接指向具体的位置
## ...
# content2
# ...
```

在 `tools.md` 文件中的二级标题 `content1` 下新建三级标题，三级标题名称即要更新的工具名称 `tool x`

三级标题 `tool x` 下，简单介绍一下 `tool x`（功能、特色等），并提供链接指向 `ToolsConent` 文件夹下 `tool x` 内容所在位置，即：

````markdown
[Tool X](ToolsConent/content1.md#tool x)
````

> Note: 如果 tool x 并不属于已有大类，可以根据项目结构新建一个大类

## Step 2

`content1.md` 文件内容结构组织如下：

```markdown
# tool 1
教程、教程链接、注意事项等具体内容
# tool 2
# ...
```

在 `content1.md` 文件中新建二级标题 `tool x`，内容部分自行组织即可

内容可以是自己的总结，也可以给出相关链接或者资源

其中，将文件中插入的图片等显示相关的内容，放在 `Attachments` 文件夹中，统一命名`toolx_figx`；其他资源文件请在正文部分用 *TODO: Source Name* 标注清楚希望该资源链接插入的位置，并将资源文件发送到seu_tcctt@163.com，主题为 Content1-Tool X-Source Name，我们将统一存储管理

## Step 3

具体投稿流程请见[投稿](../contribute.md)

