# Logica2
Questões de logica
int main()
{
    int ct,hdlt,tgd,ldl;
    
    scanf("%d\n%d\n%d",&ct,&hdlt,&tgd);
    
    ldl = ct - hdlt - (tgd * 0.2);
    
    if(ldl<100)
    printf("Otimo");
    else if(ldl>99 && ldl<130)
    printf("Sub-otimo");
    else if (ldl>129 && ldl<60)
    printf("Limitrofe");
    else if (ldl>159 && ldl<190)
    printf("Alto");
    else if(ldl>190)
    printf ("Muito Alto");
    
    return 0;
}
