# disglair

#include <stdio.h>

int main()
{
    
    
    int not;
    
    printf("Notunuzu Giriniz : ");
    scanf("%d",&not);
    
    
    if(not >100)
        printf("Gecersiz Not\n");
    else if(not<0)
        printf("Gecersiz Not\n");
    else if(not>=90)
        printf("Not : A\n");
    else if(not>=80)
        printf("Not : B\n");
    else if(not>=70)
        printf("Not : C\n");
    else if(not>=60)
        printf("Not : D\n");
    else
        printf("Not : F\n");
    
    
        
}
