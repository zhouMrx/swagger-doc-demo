# 生成与 swagger-ui 页面对应的离线文档（html、pdf）
## 使用的插件
> swagger2markup-maven-plugin

> asciidoctor-maven-plugin

## 使用方法
替换 `docs/swagger/swagger.json`
运行 `mvn test` ，即可在 `target/asciidoc` 目录下找到对应的 html 和 pdf 文件