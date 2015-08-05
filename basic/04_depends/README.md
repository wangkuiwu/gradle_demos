
这里定义了两个task：hello和intro；并且intro是依赖于hello的。就是说，执行intro的话，会先执行hello。

指令1：`gradle -q hello`

指令2：`gradle -q intro`


