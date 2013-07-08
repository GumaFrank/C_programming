C_programming
=============
// writting an error message in c just like a try- catch block in java
// when the user doesn't type in Y or N, the computer is going to tell him
// that he nust enter a Y or N to continue.

#include <stdio.h>
 main(void)
 {
   char ans;
   printf("Do you want to continue (Y/N)?");
   scanf("%c", &ans); // this gets user's answers
   
   while ((ans !=|y|) &&(ans !=|N|) )
   {
   printf("\n You must type a Y or an N \n");
   printf("Do you want to continue (Y/N)?");
  scanf("%c", &ans);
   
   }
  return 0;
 }
