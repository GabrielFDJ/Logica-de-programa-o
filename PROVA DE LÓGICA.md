# Logica2
Questões de logica
int main()
{
    int n;
    int q1,q2,q3;
    int r1,r2,r3;
    int soma,rd;
    
    scanf("%d",&n);
    
    q1 = n/7;
    r1 = n % 7; 
    
    q2 = q1/7;
    r2 = q1 % 7; 
    
    q3 = q2/7;
    r3 = q2 % 7; 
    
    soma = r1+r2+r3+q3;
    rd = soma % 7;
    
    printf("%d%d",n,rd);
    

    return 0;
}
