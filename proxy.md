# npm 加速代理

```
npm config set proxy=http://127.0.0.1:7890
```

## 一些代理参数:

```
# 全局路径，也就是 npm install -g，这里 -g 的意义
npm config set prefix="c:\nodejs"

# 一般使用 goagent 翻墙，他的默认端口是 8087
npm config set proxy=http://127.0.0.1:8087

# 设置 https 的代理
npm config set https_proxy=http://127.0.0.1:8087

# 这个地方记得设置下，别搞了个代理，结果在国内源下载
npm config set registry=http://registry.npmjs.org
```

