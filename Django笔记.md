#Django 笔记

**主要用来记录写代码过程中比较难记忆的点**

* django.conf.urls.include 函数的正则表达式末尾没有$，而是一个斜线。当Django 遇到include() 的时候，会将URL 中之前匹配的字符串去掉，然后剩下的字符串交由include 指定的urlConf 做处理。
