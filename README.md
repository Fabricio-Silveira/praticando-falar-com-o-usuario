# praticando-falar-com-o-usuario
- - - - - - - - - - - - - - - - - - -
#include <stdio.h>
#include <stdlib.h>

int main()
{

    char nome [256];
    char sobrenome [256];
    int ano_nascimento;
    int idade;
    char alternativa[3];

    printf ("Ola Usuario, Qual o seu nome ?\n");
    scanf ("%s",nome);

    printf ("\nLegal, %s. . . Qual a sua idade ?\n",nome);
    scanf ("%d",&idade);

    printf("\n show, o %s tem %d anos\n" ,nome,idade);
    printf("\nAgora, %s Qual seu sobrenome ?\n",nome);
    scanf("%s", sobrenome);

    printf("\nBeleza, qual o seu ano de nascimento ?\n");
    scanf ("%d",&ano_nascimento);

    printf ("\nperfeito, Entao ate agora nos sabemos que o seu nome completo e %s %s e que voce nasceu em %d tendo agora %d anos, certo?\n",nome,sobrenome,ano_nascimento,idade);
    scanf ("%s",alternativa);

    return 0;
}
