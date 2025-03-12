# first-repository
#include <stdio.h>

int sum(int a, int b)    //덧셈
{
    return a+b;
}

int multiply(int a, int b)    //곱셈
{
    return a*b;
}

int sub(int a, int b)    //뺄셈
{
    return a-b;
}

int divide(int a, int b)    //나눗셈
{
    return a/b;
}

int mod(int a, int b)    //나머지연산
{
    return a%b;
}

int main()
{
    int a = 5;
    int b = 10;

    printf("덧셈 : a+b = %d + %d = %d\n", a,b,sum(a,b));
    printf("곱셈 : a*b = %d * %d = %d\n", a,b,multiply(a,b));
    printf("뺄셈 : a-b = %d - %d = %d\n", a,b,sub(a,b));
    printf("나눗셈 : a/b = %d / %d = %d\n", a,b,divide(a,b));
    printf("나머지연산 : a%%b = %d %% %d = %d\n", a,b,mod(a,b));
    
    return 0;
}
