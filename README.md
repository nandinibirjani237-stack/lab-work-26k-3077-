# lab-work-26k-3077-
# task 1
#include <stdio.h>
int main(){
    int age;
     float marks;
    printf("enter marks");
     scanf("%f",&marks);
    printf("enter age");
    scanf("%d",&age);
        
   
    if (age>=18){
        if(marks>=50){
            printf("you are eligible");
        }
            else{
    printf("you are not eligible");    
    }
} else{
    printf("you are not eligible"); }
}
 # task 2
 #include <stdio.h>
int main(){
    char cnic;
    char driving_license;
    printf("enter cnic if yes write 1 if no write 0");
     scanf(" %c",&cnic);
    printf(" driving license test pass say y if no then write n");
    scanf(" %c",&driving_license);
        
   
    if (cnic=='1'){
        if(driving_license=='y'){
            printf("License Can Be Issued");
        }
            else{
    printf("appropriate message.");    
    }
} else{ printf("appropriate message.");
    }
}

# task 3
#include <stdio.h>
int main(){
   int department;
    int section;
    printf("select the department (1 for cs, 2 for IT ,3 for AI) ");
    scanf("%d",&department);
    printf("select the section (1 for section A , 2 for section b )");
    scanf("%d",&section);
    
    switch(department){
        case 1: 
        printf("cs");
        switch(section){
        case 1 : 
        printf("section A");
         break;
            case 2 : 
        printf("section b");
         break;
         default :
        printf("invalid choices");
            break;
        }break;
        
        
            case 2 : 
        printf("information technology");

        switch(section){
             case 1 : 
        printf("section A");
         break;
            case 2 : 
        printf("section b");
         break;
         default :
        printf("invalid choices");
    }break;
        
            
       case 3 : 
        printf("AI");
    
    switch(section){
             case 1 : 
        printf("section A");
         break;
            case 2 : 
        printf("section b");
         break;
        
       
        default :
        printf("invalid choices");
        break;
    } break;
     default :
        printf("invalid choices");
    }
}

 # task 4
 #include <stdio.h>
int main(){
    int marks;
    printf("enter the marks");
    scanf("%d",&marks);
     ( marks >=50) ? printf("pass") : printf("fail");
    return 0;
    printf("appropriate message.");
    }
}
