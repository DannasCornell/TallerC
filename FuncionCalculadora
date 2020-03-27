#include <stdio.h>
#include  <math.h>
#include <windows.h>

float Suma (float n1, float n2 );
float Resta (float n1, float n2);
float Mult (float n1, float n2);
float Div (float n1, float n2);
float Potencia (float n1, float n2);
float Raiz(float n1);

int main(){
	
	int opcion;
	
	float n1, n2;
	
	do{
	
		printf("Elige una opci%cn \n", 162);
	
		printf("\t 1.- Suma\n");
	
		printf("\t 2.- Resta\n");
	
		printf("\t 3.- Multiplicaci%cn \n",162);
	
		printf("\t 4.- Divisi%cn \n",162);
	
		printf("\t 5.- Potencia \n");
	
		printf("\t 6.- Ra%cz \n", 161);
	
		printf("\t 7.- Salir \n");
	
		scanf("%d",&opcion);
	
		system("cls");
		
		
		if (opcion==6){
			
			printf("\n Dame el primer valor: ");
	
			scanf("%f", &n1);
	
		}else if(opcion>=7){
	
		}else{
			printf("\n Dame el primer valor: ");
	
			scanf("%f", &n1);
	
			printf("\n Dame el segundo valor: ");
	
			scanf("%f", &n2);
	
		}//fin if-else
		
		switch (opcion)
	
		{
			case 1: 
			
				printf("\n");
			
				printf("\t 1.- Suma\n");
				
				printf("\t El resultado de la suma es: %.2f \n", Suma(n1,n2) );
			
			break; 
			
			case 2:
				
				printf("\n");
				
				printf("\t 2.- Resta\n");
				
				printf("\t El resultado de la resta es: %.2f \n", Resta(n1,n2) );
			
			break;
			
			case 3:
				
				printf("\n");
				
				printf("\t 4.- Multiplicaci%cn \n",162);
				
				printf("\t El reusltado de la multiplicaci%cn es: %.2f \n", 162, Mult(n1,n2) );
	
			break; 
			
			case 4: 
			
				printf("\n");
				
				printf("\t 3.- Divisi%cn \n",162);
				
				if(n2 == 0){
		
					printf("\t La operaci%cn entre 0 no esta definida \n", 162);
		
				}else{
					
					printf("\t El resultado de la divisi%cn es: %.2f \n", 162, Div(n1,n2));
				
				}
			
			break;
	
			case 5:
				
				printf("\n");
				
				printf("\t 5.- Potencia \n");
				
				printf("\t El resultado de la potencia es: %.2f \n", Potencia(n1,n2));
					
	
			break;
			
			case 6:
				
				printf("\n");
				
				printf("\t 6.- Ra%cz \n", 161);
				
				if(n1 < 0){
					
					printf("\n La ra%cz cuadrada de un n%cmero negativo no esta definida\n", 161, 163);
					
				}else{
					
					printf("\n El resultado de la Ra%cz es: %.2f\n", 161, Raiz(n1));
					
				}//fin if-else
					
			break;
			
			case 7: 
				
				printf("\t 7.- Salir \n");
				
				exit(0);
			
			break;
			
			default:
				
				printf("Opci%cn No valida \n",162);
				
		}//fin switch
	
	}while (opcion !=7 );
	
}//fin int main

float Suma(float n1, float n2){
	
	float res = 0;
	
	res = n1 + n2;
	
	return res;	
}//fin funcion Suma

float Resta (float n1, float n2){
	
	float res = 0;
	
	res = n1 - n2;
	
	return res;
}//fin Funcion Resta

float Mult (float n1, float n2) {
	
	float res = 0;
	
	res = n1 * n2 ;
	
	return res;
}// fin funcion Mult

float Div (float n1, float n2){
	
	float res = 0;

	res = n1/n2;

	return res;
	
}//fin funcion Div

float Potencia (float n1, float n2){
	
	float res = 0;
	
	res =  pow(n1,n2);
	
	return res;
	
}// fin Funcion Potencia

float Raiz(float n1){
	
	float res = 0;
	
	res = sqrt(n1);
	
	return res; 
	
} //fin Funcion Raiz 

