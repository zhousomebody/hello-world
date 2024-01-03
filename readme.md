## github官网
https://github.com
## create blog
### 仓库建立
<img width="1080" alt="6f3618aec5b50c29cd6b0e05a8b22ea" src="https://github.com/zhousomebody/zhousomebody.github.io/assets/143860497/07779647-a880-4e06-b341-7873c6bddca5">

登录github并在页面的右上角选择“+”号，然后选择New repository

<img width="1080" alt="a39fd67ae25dcaea67902d57d75cee9" src="https://github.com/zhousomebody/zhousomebody.github.io/assets/143860497/cd7c92d4-32e4-4bc1-824d-6551445376a8">

在为仓库命名时，因为我们是要做个人blog，所以一般都是选用owner.github.io

discript 描述一下自己仓库的作用

public和private选择的时候一般选择public，因为github是一个在线软件源代码托管服务平台，是开源的！若选择private要付费

readme  README文件通常采用Markdown语言，是一个文件，可以记录个人的心得，记录一下详细信息

<img width="1080" alt="49124a207d69fb29bd43ec0a4e75a93" src="https://github.com/zhousomebody/zhousomebody.github.io/assets/143860497/461b9dc1-6f69-4fb6-899c-27db2683859a">

然后点击后面的create repository，便完成了仓库的建立

<img width="1080" alt="55455ef08e2c6dd496d6b713712d3df" src="https://github.com/zhousomebody/zhousomebody.github.io/assets/143860497/c8d0c1a7-b0a8-4f1a-8b0c-22dadf4c1015">

若是仓库建错了，点击齿轮setting，选中general

<img width="1080" alt="aa0f0935be0c6beca1712381a5d3380" src="https://github.com/zhousomebody/zhousomebody.github.io/assets/143860497/9c786c54-7a92-4c4e-a2e1-bc1101cfbdb1">

浏览此页面都最后，选中delete this repository 删除便可

### github pages

<img width="1080" alt="33c51b2d61f2efc15ebcfb0b662d0b9" src="https://github.com/zhousomebody/zhousomebody.github.io/assets/143860497/69c8a803-accf-439a-8ca3-276003dbbe06">

点击setting 选中pages，可能有时候github pages下面哪个site可能会不存在

<img width="1080" alt="0adbd6bf2797ddba0bda690670a92d6" src="https://github.com/zhousomebody/zhousomebody.github.io/assets/143860497/805cd52d-8470-41f8-a406-6a93510df132">

可以先选择build and deployment 下面的source切换GitHub actions 和deploy from branch，然后选中deploy from branch

在选择下面的branch 分支为main，/root 然后save保存

#### GitHub Pages 站点的发布源
GitHub Pages 站点的发布源是存储源文件的分支和文件夹

##### 注意：GitHub Pages 网站是默认公开的，即使该网站的存储库是密封的或内部的。

如果你的存储库中存在的默认发布源，GitHub Pages 将自动从该源发布一个站点。用户和组织站点的默认发布源是存储库的默认分支的根。项目站点的默认发布源是 gh-pages分支的根。

如果希望将站点的源文件保存在不同的位置，可以更改站点的发布源。你可以从库中的任何分支发布你的站点，或者从该分支的库的根目录发布，或者从该分支的 / docs文件夹发布。

如果你选择任何分支的 /docs 文件夹作为你的发布源，GitHub Pages 将读取你发布的站点的所有内容，包括 /docs 文件夹中的 CNAME 文件。例如，当你通过 GitHub Pages 设置编辑你时的自定义域时，自定义域将写入 /docs/CNAME。

#### 静态网站生成器
GitHub Pages 发布任何您静态到存储库的静态文件。您可以创建自己的静态文件或使用静态站点生成器来为您构建站点。您还可以在本地或其他服务器上自定义自己的构建过程。我们推荐Jekyll，一个内置支持 GitHub Pages 的静态站点生成器，并且简化了构建过程。

GitHub 页面将默认使用 Jekyll 来构建您的网站。如果您想使用除 Jekyll 之外的静态站点生成器，请通过在发布源的根目录中创建一个名为 .nojekyll 的空文件来取消 Jekyll 构建过程，然后按照静态站点生成器的说明在本地构建站点。

GitHub Pages 不支持服务器端语言，如 PHP、Ruby 或 Python。

### 版本回滚



