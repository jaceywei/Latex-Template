## LaTex_Template

by **Yanzhou Wei**.

### Features

1. 页面采用浅蓝色主题色排版，十分优雅（和elegentbook大致相同）
2. 既可以供论文等大型项目使用，也可以供平时小论文、笔记等使用
3. 自定义定义、定理、证明等数学环境
4. 自定义数学宏，如用\R替换\mathbb{R}，告别冗长的 mathbb, mathcal.....
5. 封装插入图片环境为函数\fig和\minifig，告别latex插入图片的烦扰

**对模版更详细的介绍请参见https://zhuanlan.zhihu.com/p/1997082556697433063**

### Empty Template
可供小型项目使用（不分多个.tex）

main.tex里面没有写任何内容，并注释掉了模版文件中添加参考文献的部分。

### Instruction文件夹
这是整个模版的说明，也是大型项目的模版
+ main.tex -- 主文件，如果引入新的tex文件，需要在此 \input{新文件}，例如写新chapter时
+ head.tex -- 封面以及目录，修改注释部分即可
+ chapterx.tex -- 章节内容
+ template.tex -- 配置文件
+ refs.bib -- 引用文献信息的文件
+ references.tex -- 生成文末参考文献信息，无需修改
+ Figures -- 图片文件夹，已经设置为默认插入图片来源目录
