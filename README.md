# 05310b
#include <iostream>

using namespace std;

int main()
{
    int a,b,c,d;
    setlocale(LC_ALL, "Russian");
    cout << "введите первое число: " << endl;
    cin>> a;
    cout << "введите второе число: " << endl;
    cin>> b;
    cout << "введите третее число: " << endl;
    cin>> c;
    cout << "введите четвертое число: " << endl;
    cin>> d;
    cout << "сумма равна: " << a+b+c+d << endl;
    cout << "среднее арифметическое равно: " << (float)((a+b+c+d)/3) << endl;
    cout << "сумма квадратов: " << a*a+b*b+c*c+d*d << endl;
    cout << "сумма чесел в третей степени: " << a*a*a+b*b*b+c*c*c+d*d*d << endl;

    return 0;
}
