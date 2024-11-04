# Programando_em_C_5
Trabalhando com a estrutura do switch

código 100% funcional

// Desenvolvedor.: Adalberto Fernnandes
// Sistema Versão.: v1.0

/*
 Estrutura de decisão - Switch case usamos em casos onde tenhamos uma estrutura
 grande ou confusa de if/else/if else.
*/ 

#include<stdio.h>
#include<stdlib.h>
#include<locale.h>

int main(){
	setlocale(LC_ALL, "Portuguese");
	
	int opcao = 0;
	char escolha;	
	
	printf("Escolha um valor (1 - 7): ");
	scanf("%d", &opcao);
		
	switch(opcao){
 		case 1:
 			printf("Domingo");
 			break;
 		case 2:
 			printf("Segunda");
 			break;
 		case 3:
 			printf("Terca");
 			break;
 		case 4:
 			printf("Quarta");
 			break;
 		case 5:
 			printf("Quinta");
 			break;
 		case 6:
 			printf("Sexta");
 			break;
 		case 7:
 			printf("Sábado \n");
 			break;
 		default:
 			printf("Desculpa esse valor escolhido não consta nosso sistema!!!");
	}
		
	return 0;
}
