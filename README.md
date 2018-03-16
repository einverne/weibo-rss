# weibo-rss
把微博内容转成 RSS Feed，支持长微博，表情，图片，链接的输出

原始项目地址: <https://github.com/zgq354/weibo-rss>

## 使用

    docker build -t weibo-rss .
    docker run -p 3000:3000 -d --name weibo-rss --restart=always weibo-rss


如果自己搭建，相应的链接为：  

- 程序主页：http://example.com/  
- RSS地址：http://example.com/rss/{微博博主的uid}  

## 依赖

环境：Node.js >= v6.9.0  

参考[项目Wiki](https://github.com/zgq354/weibo-rss/wiki)  

From: <https://einverne.github.io/post/2018/02/self-hosted-weibo-to-rss.html>

## License
MIT
