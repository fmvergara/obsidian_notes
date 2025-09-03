```C
#include<stdio.h> 
int main(){ return 0; } 
printf("lapmos.com") 
int variable_name; char var; 
loat var_name; 
double variable_name;

 // new line: Add new line \n 
 // Null: The null character is usually used to terminate a string. \0 

switch(/*expression*/){ 
case 1 : /*statement*/ break; 
case 2 : /* statement */ break; 
.... 
default : /* default statement */ 
} 

return_type name_function(data_type parameter ...){ // code of the function 
}

data_type = *variable_name; //pointer 
data_type array_name[array_size]; 
arr[index_no]; //access value in array 
char string_name[string_size]; //string is a 1D character array terminated by (\0)
strlen(string_name); 
strcpy(destination, source); 
strcat(first_string, second_string); //concat 
strcmp(first_string, second_string); //compare 
struct structure_name { datatype member1; datatype member2; ... .... ... }; //typedef allows user to provide alternative names for the primitive and user-defined data type. 
struct structure_name { datatype member1; datatype member2; ... ... ... }; typedef structure_name new_name; //OR 
typedef struct structure_name { datatype member1; datatype member2; ... ... ... }name; 
// File Pointer 
FILE *filepointer; filePointer = fopen(filename.txt,w); //open file 
fscanf(FILE *stream, const char *format, ...); //read 
fprintf(FILE *fptr, const char *str, ...); //write 
fgetc(FILE *pointer); //reads character from a file opened in read mode
fputc(char, FILE,*pointer); //writes character to file opened in write mode
fclose(filePointer); 
ptr = (TypeCast*)malloc(size()); 
ptr = (TypeCase*)calloc(n,size);
free(ptr);
ptr = realloc(ptr, x); 

//Looping through char array 
const char *os_types[] = {"Mac", "X11", "Windows", "Linux"}; /* decisions are made here */ 
for (int i = 0; i < sizeof(os_types)/sizeof(os_types[0]); i++) { }
```

**To find out the number of elements in an array :  sizeof(arr) / sizeof(arr[0])**