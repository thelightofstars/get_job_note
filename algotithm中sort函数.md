// for c++

##### 需要头文件
#include <algorithm>

1. **reverse**  
reverse()  
reverse(it,it2) 可以将数组指针在[it,it2)之间的元素或容器的迭代器在[it,it2)范围内的元素进行反转。

2. **sort**   
语法描述：sort（begin，end，cmp），cmp参数可以没有，如果没有默认非降序排序。   
注意：sort()函数的排序：可以对数组元素和结构体数组排序; 对容器排序只能对vector, string,  deque进行sort()    
升序：sort(begin,end,less<data-type>());   
降序：sort(begin,end,greater<data-type>()).
