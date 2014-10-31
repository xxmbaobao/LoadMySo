LoadMySo
========

Android 动态加载so 

(so可以放到sdcard中) 主要通过dlopen(char *sopath)把so 加载到内存中  然后dlsym查找 so中函数符号（函数名，必须是:未提供jni接口的函数）
