# Github Pages

<https://docs.github.com/en/pages>

## Github Pages页面编译

Github Pages提供静态网页服务器，支持HTML、CSS和JavaScript，另外包括Markdown文档。不支持后端语言执行，包括PHP与Python。

Github建议并且默认使用Jekyll静态网页生成器，因此支持完全由Markdown文件定义基础格式和内容的网站，具体外观由Jekyll主题文件决定。通过创建空文件```.nojekyll```可以通知Github Pages不要使用Jekyll编译Markdown文件，在此以后可换用其他网页生成器。

## 域名

Github为个人/组织的项目提供默认URL

```text
    <username>.github.io/<repo>
<organization>.github.io/<repo>
```

，但也可改为自定域名。

Github可以为自定域名提供TLS及证书。

## 限制

1. 作为**免费网站托管服务**，Github不允许将Github Pages用以**任何商业用途**。

2. Github Pages不应用于传递敏感信息，如密码等。

3. 配额：
    1. 源代码库最大1GB；

    2. 软性限制每月100GB，每小时十个版本。