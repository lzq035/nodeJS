#### Express应用生成器
> express应用生成器是一个快速搭建web项目的工具，可以生成应用骨架

```bash
npm i express-generator -g  # 全局安装应用生成器
express super-admin -e   # 使用ejs模板引擎初始化空白项目
cd super-admin  # 进入项目目录
npm i           # 安装项目依赖项
npm start       # 启动项目，项目的启动信息配置在pack.json文件中
    # 在pack.json文件中的sgripts节点中配置的属性名可以通过npm run 执行
    # start节点可以不加run
```