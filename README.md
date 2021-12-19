# 05310b
#include <iostream>

using namespace std;

int main()
{
    int a,b,c;
    setlocale(LC_ALL, "Russian");
    cout << "введите первое число: " << endl;
    cin>> a;
    cout << "введите второе число: " << endl;
    cin>> b;
    cout << "введите третее число: " << endl;
    cin>> c;
    cout << "сумма равна: " << a+b+c << endl;
    cout << "среднее арифметическое равно: " << (float)((a+b+c)/3) << endl;
    cout << "сумма квадратов: " << a*a+b*b+c*c << endl;
    cout << "сумма в чесел в третей степени: " << a*a*a+b*b*b+c*c*c << endl;

    return 0;
}
