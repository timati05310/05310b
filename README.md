# 05310b
#include <iostream>

using namespace std;

int main()
{
setlocale(LC_ALL, "Russian");
    int n,Min,x;
    Min = 9999999999999999;
    cout<<"выберите колличество цифор для сравнения: "<<endl;
    cin>>n;
    for (int i = 1; i<n+1; i++)
    {
        cout<<i<<")"<<ends;
        cin>>x;
        if (Min>x)
            Min = x;
    }
    cout<<"минимальное число: "<<Min<<endl;
    return 0;
}
