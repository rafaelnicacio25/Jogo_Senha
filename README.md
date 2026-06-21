# Jogo_Senha
Trabalho em grupo com objetivo de desenvolver programação em equipe, desenvolvendo um sistema interativo, um jogo.

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int senha[5];
    int palpite[5];
    char nome_jogador[30];
    
    printf("~ Narrador: Voce esta em um mundo cheio de monstros e magias...\n");
    printf("Enquanto se aventurava por ruinas devastadas voce escuta uma voz...\n");
    printf("Tal voz tenta se comunicar com voce...\n");
    printf("Ela comeca com uma voz extremamente animada:\n");
    printf("~ Voz desconhecida:  BRAVO AVENTUREIRO! SEJA BEM VINDO AS RUINAS!!, ME DIGA SEU NOME!\"\n");
    printf("~ Jogador: Quem ta falando?\n");
    printf("~ Voz desconhecida: SOU EU, nao e obvio?! A MAIS PODEROSA, A MAIS CORAJOSA, A MAIS LEGAL!!\n");
    printf("EU MESMO.... A GRANDIOSA LILY!! AGORA DEIXE DE BOBEIRA, ME DIGA SEU NOME!!\n");
    printf("~ Jogador: Prazer! Sou o: ");
    scanf("%29s", nome_jogador);
    printf("\n~ Lily: PRAZER %s! Oque voce veio fazer nessas bandas?\n", nome_jogador);
    printf("~ %s: Ouvi dizer que nesse lugar existe um bau que guarda um tesouro FODA!\n", nome_jogador);
    printf("~ Lily: Ah entendi... entao voce veio atras do tesouro... voce nao veio brincar com a Lily? :C\n");
    printf("~ Narrador: Lily esta decepcionada com voce...\n");
    printf("~ %s: NAO! NAO! Eu posso brincar com voce...\n", nome_jogador);
    printf("~ Lily: EBAAAAA!!!! ENTAO VAMOS JOGAR!!\n");

    return 0;
