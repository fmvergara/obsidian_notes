```c
data_type arr_name[size1]; //1D array data_type 
arr_name [size1][size2]; //2D array 
data_type arr_name[size1][size2][size3]; //3D array
```

```C
int arr[5] = { 10, 20, 30, 40, 50 }; // modifying element at index 2 
arr[2] = 100; 
for (int i = 0; i < 5; i++) {
 printf("%d ", arr[i]); 
} 
```

To find out the number of elements in an array :  sizeof(arr) / sizeof(arr[0])