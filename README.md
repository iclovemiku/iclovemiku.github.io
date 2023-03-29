
=================================




## 主题安装

安装 Jekyll 本地环境，以便于调试：

```bash
gem install jekyll
jekyll new my-awesome-site
cd my-awesome-site
bundle install
bundle exec jekyll serve
# => 打开浏览器 http://localhost:4000
```

下载原作者主题安装调试：

```bash
git clone https://github.com/alafighting/maupassant-jekyll.git maupassant
cd maupassant
# 当然你也可以选择clone我的这个更改后的博客主题，只需改一下地址即可：
# git clone https://github.com/oukohou/oukohou.github.io oukohou
# cd oukohou
gem install jekyll-paginate
jekyll build
jekyll server
```

