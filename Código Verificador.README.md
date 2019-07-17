# Logica2
Questões de logica
int main()
{
    int num,m,c,d,u,s1,s2,m3,s3,r,j;

scanf("%d",&num);

if (num > 9999){
printf("Invalido");    
}
else {
    
m = ( num / 1000);
c = (num / 100);
d = (num % 100/10);
u = (num % 10);
s1 = m + d;
m3 = s1 * 3;
s2 = c + u;
s3 = m3 + s2;
r = s3  % 10;
j = 10 - r;
  
printf("%d%d",num,j);
}
    return 0;
}
