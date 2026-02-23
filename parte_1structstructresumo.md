// Online C compiler to run C program online
#include <stdio.h>
#include <string.h>


#define TAM 10 //Isso significa:TAM vale 10, Ele está dizendo que a lista terá 10 posições


struct Endereco { //Aqui ele está criando um NOVO TIPO de dado chamado Endereco.
char nome[50];// Campo chamado nome e pode guardar até 49 letras + o caractere final \0.
char rua[100];// Campo chamado rua e pode guardar até 99 letras.
char estado[50];
char cidade[50];
char cep[10];
} //} → termina o bloco da estrutura. ; → obrigatório para finalizar definição de struct.

