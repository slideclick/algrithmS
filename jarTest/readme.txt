java��jar·������python����
����ǰ��д��import�󣬺���Ϳ���ֱ�������ˡ�
�����дimport����ȫ������
�����ڵ�ǰcp����������edu.princeton.cs.introcs.StdIn
edu���Ŀ¼
�������jar��ѹ��here���Կ���eduĿ¼����������
edu.princeton.cs.introcsĿ¼
Ȼ���ҵ�StdIn����ļ�
�����public static�ĺ���readInt

javac -cp ".;stdlib-package.jar" nQuickFindUF.java
ʧ��




javac -cp ".;stdlib-package.jar" iQuickFindUF.java
Ҳʧ�ܣ���ΪҪȥ�ļ���������һ��

javac -cp ".;stdlib-package.jar" QuickFindUF.java
�ɹ�
֮�����У�
java -cp ".;stdlib-package.jar" QuickFindUF < tinyUF.txt
-------------
In Java, you can refer to an object in a package or class without any import.

You can do so by new java.util.ArrayList().

OTOH, in Python, you always have to import the wanted module somehow: before you can use sys.argv, you have to import sys.

Both can be abbreviated: in Java, you do

import java.util.ArrayList;

...

... = new ArrayList();
in Python, you can do

from sys import argv
and then use it.