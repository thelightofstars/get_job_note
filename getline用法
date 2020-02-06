# get_job_note
for c++
1、getline是string模板类下的一个函数，功能是读取证行的语句
其原型为
istream& getline ( istream &is , string &str , char delim );
其中 istream &is
表示一个输入流，譬如cin；string&str表示把从输入流读入
的字符串存放在这个字符串中（可以自己随便命名，str什么
的都可以）；
char delim表示遇到这个字符停止读入，在不设置的情况下系统默
认该字符为'\n'，也就是回车换行符（遇到回车停止读入）
。给大家举个例子：

string line;
cout<<"please cin a line:"
getline（cin,line,'#');
cout<<endl<<"The line you give is:"<<line;
那么当我输入"You are the #best!"
的时候，输入流实际上只读入了"You are the
"，#后面的并没有存放到line中（应该是在缓冲区里吧）。
然后程序运行结果应该是这样的：

please cin a line:You are the #best!
The line you give is:You are the

2、头文件
用法一：
#include<string>
string str;
getline(cin,str)

用法二：
限制长度：
char str[100];
cin.getline(str,100)；


