# get_job_note
for c++

1. memset()函数原型是extern void *memset(void *buffer, int c, int count)        buffer：为指针或是数组, 
              c：是赋给buffer的值,
       count：是buffer的长度.

       这个函数在socket中多用于清空数组.如:原型是memset(buffer, 0, sizeof(buffer))
       Memset 用来对一段内存空间全部设置为某个字符，一般用在对定义的字符串进行初始化为‘ ’或‘/0’；
      例:char a[100];memset(a, ‘/0’, sizeof(a));
      
      
2、例子
初始化:
	char a[1000] = { 0 };
	int arr[127] = { 0 };
  重置：
		memset(arr, 0, 127 * sizeof(int));
		memset(arr, 0,  sizeof(a));//重置数组
		memset(a, 0, 1000);
