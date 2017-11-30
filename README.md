# Loops-in-c
Different Type of loop present in c

1)for Loop:-
 The syntax of for loop is:
 Syntax:
          for (initializationStatement; testExpression; updateStatement)
          {
                  // codes 
          }
          
 Example:
          // Program to print numbers

            #include <stdio.h>
            int main()
            {
                int num, count;

                printf("Enter a number: ");
                scanf("%d", &num);
                // for loop terminates when n is less than count
                for(count = 1; count <= num; ++count)
                {
                    printf("count = %d", count);//print numbers 

                } return 0;
            }

2) while loop :-
The syntax of a while loop is:
Syntax:
            while (testExpression) 
            {
                //codes 
            }
Example:// Program to find factorial of a number
                   #include <stdio.h>
                  int main()
                  {
                      int number;
                      int factorial=1;

                      printf("Enter an integer: ");
                      scanf("%d",&number)
                      // loop terminates when number is less than or equal to 0
                      while (number > 0)
                      {
                          factorial =factorial* number;  // factorial = factorial*number;
                          number=number-1;;
                      }

                      printf("Factorial= %d", factorial);

                      return 0;
                  }
                  
 3)Do....while
 do...while loop Syntax
Syntax:
                      do
                      {
                         // codes
                      }
                      while (testExpression);
 Example:
            // Program to add numbers until user enters zero

                    #include <stdio.h>
                    int main()
                    {
                        double number, sum = 0;

                        // loop body is executed at least once
                        do
                        {
                            printf("Enter a number: ");
                            scanf("%f", &number);
                            sum =sum+ number;
                        }
                        while(number != 0.0);

                        printf("Sum = %.2lf",sum);

                        return 0;
                    }
