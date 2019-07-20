# Logica2
Questões de logica
int main()
{
    int num,m,c,d,u,r,v;
scanf ("%d", &num);

if (num > 9999) {
    printf ("Invalido"); 
} else if (num % 1111 == 0) {printf ("%d", num); 
} else {

m = (num / 1000); c = (num % 1000/100); d = (num % 100/10); u = (num % 10); 
r = 3 * (m + d ) + (c + u) ;
v = r % 10;
printf ("%d%d",num, v); }

    return 0;
}
