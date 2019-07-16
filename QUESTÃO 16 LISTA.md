# Logica2
Questões de logica
int main()
{
    int num,c,d,u;
    
    scanf("%d",&num);
    
    if (num > 999){
    printf("Invalido");    
    }
    else if(num % 111==0){
    printf("%d",num);    
    }
    else {
    
    c = (num / 100);
    d = (num % 100/10);
    u = (num % 10);
    num = ((u * 100) + d * 10 + c);
    
    printf("%d", num);
    }
    
    
    
    return 0;
}
