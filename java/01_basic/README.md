
该工程演示了"gradle构建最基本的java工程的相关内容"

### 1. 构建工程

**第1步**：切换到当前目录

    $ cd .../01_basic

**第2步**：编译工程

    $ gradle build

说明：`gradle build`则会执行生成compileJava, jar, assemble, test等人物。

## 2. 运行HelloWorld

**第1步**：切换到包所在的目录

    $ cd build/classes/main

**第2步**：运行HelloWorld

    $ java com.skw.hello.HelloWorld

输出如下：

    hello, world

其他关键点说明：  
(1) src/main/java是gradle中java源码的默认存放路径。  
(2) src/main/resources是gradle中java资源的默认存放路径。  
