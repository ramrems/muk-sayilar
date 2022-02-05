# muk-sayilar
#include<stdio.h>
int main(){
	int x,y,sayac,toplam;
	y=15000;
	printf("5 ie 15.000 arasindaki mukemmel sayilar:\n");

	for (x=5; x<y; x++)	{

	toplam=0;
	for (sayac=1; sayac<x; sayac++){
	if(x%sayac==0){
	toplam=toplam+sayac;
} }

	if (x==toplam) {

	printf("%d\n",x);}	}
	return 0;
	}
