#include<stdio.h>

int main()
{
  int r,h,hacim,alan;
  int pi=3;
  
  printf("Lutfen silindirin yaricap(r) degerini giriniz?: ");
  scanf("%d",&r);
  printf("Lutffen silindirin yukseklik(h) degerini giriniz?: ");
  scanf("%d",&h);
  
  alan = 2*pi*r*h;
  hacim = pi*r*r*h;
 
  printf("Silindirin Alani %d ve Hacmi %d'dir.",alan,hacim);
  
  return 0;
}
