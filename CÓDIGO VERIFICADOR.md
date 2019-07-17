# Logica2
Questões de logica
int main()
{
   
    int num,m,c,d,u;

scanf("%d",&num);

if (num > 9999){
printf("Invalido");    
}
else if(num % 1111==0){
printf("%d",num);    
}
else {

m = (num / 1000);
c = (num / 100);
d = (num % 100/10);
u = (num % 10);
num = ((u * 100) + (d * 10) + c );

printf("%d", num);
}

}
