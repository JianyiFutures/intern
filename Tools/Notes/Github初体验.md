## 什么是Github?
>Github就是一个面向开源及私有软件项目的托管平台，它只支持Git作为唯一的版本库格式进行托管。

## 接触Github
1. 注册完成并加入群组
2. 在项目页面进行了操作探索，查看了Issues的内容，尝试回复了一个新Issue
![](https://github.com/XifenYE/-/blob/master/home/%E7%81%AB%E7%8B%90%E6%88%AA%E5%9B%BE_2017-03-14T06-53-59.101Z.png?raw=true)

3. 尝试将项目目录Fork 到自己的Repository

![](https://github.com/XifenYE/-/blob/master/home/1.png?raw=true)

4. 尝试建立了自己的Repository

![](https://github.com/XifenYE/-/blob/master/home/2.png?raw=true)
## 问题解决
### fork和pull request的作用？
>![](https://pic3.zhimg.com/dadbcef0bca3d2eb68ef6009f45361e2_r.png)
转自知乎

- 通俗来说，fork就是将原作者的项目拷贝到自己的repository里，pull request就是自己在对这份项目作了补充修改后，向原作者展示我所作的的修改，原作者看过之后觉得修改可行，就会 merge 到他自己的项目中，至此，整个 pull request 的过程就结束了

### fork项目之后,如何保持和原作者同步的更新？
- 在查阅许多解答后，唯一一个看懂并且实验成功的经验——
[github上fork别人的代码之后,如何保持和原作者同步的更新?](https://blog.iplayloli.com/get-update-from-author-after-fork-on-github.html)
- 简单来说，就是进入Github发起Pull Request，选择Compare across fork ，然后反向操作，base改成自己的Fork，head改成原作者的，然后发起Pull Request，接着在自己项目的Request页面合并，今天Intern repo里更新的资料就同步到我的repo中了

- 这可能是一个比较取巧的方法，有待进一步学习

### 在Reposiory中设置目录时如何新建文件夹？
-  文件夹与文件用 / 隔开，例如home/test.md就在该仓库下创建了一个文件夹home，该文件夹下有一个新的文件test.md 

### 如何在Github中添加本地图片 ？
- Github 图片链接格式： 叹号! + 方括号[ ] + 括号(图片的URL ) 
- URL是图片的在线链接，如果是本地图片的话就没有URL
- 一个可行的方法是在自己的项目目录里新建一个Picture文件夹，将本地图片uplaod files到该文件夹中，之后打开图片就可以右键选择复制图片地址得到URL
- 亲测有效但稍显繁琐

