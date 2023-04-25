# Arrays-
### ARRAY 
 In  an array Multiple variables of the same data type can be stored with corresponding memory addresses. 
 
 The basic syntax to declare an array is:

int myArray[5]; // declares an integer array with 5 elements

![image](https://user-images.githubusercontent.com/91966097/234185422-d0c750d4-5c33-4458-a661-ffb13b4924d0.png)

TO DECLARE AN ARRAY-

Basic syntax to declare an array is 

datatype arrayName[arraySize];

'datatype' is the data type of the elements that will be stored in the array, 'arrayName' is the name of the array, and 'arraySize' is the number of elements that the array can hold.

Initializing Arrays

datatype arrayName[arraySize] = {value1, value2, ..., valueN};

example-
int myArray[5] = {1, 2, 3, 4, 5};

Here, 'datatype' is the data type of the elements that will be stored in the array, 'arrayName' is the name of the array, 'arraySize' is the number of elements that the array can hold, and 'value1' to 'valueN' are the values that you want to assign to the elements of the array.

      #include <stdio.h>
      int main() {
          int myArray[5] = {1, 2, 3, 4, 5};
          printf("The first element of the array is: %d\n", myArray[0]);
          printf("The third element of the array is: %d\n", myArray[2]);
          printf("The last element of the array is: %d\n", myArray[4]);
          return 0;
      }

OUTPUT- 
         The first element of the array is: 1
         
         The third element of the array is: 3
         
         The last element of the array is: 5
