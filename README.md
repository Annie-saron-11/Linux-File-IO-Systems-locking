# Linux-File-IO-Systems-locking
Ex07-Linux File-IO Systems-locking
# AIM:
To Write a C program that illustrates files copying and locking

# DESIGN STEPS:

### Step 1:

Navigate to any Linux environment installed on the system or installed inside a virtual environment like virtual box/vmware or online linux JSLinux (https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192) or docker.

### Step 2:

Write the C Program using Linux IO Systems locking

### Step 3:

Execute the C Program for the desired output. 

# PROGRAM:

```
1)


#include <stdio.h>

int main() {
    int a = 21, b = 22;
    int and_result, or_result;

    and_result = a & b;      or_result = a | b;  
    printf("Bitwise-AND result is = %d\n", and_result);
    printf("Bitwise-OR result is = %d\n", or_result);

    return 0;
}



2)


#include <stdio.h>

int main() {
    int amount;
    int n100, n50, n20, n2, n1;

       printf("Enter the amount: ");
    scanf("%d", &amount);

    
    n100 = amount / 100;
    amount = amount % 100;

    n50 = amount / 50;
    amount = amount % 50;

    n20 = amount / 20;
    amount = amount % 20;

    n2 = amount / 2;
    amount = amount % 2;

    n1 = amount / 1;
    amount = amount % 1;

        printf("There are:\n");
    printf("%d Note(s) of 100.00\n", n100);
    printf("%d Note(s) of 50.00\n", n50);
    printf("%d Note(s) of 20.00\n", n20);
    printf("%d Note(s) of 2.00\n", n2);
    printf("%d Note(s) of 1.00\n", n1);

    return 0;
}



3)


#include <stdio.h>

int main() {
    char ch = '9';  // Given value

       (ch >= 'A' && ch <= 'Z') ? printf("Uppercase Letter\n") :
    (ch >= 'a' && ch <= 'z') ? printf("Lowercase Letter\n") :
    (ch >= '0' && ch <= '9') ? printf("Number\n") :
    printf("Special Character\n");

    return 0;
}



4)


#include <stdio.h>
#include <string.h>
#include <ctype.h>

int main() {
    char str[50];

        printf("Enter a string: ");
    scanf("%s", str);

        for(int i = 0; str[i] != '\0'; i++) {
        str[i] = tolower(str[i]);
    }

       printf("Lower case String is:%s\n", str);

    return 0;
}



5)


#include <stdio.h>

int main() {
    char str1[50], str2[50];
    int i, flag = 0;

    printf("Enter first string: ");
    scanf("%s", str1);
    printf("Enter second string: ");
    scanf("%s", str2);
    for(i = 0; str1[i] != '\0' || str2[i] != '\0'; i++) {
        if(str1[i] != str2[i]) {
            flag = 1;
            break;
        }
    }
    if(flag == 0)
        printf("strings are same\n");
    else
        printf("strings are not same\n");

    return 0;
}

'''
<img width="512" height="2843" alt="image" src="https://github.com/user-attachments/assets/4f44a7a5-97be-4bb1-8412-1d6938637bd2" />


## 1.To Write a C program that illustrates files copying 







## 2.To Write a C program that illustrates files locking




## OUTPUT





# RESULT:
The programs are executed successfully.
