# HEXO个人博客
## 前言

搭建博客查看了很多教程，从这些教程中获益良多，但还是浪费了很多时间，整理下就凑够了我的第一篇博客，希望可以帮助那些急需搭建个人博客的人。自己目前能做到的就是收集和整理前辈们的经验，把它写下来的主要目的是为了给自己做个总结，并且留个底，方便以后查看。做得简陋，请多多包涵。

## Github +HEXO搭建个人博客详细教程

**注明**： 以下PPT内容来源于英格科技共享群。 


**省时小技巧**：[将HTML文件转换为MD文件](https://www.cnblogs.com/KHZ521/p/13952002.html) 

## hexo常用指令：
hexo new "title" 新建文章(md文件)，title为文章的标题
hexo new page "pagename" 新建网页，pagename为网页的名称
hexo clean 清除部署的緩存
hexo n == hexo new 新建一篇文章
hexo g == hexo generate 生成静态页面
hexo s == hexo server 本地部署，可预览网站，默认端口为4000，浏览器输入localhost:4000即可进入网站进行预览，回到git-bash按ctrl+c退出预览(退出后localhost:4000失效)
hexo d == hexo deploy 将网站部署到GitHub
hexo g -d 生成页面并部署到GitHub
hexo g -s 生成页面并本地部署进行预览

## Butterfly 主题设置
**注明**：主题中的个人文件不要放在Hexo根目录的source文件夹里的源文件夹中，升级主题会覆盖掉，可以在source文件夹里新键文件夹。引用文件为：/文件夹名/文件名。
### 一般配置
官网：https://butterfly.js.org/posts/4aa8abbe/#頂部圖   
**注明**： 因为是外国网站，有时候网站打开太慢，有时候打不开，建议使用代理。  

###  功能配置
#### Hexo增添搜索功能
引用：https://www.jianshu.com/p/d388119a90ec
#### Hexo搜索引擎收录
github上的免费域名不能用，要自己购买域名。因为github不允许百度爬取。
github使用百度爬取：https://segmentfault.com/a/1190000002953535    
未尝试！
#### 添加Valine评论
官网：https://butterfly.js.org/posts/ceeb73f/#評論  
官方文档：https://valine.js.org/quickstart.html
补充： https://blog.csdn.net/blue_zy/article/details/79071414
#### 添加Artitalk说说
Butterfly文档：https://butterfly.js.org/posts/4073eda/#説説
参考文档：https://blog.csdn.net/weixin_58068682/article/details/116612753
#### 指定页面配置
官网：https://butterfly.js.org/posts/dc584b87/#Front-matter