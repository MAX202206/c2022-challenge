# c2022-挑战班

## 基本操作流程

1. 从 [https://github.com/luckymark/c2022-challenge](https://github.com/luckymark/c2022-challenge) fork 到你自己的 github 中
2. 创建本地仓库：

   ```
   git clone https://github.com/ **YourGithubAccount** /c2022-challenge
   cd c2022-challenge
   ls

   git config user.name "???"
   git config user.email "???"

   git remote -v
   git remote add upstream https://github.com/luckymark/c2022-challenge
   ```

3. 修改、提交代码：

   ```
   git status
   git add .
   git commit -m "完成了running letter"
   git push
   ```

4. 从 https://github.com/luckymark/c2022-challenge 获取更新

   ```
   git fetch upstream
   git merge upstream/master
   ```

   [在 github 网页上更新的方法](https://www.zhihu.com/question/20393785/answer/30725725)

   [fork 后如何同步源的新更新](https://segmentfault.com/q/1010000002590371)

5. 请求老师 review 代码的方法：在 github 网页上发起一个 PR（pull request）即可

## [作业](https://github.com/luckymark/c2022-challenge/tree/main)

1. level0 可选，用于还不够熟练的同学练手（嫌题目太少的同学，那就刷刷咱[电子神技大学的 OJ](http://acm.uestc.edu.cn/#/)吧，从低到高地刷哈）
2. level1 必做，课堂＋课后练习
3. level2 可选，供精力旺盛到变态的大神们发泄之用，不过还蛮有趣的，试试就知道了

## 参考

### IDE: 

- 墙裂推荐JetBrains的[CLion](https://www.jetbrains.com/clion/) ，申请免费的License点[这里](https://www.jetbrains.com/community/education/)

### C语言参考：

- [c语言资料大全](https://github.com/jobbole/awesome-c-cn)

- [Linux C编程一站式学习](http://akaedu.github.io/book/index.html)  （把书读厚）

- [K&R C语言程序设计](https://github.com/huyubing/books-pdf/blob/master/C%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1%E8%AF%AD%E8%A8%80(K%26R)%E6%B8%85%E6%99%B0%E4%B8%AD%E6%96%87%E7%89%88.pdf) （把书读薄）

### GIT

[史上最浅显易懂的 Git 教程！ 廖雪峰](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

[Pro Git（中文版）](http://git.oschina.net/progit/)

[撸袖子 动手学 Git 专治菜鸟](http://igit.linuxtoy.org/contents.html)

[Git 远程操作详解 阮一峰](http://www.ruanyifeng.com/blog/2014/06/git_remote.html)

[fork 后如何跟上源 repo 的变化](https://segmentfault.com/q/1010000002590371)

### Markdown

[Markdown 入门指南](http://www.jianshu.com/p/1e402922ee32)

### 其他

[免费的计算机编程类中文书籍](https://github.com/wwj718/free-programming-books-zh_CN)
