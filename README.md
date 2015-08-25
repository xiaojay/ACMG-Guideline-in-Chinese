＃中文版ACMG官方基因组解读指南
=============================================
翻译《Standards and guidelines for the interpretation of sequence variants: a joint consensus recommendation of the American College of Medical Genetics and Genomics and the Association for Molecular Pathology》

[英文原版](http://www.nature.com/gim/journal/v17/n5/full/gim201530a.html)

利用老板不在的时间和周末，悄悄翻译，速度可能有些慢。

# 在线阅读

使用Gitbook制作，可以直接[在线阅读](https://www.gitbook.com/book/biolee/acmg-guideline-in-chinese/)。
不过，翻译才刚刚开始，这个链接并无卵用。





# 贡献力量

如果想做出贡献的话，你可以：

－你可以做任何事情

# 翻译建议

如果你愿意一起翻译校对的话，请仔细阅读：

- 使用markdown进行翻译，文件名必须使用英文，因为中文的话gitbook编译的时候会出问题
- 翻译后的文档请放到inChinese文件夹下的对应部分中，然后pull request即可，好像用github和gitbook同步了，具体这里还需要确认一下（其实这里也无卵用，只是希望以后的基因解读指南都有中文版。
- 有其他任何问题都欢迎发issue，我看到了会尽快回复

谢谢！

# 关于术语

翻译术语的时候请参考这个流程：

- 尽量保证和已翻译的内容一致，所以目前我有可能自己生造一些词汇，但是我会尽量参考《牛津案头参考手册——临床遗传学》，医学的绿皮书。我记得是有官方标准的，再找找。

# 参考流程

有些朋友可能不太清楚如何帮忙翻译，我这里写一个简单的流程，大家可以参考一下：

(然而，下面的方法可能并无卵用)

1. 首先fork我的项目
2. 把fork过去的项目也就是你的项目clone到你的本地
3. 在命令行运行 `git branch develop` 来创建一个新分支
4. 运行 `git checkout develop` 来切换到新分支
5. 运行 `git remote add upstream https://github.com/biolee/ACMG-Guideline-in-Chinese.git` 把我的库添加为远端库
6. 运行 `git remote update`更新
7. 运行 `git fetch upstream gh-pages` 拉取我的库的更新到本地
8. 运行 `git rebase upstream/gh-pages` 将我的更新合并到你的分支

这是一个初始化流程，只需要做一遍就行，之后请一直在develop分支进行修改。

如果修改过程中我的库有了更新，请重复6、7、8步。

修改之后，首先push到你的库，然后登录GitHub，在你的库的首页可以看到一个 `pull request` 按钮，点击它，填写一些说明信息，然后提交即可。



# 开源协议
基于[WTFPL](http://en.wikipedia.org/wiki/WTFPL)协议开源。