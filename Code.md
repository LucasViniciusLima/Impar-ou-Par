# Impar-ou-Par
Uma atividade simples

#include <stdio.h>
#include <stdlib.h>
#include <locale.h>
#include <conio.h>

main()
{
	int num;
	system("color E0");
	setlocale(LC_ALL,"PORTUGUESE");
	printf("Digite um numero: ");
	scanf("%i", &num);
	if ( (num % 2) == 0 )
		printf("O numero %i é par.", num);
	else
		printf("O numero %i é impar", num);
	system("pause > null");
}
