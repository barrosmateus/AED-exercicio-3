# AED-exercicio-2

#include <stdio.h>

main(){
    
    int anonascimento, anoatual, idade, idade2;
    
    printf("em que ano voçe nasceu?");
    scanf("%i", &anonascimento);
    
    printf("em que ano estamos?");
    scanf("%i", &anoatual);
    
    idade = anoatual - anonascimento;
    idade2 = 2028 - anonascimento;
    
    printf("voçe tem %i anos.\n e vai ter %i anos em 2028", idade, idade2 );
    
}
