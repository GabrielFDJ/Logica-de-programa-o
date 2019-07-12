# Logica2
Questões de logica
int main()
{
    
    int n,r,d;
    
    scanf("%d",&n);
    
    d = n + 2;
    r = d % 2;
    
    if (r == 0) 
    {
    printf("Subprimo de Chen");
    }
    else if (r > 0){
    printf("Primo de Chen");
    }
    
    
    return 0;
}
