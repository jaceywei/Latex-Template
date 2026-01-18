## LaTex_Template

This is a LaTex template used for daily study and note-taking.

by Yanzhou Wei.

### Features

1. 页面采用浅蓝色主题色排版，十分优雅
2. 自定义定义、定理等数学环境
3. 自定义数学宏，如用\R替换\mathbb{R}，简洁方便
4. 既可以供论文等大型项目使用，也可以供平时小论文、笔记等使用

### Empty Template
可供小型项目使用（不分多个.tex）
main.tex里面没有写任何内容，也注释掉了模版文件中添加参考文献的部分。

### Instruction文件夹
这是整个模版的说明，也是后期大型项目的模版
+ main.tex -- 主文件，如果引入新的tex文件，需要在此 \input{新文件}，例如写新chapter时
+ head.tex -- 封面以及目录，修改注释部分即可
+ chapterx.tex -- 章节内容
+ template.tex -- 配置文件
+ refs.bib -- 引用文献信息的文件
+ references.tex -- 生成文末参考文献信息，无需修改
+ Figures -- 图片文件夹，已经设置为默认插入图片来源目录
