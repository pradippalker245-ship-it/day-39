# day-39
c++ pracatice 
#include <iostream>
using namespace std;

class student
{
public:
    int x;
    int y;
    int z;

    void setdata(int a, int b)
    {
        x = a;
        y = b;
    }

    void display()
    {
        cout << "pradip";
    }
};

int main()
{
    student s1;

    s1.setdata(3, 6);
    s1.display();

    return 0;
}
