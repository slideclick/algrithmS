java的jar路径不如python清晰
它在前面写了import后，后面就可以直接引用了。
如果不写import就用全称域名
它就在当前cp设置里面找edu.princeton.cs.introcs.StdIn
edu这个目录
或者你把jar解压到here可以看到edu目录里面依次有
edu.princeton.cs.introcs目录
然后找到StdIn这个文件
里面的public static的函数readInt

javac -cp ".;stdlib-package.jar" nQuickFindUF.java
失败




javac -cp ".;stdlib-package.jar" iQuickFindUF.java
也失败，因为要去文件名和类名一样

javac -cp ".;stdlib-package.jar" QuickFindUF.java
成功
之后运行：
java -cp ".;stdlib-package.jar" QuickFindUF < tinyUF.txt