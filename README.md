# Java-Types-Variables-Branching
#include <stdio.h> 

int global;

int main()
{
    //illegal field name
    int 1illegal;
    char space separated;
    
    //legal field name
    int legal;
    char space_separated;
    
    int local;
    
    printf("%d",1illegal);
    printf("%c",space separated);
    
    
    printf("%d",legal);
    printf("%d",space_separated);
    
    
    printf("%d",local);
    printf("%d",global);
}

main.c 5 int main() 6 { 7 //illegal field name 8 int lillegal; 9 char space separated; 10 11 //Legal field name 12 int legal;

Correct the errors
#include <stdio.h> 

int global;

int main()
{
    //illegal field name
    //int 1illegal;
    //char space separated;
    
    //legal field name
    int legal;
    char space_separated;
    
    int local;
    
    //printf("%d",1illegal);
    //printf("%c",space separated);
    
    
    printf("%d ",legal);
    printf("%d ",space_separated);
    
    
    printf("%d ",local);
    printf("%d ",global);
}

