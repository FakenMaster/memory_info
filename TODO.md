使用platform view或者某个跨平台接口，实现当前平台的系统内存数据

#1 需要的内容：总内存，当前已用内存/当前可用内存，已用内存分布，哪些应用程序在占用：
所以这个跨平台插件的功能，就是MemoryInfo：totalMemory，usedMemory，freeMemory，memoryApplicationInfo