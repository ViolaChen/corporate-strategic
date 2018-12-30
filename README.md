# 项目专用仓库

## 目录

一.工作流说明

二.项目贡献规则

## 一.工作流说明(这里照搬开智方法论)
1. 在沟通中触发的灵感、改进点,灵感=>放入issues具体描述.

也可以在issues里面开个自己的树洞贴,把自己平时觉得做项目时自己需要注意的点写在里面.
比如: 

![大蔚对自己的提醒.png](https://upload-images.jianshu.io/upload_images/15413521-9a0ec85c520b0be3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 成果沉淀到wiki里,wiki里面放整理好的清单,说明等.
**并在issue里面放置对应wiki链接.**


3. 认领好任务后,在仓库里自创文件夹.




## 二.项目贡献规则

### (一)仓库文件夹/文件名命名规则.

文件夹/文件名必须用**英文字母**命名!哪怕是用拼音.若是用中文,将无法使用git log查看曾经改动了什么

根据我们项目的维度“学术、商业、职业、个人思考，如何从中**套利**”这四个维度:

暂规定文件夹名的前缀是:
- `xs`:学术
- `sy`:商业
- `zy`:职业
- `tl`:个人思考以及如何套利.

举例,大蔚承担的任务是分析"麦肯锡"这家顶级战略咨询公司.

那么,大蔚可以在仓库里直接创建一个文件夹

并命名为"sy-mckinseyRearch" 或者用拼音 "sy-maikenxi"

因为最后我们需要把成果汇总起来,所以文件夹/文档命名上大家尽量写的详细一些,以后好汇总.



### (二) 协作文档规范

参考于:[开智协作文档撰写指南](https://github.com/OpenMindClub/Share/wiki/HbDoc)

一个文章包括4点:
- 头部说明
- 正文
- 参考资料
- changelog

**各版块规则**

- 头部说明:根据`5w1h`分析法

交代文档是谁写的,或者是哪几个小伙伴合写的,各自有没有什么分工?

交代背景和为何写出本文的原因

目前的进展如何

目前根据已有信息已经有了什么判断.

以方便小伙伴根据头部信息判断要不要阅读，判断文档内容是否OK,是否能给出建设性意见等.



### (三) commit message 用语规范.

参考于:[GitHub Commit message 用语规范 | 安人集团](https://github.com/OpenMindClub/Share/wiki/HbGitHubCommitMessage)

请写**有区分度**的commit message.以便自己日后查看过往版本时一目了然,也方便同伴愉快合作.

有4个常见的动作,根据不同的动作写commit  message:
- create:创建某文档
- fix:修正一些内容.排版,格式,链接,图片,文件名等.
- add:添加某些内容.注意简述添加了什么内容
- refactor:调整某文章结构.
- ......

比如"create 学术维度.md","fix 某某文章格式",
可以采用[英+中]的格式,防止不会用英文表达具体情境.


## 三.其他贡献规则参考文献


[备忘录写作指南](http://www.sohu.com/a/235028826_380923)

[awesome-reademe github](https://github.com/matiassingers/awesome-readme)


## changelog

- 181230 大蔚添加项目贡献规则