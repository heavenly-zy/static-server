# 这是一个静态服务器(Static Server)

自动查找对应文件，即静态文件服务器

- [x] 根据请求的URL路径自动匹配public目录下的文件路径
- [x] 支持默认首页
- [x] 根据请求的URL路径的后缀自动添加对应的Content-Type类型
- [x] 请求路径不存在时显示“文件不存在”，并返回404
- [ ] 添加Cache-Control缓存：默认读取当前目录下的http_config.json
- [ ] 上传到npm
