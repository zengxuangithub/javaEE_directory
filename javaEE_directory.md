#   java web 目录结构
test
    
    
    | **WEB-INF**   
            | **web.xml**
            | **lib**
            | **classes**
            | tags
            | database.properties
    
    | **META-INF**
    
    
    | index.jsp //   自定义文件
    | js //   自定义目录 
    | css //   自定义目录 
    | images //   自定义目录 
    |  //还可以根据业务增加文件和文件夹
    
## 注意：
1. 粗体字为java规范中的基本文件或者文件夹 不可删除和修改文件或者文件夹名 
2. index.jsp js css images 以及WEB-INF和META-INF文件夹以外的 都为公共目录 都可以被外部网站用户访问



---

- WEB-INF java EE 规范中的命名文件夹 不可更改

- web.xml 应用程序配置文件描述servlet和其它应用组件配置和命名规则

- lib 用于存放各种JAR文件 例如数据库驱动JAR文件

- classes servlet以及其它java编译后生成的.class 字节码文件

- tags标签库  用于存放自定义标签  可自己根据需要修改名字  使用时自己声明
 必须在 jsp 文件头声明为：

```
<%@ taglibprefix="tags" tagdir="/WEB-INF /simpleTags" % >
```
- database.properties 数据库配置文件

- index.jsp  web应用中的jsp页面

- css css 资源文件夹

- iamges图片资源文件夹