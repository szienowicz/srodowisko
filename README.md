#rozwiazania

zad1
```c
#include <stdio.h>
int main()
{
int i
int tabela[]={1,2,4,6,12};
for (i=4; i>=0; i=i-1)
printf("%i", tabela[i]);
return 0;
}
```

zad2
```c
include <stdio.h>

main ()
{
int i,n,suma;
suma=0;
printf("podaj liczbe\n");
scanf("%i",&n);
for (i=1; i<=n; i=i+1)
suma=suma+i*i;
printf("podana liczba to %i\n",suma);
}
```

zad3
```c
#include <stdio.h>

main ()
{
int n1,n2,n3;
n1=5+3*8/2-3;
n2=2%2+2*2-2/2;
n3=2*4*(5+9/2);
printf("n1=%i\n",n1);
printf("n2=%i\n",n2);
printf("n3=%i\n",n3);

}
```

zad4
```c
#include <stdio.h>

int main ()
{
int a,tabela []={1,2,4,6,12};
for (a=4; a>=0; a--)
printf("%i\n ",tabela[a]);
return 0;

}
```
zad4
```c
#include <stdio.h>

int main ()
{
int a,b;
for (a=1; a<2011; a=a*2)
printf("%i\n ",a);
return 0;

}
```

zad5
```c
#include <stdio.h>

int main ()
{
int a,b;
a=1;
while (a<=2010){
printf("%i\n ",a);
a=a*2;}
return 0;

}
```

zad6 
```c
#include <stdio.h>
main(){
int liczba=8;
int i;
int wynik[20];
printf("Podaj liczbę w systemie 10: ");
scanf("%i",&liczba);
i=0;
while(liczba!=0)
{
    wynik[i]=liczba%2;
    printf(" RESZTA %i przez 2 = %i ",liczba,wynik[i]);
    liczba=liczba/2;
    printf(" PO PODZIELENIU LICZBA =  %i \n", liczba);
    i++;
}
printf("\nWYNIK:");
for(i=i-1;i>=0;i--) printf(" %i ",wynik[i]);


}
```




