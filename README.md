# pointer.cpp
include<iostream>
using namespace std;
class A
{
    int a;
    public:
    A& test(int a)
    {
        this->a=a;
        return *this;
    }
    void display()
    {
        cout<<"the value of a is"<<a<<endl;
    }
    };
    int main()
    {
        A a;
        a.test(4).display();
        a.display();
        return 0;
    }
