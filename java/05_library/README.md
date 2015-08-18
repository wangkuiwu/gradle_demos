
该工程演示了"如何通过gradle编译jar包，并使用jar包"。

### 1. 编译jar包

**第1步**：切换到lib目录

    $ cd lib

**第2步**：编译jar包

    $ gradle jar
    或
    $ gradle build

说明：  
(1) `gradle jar`单单只会执行生成jar包的任务，而`gradle build`则会执行生成jar包、check、运行test等一系列的任务。  
(2) jar包的路径应该是: **build/libs/HelloLib-0.0.1.jar**


### 2. 使用jar包

**第1步**：切换到libTest目录

    $ cd libTest

**第2步**：编译Test.java

    $ javac -cp ../lib/build/libs/HelloLib-0.0.1.jar Test.java

**第3步**：运行Test.java

    $ java -cp .:../lib/build/libs/HelloLib-0.0.1.jar Test

运行结果：

    Plus: 4+6=10

