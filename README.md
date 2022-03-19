# Webstack网址导航

- 这是一个魔改过了[webstack](https://github.com/hassanblog/navigation)
- 原版[webstack](https://github.com/WebStackPage/WebStackPage.github.io)
- 博客框架[Hexo](https://hexo.io/zh-cn/)

## 快速上手🚀

```bash
# 克隆
git clone https://github.com/Geda-999/nav.git

# 进入项目
cd nav

# Hexo 相关组件
npm install hexo-util --save

# 打开命令行中输入 Hexo 三连
hexo clean   #清空缓存
hexo g	     #部署代码
hexo s	     #预览效果
hexo d       #部署上Github
```



==bug问题==

```js
//hexo d 打包完，index.html 打开网页是解析不了css和js 

打开index.html 替换
把 href="/ 替换成 href="./
把 <script src="/ 替换成 <script src="./
```



![](https://cdn.jsdelivr.net/gh/ashunun/Picture/image/WebStack.png)