#include <stdio.h>

int main(void) {
	
	int num = 0;
	
	printf("\nDigite um numero: ");
	scanf(" %d", &num);
	
	if (num == 0){
		printf("\nNumero igual a 0.\n\n");
	}
	else if(num > 0){
		printf("\nNumero Positivo.\n\n");
	}
	else{
		printf("\nNumero Negativo.\n\n");
	}
	
	return 0;
}
