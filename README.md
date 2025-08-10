# exp8_multidimensionalArray

AIM:
     
       To study and implement C++ 2D Array - Matrices

SOTWARE USED:

        VS Code

OBJECTIVE:

       /*


Objectives:

      1. Understand the structure and usage of 2D and multidimensional arrays.
      2. Implement dynamic memory allocation for arrays using pointers.
      3. Perform input, output, and traversal operations on arrays.
      4. Analyze memory layout and access patterns in multi-level arrays.
      5. Strengthen programming skills through practical experimentation.

Theory:

      - Arrays are collections of elements of the same data type stored in contiguous memory.
      - A 2D array is essentially an array of arrays, often visualized as a matrix.
              Example: int arr[3][4]; // 3 rows, 4 columns
      - Multidimensional arrays extend this concept to more than two dimensions.
              Example: int arr[2][3][4]; // 3D array
      - Dynamic memory allocation allows arrays to be created at runtime.
              Example for 2D array:
     int** arr = new int*[rows];
    for (int i = 0; i < rows; i++) {
        arr[i] = new int[cols];
    }
      - Traversal is done using nested loops:
    for (int i = 0; i < rows; i++) {
        for (int j = 0; j < cols; j++) {
            cout << arr[i][j] << " ";
        }
        cout << endl;
    }
      - Memory must be deallocated to prevent leaks:
    for (int i = 0; i < rows; i++) {
        delete[] arr[i];
    }
    delete[] arr;


       
SAMPLE OUTPUT:

      1. addition of two matrix-
                 Enter the number of rows: 2
                 Enter the number of columns: 2
                 Enter the number of rows m2: 2
                 Enter the number of columns m2: 2
                 
                 Enter elements for Matrix 1:
                 Enter element at (1,1): 1
                 Enter element at (1,2): 3
                 Enter element at (2,1): 4
                 Enter element at (2,2): 5
                 
                 Enter elements for Matrix 2:
                 Enter element at (1,1): 3
                 Enter element at (1,2): 1
                 Enter element at (2,1): 6
                 Enter element at (2,2): 8
                 
                 Sum of the matrices:
                 4 4 
                 10 13 

      2. displaying a matrix-
                Enter the number of rows: 2
                Enter the number of columns: 3
                Enter elements of the matrix:
                4 5 6 7 5 1
                The matrix is:
                4 5 6 
                7 5 1 

     3. Addition of diagonal matrix:
                 Enter the number of the rows and columns: 2
                 5
                 Diagonal addition not possible.

     4. Multipilcation of a matrix:
                Enter number of rows for Matrix 1: 2
                Enter number of columns for Matrix 1: 3
                Enter number of rows for Matrix 2: 3
                Enter number of columns for Matrix 2: 2
                Enter elements of Matrix 1:
                2 3 4 5 6 7
                Enter elements of Matrix 2:
                1 2 3 4 5 6
                Resultant Matrix after Multiplication:
                31 40 
                58 76


🔹 Conclusion:
                 
                 This experiment provided hands-on experience with 2D and multidimensional arrays in C++. It demonstrated how to dynamically allocate memory, accept user input, display matrix data, and properly deallocate memory. The exercise reinforced key concepts in array manipulation, 
pointer usage, and memory management—essential skills for efficient programming in C++.
