# 网页静态资源加速
>jsDelivr CDN

Github资源在国内加载速度比较慢，因此需要使用CDN加速来优化网站打开速度，jsDelivr + Github 便是免费且好用的CDN，适合小型网站、个人博客网站使用。
# 1.jsdelivr cdn 教程
https://www.cherishspring.cn/archives/jsdelivrcdn.html
# 2.如何通过jsdelivr引用资源？
使用方法如下：
https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径

例如：https://cdn.jsdelivr.net/gh/Notys-dev/cdn@1.0/img/photo.png
```txt
// load any GitHub release, commit, or branch
// note: we recommend using npm for projects that support it
https://cdn.jsdelivr.net/gh/user/repo@version/file

// load jQuery v3.2.1
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/dist/jquery.min.js

// use a version range instead of a specific version
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2/dist/jquery.min.js
https://cdn.jsdelivr.net/gh/jquery/jquery@3/dist/jquery.min.js

// omit the version completely to get the latest one
// you should NOT use this in production
https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js

// add ".min" to any JS/CSS file to get a minified version
// if one doesn't exist, we'll generate it for you
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js

// add / at the end to get a directory listing
https://cdn.jsdelivr.net/gh/jquery/jquery/
```