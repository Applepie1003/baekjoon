#include <stdio.h>

int main(void) {
    int num1 = 0;
    int num2 = 0;
    int oper1 = 0, oper2 = 0, oper3 = 0;
    
    scanf("%d\n %d", &num1, &num2);
    oper1 = num1 * (num2 % 10);
    printf("%d\n", oper1);
    oper2 = num1 * ((num2 % 100) - (num2 % 10)) / 10;
    printf("%d\n", oper2);
    oper3 = num1 * (num2 / 100);
    printf("%d\n", oper3);
    printf("%d\n", oper1 + (oper2 * 10) + (oper3 * 100));
    return 0;
}
