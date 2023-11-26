# 你是怎么到这里来的？

其他地方不方便写的东西都堆到这里来了。
 文件组织结构:

 ```
├── good_stuff.md
└── GoodStuffContent
    ├── Attachments
    ├── content1.md
    ├── ...
    ├── contentN.md
    └── README.md
 ```

* `good_stuff.md` 文件：整个 `好东西` 模块的索引，短内容
* `GoodStuffConent` 文件夹：存储工具相关的内容
* `Attachments` 文件夹：存储 `好东西` 模块用到的图片等资源文件
* `content.md`文件：你的正文

## 短内容

如果你想添加的内容不是很长，完全可以直接写在 `./good_stuff.md`，如果添加的内容中包含图片，则将图片放在 `./Attachments` 中。

## 长内容

如果你想添加的内容很长，可以在 `./good_stuff.md` 文件里面写一下**标题**，**内容简介**，**正文链接**，并把正式的内容以 Markdown 文件的形式添加在 `./GoodStuffContent/` 中，如果你的内容附有图片，则将图片全部放在 `./GoodStuffContent/Attachments` 中(记得在正文里修改对应图片的引用)。
