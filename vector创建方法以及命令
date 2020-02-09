# get_job_note
for c++
一vector两种赋值方法：
1.push_back(element)方法像vector末尾添加元素；
2.vector vec(address1,address2)，通过截取数组中一顿连续的数值赋值给vector，地址所指元素同样遵循左闭右开。
二示例代码如下：
#include
#include
#include
using namespace std;
int main()
{
int arr[6] = { 1, 2, 3, 4, 5, 6 };
vector vec(arr+1,arr+4);



1 vector二维数组的创建和初始化
std::vector <int> vec(10,90); //将10个一维动态数组初始为90
std::vector<std::vector<int> > vec(row,vector<int>(col,0)); //初始化row * col二维动态数组，初始化值为0
2 获取一维数组的长度
int size = vec.size();
3 获取二维数组的长度
int size_row = vec.size(); //获取行数
int size_col = vec[0].size(); //获取列数
 
4 给vector二维数组赋值
简单的就直接赋值
ans[0][0]=1;
ans[0][1]=2;
ans[1][0]=3;
ans[1][1]=4;


案例：
#include<iostream>
#include <string.h>
#include<vector>
using namespace std;
int main()
{
	vector <int> vec(10, 0);
	vector <vector<int>> vect(5, vector<int>(6, 0));
	cout << vect.size() << endl;
	cout << vect[0].size() << endl;
  
}


命令用法：
1 基本操作
(1)头文件#include<vector>.
(2)创建vector对象，vector<int> vec;
(3)尾部插入数字：vec.push_back(a);
(4)使用下标访问元素，cout<<vec[0]<<endl;记住下标是从0开始的。
(5)使用迭代器访问元素.
<span style="font-size:18px;">vector<int>::iterator it;

for(it=vec.begin();it!=vec.end();it++)

    cout<<*it<<endl;</span>
(6)插入元素：    vec.insert(vec.begin()+i,a);在第i个元素后面插入a;
(7)删除元素：    vec.erase(vec.begin()+2);删除第3个元素
　　　　　　　 vec.erase(vec.begin()+i,vec.end()+j);删除区间[i,j-1];区间从0开始
(8)向量大小:vec.size();
(9)清空:vec.clear()　　　//清空之后，vec.size()为０
