#include <stdio.h>

int main (){

  // Declaration of variables
  int tp1, tp2; // Two variables forvpositions type and salary

  // Data input
  printf("Please advise which group your position is in. Enter:\n 1 for type A.\n 2 for type B.\n");
  scanf("%i",&tp1);
  printf("Perfect! Now enter your salary, numbers only, no commas.\n");
  scanf("%i",&tp2);
  
  // Processing
  if (tp1 == 1 && tp2 <= 1000){
      tp2 = 500;
      printf("Congratulations! You will receive a bonus, linked to your salary, in the amount of $ %i dollars\n", tp2); 
  // Data output, in case the user is type 'A' and earns up to $1000 USD
  }
  else if (tp1 == 1 && tp2 > 1000){ 
      tp2 = 250;
      printf("Congratulations! You will receive a bonus, linked to your salary, in the amount of $ %i dollars\n", tp2); 
  // Data output, in case the user is type 'A' and earn more  than $1000 USD
  }
  else if (tp1 == 1 && tp2 > 2500){ 
      tp2 = 100;
      printf("Congratulations! You will receive a bonus, linked to your salary, in the amount of $ %i dollars\n", tp2); 
  // Data output, in case the user is type 'A' and earn more  than $2000 USD
  }
  else if (tp1 == 1 && tp2 > 5000){ 
      tp2 = 50;
      printf("Congratulations! You will receive a bonus, linked to your salary, in the amount of $ %i dollars\n", tp2); 
  // Data output, in case the user is type 'A' and earn more  than $5000 USD
  }
  else if (tp1 == 2 && tp2 <= 2000){ 
      tp2 = 500;
      printf("Congratulations! You will receive a bonus, linked to your salary, in the amount of $ %i dollars\n", tp2); 
  // Data output, in case the user is type 'B' and earns up to $2000 USD
  }
  else if (tp1 == 2 && tp2 < 5000){ 
      tp2 = 200;
      printf("Congratulations! You will receive a bonus, linked to your salary, in the amount of $ %i dollars\n", tp2); 
  // Data output, in case the user is type 'B' and earns up to $5000 USD
  }
  else if (tp1 == 2 && tp2 > 5000){ 
      tp2 = 100;
      printf("Congratulations! You will receive a bonus, linked to your salary, in the amount of $ %i dollars\n", tp2); 
  // Data output, in case the user is type 'B' and earn more  than $5000 USD
  }
  
 
 returno 0;
 }
