//this program is written by tanmay tiwari

#include<stdio.h>
  int main()
  {
      float a,b,total;
      char op;
      int num;
      printf("--------------------------------------------------------------------------------------------------------------------------------\n");
      printf(" |enter + for add|\n |enter - for subtract|\n |enter * for multiply|\n |enter / for divide|\n |enter ^ for square|\n |enter percentage sign for percentage|\n |enter $ for cube|\n");
      printf("--------------------------------------------------------------------------------------------------------------------------------\n");
      printf("enter the operator\n");
      scanf("%c",&op);
      switch(op)
      {
        case '+':
        printf("enter the number 1\n");
        scanf("%f",&a);
        
        printf("enter the number 2\n");
        scanf("%f",&b);
        total=a+b;
        printf("total=%f\n",total); 
        break;
      
        case '-':
        printf("enter the number 1\n");
        scanf("%f",&a);
        
        printf("enter the number 2\n");
        scanf("%f",&b);
        total=a-b;
        printf("total=%f\n",total); 
       
        break;
        case '*':
        printf("enter the number 1\n");
        scanf("%f",&a);
        
        printf("enter the number 2\n");
        scanf("%f",&b);
        total=a*b;
        printf("total=%f\n",total); 
       
        break;
        case '/':
        printf("enter the number 1\n");
        scanf("%f",&a);
        
        printf("enter the number 2\n");
        scanf("%f",&b);
        total=a/b;
        printf("total=%f\n",total); 
       
        break;
        case '^':
        printf("enter the number \n");
        scanf("%f",&a);
        
        // printf("enter the number 2\n");
        // scanf("%f",&b);
        total=a*a;
        printf("square=%f\n",total); 
       
        break;
        case '%':
        printf("enter the number 1\n");
        scanf("%f",&a);
        
        printf("enter the number 2\n");
        scanf("%f",&b);
        total=a/b*100;
        printf("percentage=%f\n",total); 
        break;
        case '$':
        printf("enter the number \n");
        scanf("%f",&a);
        total=a*a*a;
        printf("cube=%f\n",total); 
        break;
        default:
        printf("error...please check your operator");
        break;
      }
          
   
   
    return 0;
}
  
