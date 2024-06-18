#include <stdio.h>
#include <string.h>
int main (){
char name(50);
//prompt user to enter friends's name printf("Enter your friend's name;");
fgets(name,sizeof(name),stdin);
//Display the message printf("%s,you are the best!\n",name);
return0;
}
