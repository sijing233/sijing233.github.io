
## Introduction

~~~
run: bundle exec jekyll serve
~~~

## Directory Structure

~~~terminal
.
├── Gemfile  
├── Gemfile.lock
├── README.md
├── _config.yml     #存储配置数据
├── _includes       #匹配布局和帖子
│   ├── disqus.html     
│   ├── footer.html
│   ├── head.html
│   ├── header.html
│   └── pagination.html
├── _data           #web数据，化身引擎自动加载
├── _layouts        #包装帖子的模板
│   ├── categories.html
│   ├── default.html
│   ├── page.html
│   ├── post.html
│   └── tags.html
├── _note           #存储各种学习笔记
│   └── readme.md
├── _posts          #存储每天的采坑记录，每周归类一次，以标签判断是否已归类
│   ├── 2016-01-08-welcome-to-jekyll.markdown
│   └── readme.md
├── _sass           #css样式
│   ├── animate.scss
│   ├── monokai.scss
│   ├── tables.scss
│   └── uno.scss
├── _site           #jekyll完成转换后生成的站点位置，ignore
├── about.md        #介绍，联系方式等
├── categories.md  
├── css             #css样式
│   └── main.scss
├── feed.xml        
├── fonts           #图标
│   └── foundation-icons
├── humans.txt
├── images          #页面图片
│   ├── cover.jpg
│   ├── favicons
│   └── profile.jpg
├── index.html      # 首页
├── js
│   └── main.js  
├── sitemap.xml
└── tags.md
~~~


## jekyll-uno

- jekyll-uno: https://github.com/daleanthony/Uno

