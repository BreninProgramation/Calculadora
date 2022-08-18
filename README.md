# Calculadora

#include <stdio.h>
#include <stdlib.h>

int main()
{
    float n1,n2,soma,menos,vezes,divisao;

    printf("\n Digite o primeiro numero:");
    scanf("\n %f",&n1);
    printf("\n Digite o segundo numero");
    scanf("\n %f",&n2);

    soma=n1+n2;
    menos=n1-n2;
    vezes=n1*n2;
    divisao=n1/n2;

    printf("\n Soma:%.0f",soma);
    printf("\n Menos:%.0f",menos);
    printf("\n Vezes:%.0f",vezes);
    printf("\n Divisao:%.0f",divisao);



    return 0;
}
