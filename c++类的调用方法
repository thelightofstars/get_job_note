# get_job_note
for c++

例子code：


#include <iostream>
using namespace std;
class Dog
{
private:
    int age;
    char name[10];
public:
    Dog();
    void setAge(int age); 
    int Age();   
};
Dog::Dog()
{
 
}
void Dog::setAge(int age)
{  
    this->age=age;
}
int Dog::Age()
{   
    return age;
}
 
int main()
{
    Dog dog;
    dog.setAge(2);
    cout<<"Age="<<dog.Age()<<endl;
 
    Dog *dog1=new Dog();
    dog1->setAge(3);
    cout<<"Age="<<dog1->Age()<<endl;
 
    return 0;
}


你可以看到main中的两种方式。
类是模板：Dog
实例化一个类：Dog dog;或者Dog *dog1=new Dog();
调用类中的方法：dog.setAge(2);或者dog1->setAge(3);
或者调用类中的属性：age，name等（此例因为，这二者定义为私有，所以不直接调用，而是通过成员函数调用）


自己的测试代码：在二维数组中找出目标
#include<iostream>
#include <string.h>
#include<vector>
using namespace std;
class Solution {
public:
	bool Find(int target, vector<vector<int> > array) {
		bool a = 0;
		for (int i = 0; i < array.size(); i++)
			for (int j = 0; j < array[0].size(); j++)
			{
				if (array[i][j] == target)
				{
					a = 1; break;
				}
			}
		return a;
	}
};
int main()
{
	vector<vector<int>> vec(5, vector<int>(3, 0));
	Solution sol;
	bool a = sol.Find(0, vec);
	cout << a << endl;
	cout << vec.size() << endl;
	cout << vec[0].size() << endl;
}
