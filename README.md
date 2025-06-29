#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main(){
int nombremystere,nombreutilisateur essais=0;
int min=1 ,max=100;
srand(time(NULL));
nombremystere=rand()%d(max-min+1),min;
printf(“bienvenue dans le jeu de devinette!\n“);
printf(“j‘ai choisi un nombre entre %d et %d devine-le\n“,min,max);
do{
printf(“choisir un nombre:“);
scanf(“%d“,&nombreutilisateur);
essais++;
if (nombreutilisateur<nombremystere){
printf(“trop petit! essayer encore.\n“);
} 
else if(nombreutilisateur>nombremystere){
printf(“trop grand! essayer encore.\n“);
}
else{
printf(“Bravo !tu as trouve le nombre mystere en %d essais.\n,essais);
}while( nombreutilisateur!=nombremystere);
return0;
}
