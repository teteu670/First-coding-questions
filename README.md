# First-coding-questions

#include <stdio.h>
#include <math.h>
int main(){


	int n1,aux,soma,contador,dig,num;

	printf("Digite um numero: ");
	scanf("%i",&num);

	for(int i = 1; i <=num;i++){

	aux = i;
	contador=0;
	soma = 0;
	
	while(aux>0){
	
	aux/=10;
	contador++;
	
	}

	aux = num;

	while(aux>0){
	
	dig%=10;
	aux/=10;
	soma += pow(dig,contador);
		
	}

	if(num == soma) printf("Numero de armstrong");}



}