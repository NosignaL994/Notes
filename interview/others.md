## 单元测试

对代码最小可测试单元进行验证。单元测试 UTDD 主要面向开发，主要关注软件内部的质量。

单元测试可以有效地降低程序出错的机率，确保代码的健壮性，更深入地理解代码，提供准确的文档，并帮助改进设计方案等等。

需要单测覆盖的代码：逻辑复杂不易理解的、公共代码、核心业务代码。

## 包管理工具

### package.json

描述项目以及项目依赖的模块信息。指定命令脚本。

### package-lock.json

是在包管理工具更改项目依赖的时候生成的。主要用来描述项目的依赖树并进行版本固定，`npm install` 会根据 package-lock.json 进行依赖安装。

### pnpm
