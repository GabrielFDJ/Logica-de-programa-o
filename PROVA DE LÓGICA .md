# Logica2
Questões de logica
int main()
{
    
    int n;
    int q1,q2,q3,q4;
    int r1,r2,r3,r4;
    int soma;
    
    scanf("%d",&n);
    
    q1 = n/2;
    r1 = n % 2; 
    
    q2 = q1/2;
    r2 = q1 % 2; 
    
    q3 = q2/2;
    r3 = q2 % 2;
    
    q4 = q3/2;
    r4 = q3 % 2;
    
    soma = r1+r2+r3+r4+q4;
    
    printf("%d",soma);
    

    return 0;
}
