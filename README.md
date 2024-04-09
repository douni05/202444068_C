#include <stdio.h>

int main(){
    int n, product = 1;
    printf("양의 정수를 입력하세요: ");
    scanf("%d", &n);

    int i = n;
    while(i>=1){
        product *=i;
        i++;
    }

    printf("1부터 %d까지의 곱은 %d입니다.\n", n, product);

    return 0;
}
//잘못된 부분은?
