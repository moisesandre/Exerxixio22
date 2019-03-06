# Exercicio22

#include <stdlib.h>
#include <stdio.h>

int main() {

system("color 0b");
int num, i, resultado = 0;

printf("Digite um numero: ");
scanf("%d", &num);

for (i = 2; i <= num / 2; i++) {
    if (num % i == 0) {
       resultado++;
    }
 }
 if (resultado == 0){
    printf("%d e primo\n", num);}
 else{
    printf("%d nao e primo\n", num);}

 return 0;
}
