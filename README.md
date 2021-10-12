# ram-webapp-with-mybatis
ram 项目工程原型-mybatis版本

## 使用方法


### 命令行创建

命令行创建(需先安装并配置好maven)：


创建项目目录

```bash
mkdir my-demo-project
cd my-demo-project
```

用原型工程初始化项目：

```bash

mvn archetype:generate -DgroupId=top.beanshell -DartifactId=your-artifact-id -Dversion=1.0.0-SNAPSHOT -Dpackage=top.beanshell -DarchetypeGroupId=top.beanshell -DarchetypeArtifactId=ram-webapp-with-mybatis-archetype -DarchetypeVersion=1.0.0-SNAPSHOT
```

将以上代码中的DartifactId替换为你想要的值，如需替换DgroupId的值，请在生成项目工程之后再修改（在此处修改会导致部分值替换异常）。

### Intellij Idea 创建
