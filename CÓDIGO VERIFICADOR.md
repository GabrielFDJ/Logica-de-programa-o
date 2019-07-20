# Logica2
Questões de logica
int main()
{
    int num,m,c,d,u,r,v,t;
scanf ("%d", &num);

m = (num / 1000); c = (num % 1000/100); d = (num % 100/10); u = (num % 10); 
r = 3 * (m + d ) + (c + u) ;
v = r % 10;
t = 10 - v;
printf ("%d%d",num, t); 

    return 0;
}
