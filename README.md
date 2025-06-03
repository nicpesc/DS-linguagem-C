# DS-linguagem-C

**//Questão 1**

#include <stdio.h>

int main() {
  int x,y;
  
printf("Insira o Numero 1: \n");

scanf("%d", &x);

printf("Insira o Numero 2: \n");

scanf("%d", &y);

printf("Soma: %d" , x+y);

}

return 0;

}

**//Questão 2**

#include <stdio.h>

int main() {

 int numero;
 
printf("Insira um número: \n");

scanf("%d", &numero);

if (numero % 2 == 0) {

    printf("O numero %d é par \n", numero);
    
}
    else {
    
        printf("O numero %d é impar \n", numero)
}

return 0;

}

**//Questão 4**

#include <stdio.h>

int main() {

 int a, b, c, d, e, f;
 
float media;

printf("Selecione o primeiro numero: \n");

scanf("%d", &a);

printf("Selecione o segundo numero: \n");

scanf("%d", &b);

printf("Selecione o terceiro numero: \n");

scanf("%d", &c);

printf("Selecione o quarto numero: \n");

scanf("%d", &d);

printf("Selecione o quinto numero: \n");

scanf("%d", &e);

printf("Selecione o sexto numero: \n");

scanf("%d", &f);

media = (a+b+c+d+e+f)/ 6.0;

printf("A media é: %.2f\n", media);

return 0;

}

**//Questão 5**

#include <stdio.h>

int main() {

int ano;

printf("Insira um ano: \n");

scanf("%d", &ano);

if (ano % 4 == 0 && ano % 100 != 0) {

printf("O ano %d é bissexto.\n", ano);

    } else {
        printf("O ano %d não é bissexto.\n", ano);
    }
    
return 0;

}

**//Questão 7**

#include <stdio.h>

int main() {

int num1, num2, num3, maior;

    printf("digite o primeiro número: ");
    
    scanf("%d", &num1);
    
    printf("digite o segundo número: ");
    
    scanf("%d", &num2);

    maior = num1;
    
    if (num2 > maior) {
    
        maior = num2;
        
    }
    
    if (num3 > maior) {
    
        maior = num3;
    }

    printf("O maior número é: %d\n", maior);

    return 0;
}

**//Questão 8**

#include <stdio.h>

#include <math.h>

int main() {

int numero;

printf ("Selecione um número: \n");

scanf ("%d", &numero);

printf("A raiz quadrada de %d é %.1f \n", numero, sqrt(numero))
;

   return 0;
}


**//Questão 10**

#include <stdio.h>

int main() {

int lado1, lado2, lado3;

printf("digite lado 1: \n");

scanf("%d", &lado1);

printf("digite lado 2: \n");

scanf("%d", &lado2);

printf("digite lado 3: \n");

scanf("%d", &lado3);

if (lado1 + lado2 > lado3 && lado1 + lado2 > lado3 && b + c > a) {
        if (a == b && b == c) {
            printf("Triângulo equilátero.\n");
        } else if (a == b || a == c || b == c) {
            printf("Triângulo isósceles.\n");
        } else {
            printf("Triângulo escaleno.\n");
        }
    } else {
        printf("Os valores informados não formam um triângulo.\n");
    }

    return 0;


