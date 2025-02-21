首先进入博客的目录：
> cd /Users/anniechen/Documents/FUN/博客

> git add .

> git commit -m "updates"

> git push

如果push不上去，把代理添加进环境变量
> export https_proxy=http://127.0.0.1:7890;export http_proxy=http://127.0.0.1:7890;export all_proxy=socks5://127.0.0.1:7890

等一下github生成，就可以去看效果啦