# c-homeworks
#include<stdio.h> //q3-Calculate circumference or area of a rectangle.  
int width;        //Take inputs from the user. You should first get an integer number for the side of the rectangle.    
int height;       //Then, you should get a character from user. If user enters ‘c’, print circumference of the square.
char typeOf;      //If user enters ‘a’ print area of the square.
      
int area;           
int circumference;      

int main() {
printf("Input sides of rectangle and type c or a= ");
 scanf("%d %d %c", &width, &height, &typeOf);
    
if (typeOf=='c'){
circumference = 2*(height + width);
printf("Circumference of the rectangle = %d \n", circumference);
}

else {
area = height * width;
printf("Area of the rectangle = %d \n", area);
}

return(0);
}
