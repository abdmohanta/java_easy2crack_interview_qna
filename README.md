0# java_easy2crack_interview_qna
Java Interview Questions and answers from zero to hero.

Q1. What is Java?

Ans : Java is a high-level, object-oriented, robust, secure programming language. It is platform-independent, high-performance, multithreaded, and portable. It was developed by James Gosling in June 1991. It is also known as a platform because it provides its own JRE and API.

Q2. What is Constructor ?

Ans : Constructors should have the same name as that of the class. Whenever an object is created, constructor is called. Constructors do not have any return type.
We can use access modifiers and keywords in constructors. By supplying values to constructors, we can create multiple constructors. In constructor, method name and class name can be same.

Q3. What is Constructor Overloading ?

Ans : Here we create more than one constructor in the same class provided that they have different number of arguments or different types of arguments.

Q4. What is JDK ?

Ans : JDK stands for Java development kit. It helps us to compile .java file to .class file.

Q5. What is JRE ?

Ans : JRE stands for java runtime environment. It helps us to run .class file.

Q6 . What is New Keyword

Ans : New keyword sends request to the class to create object.
New keyword mandatorily calls constructor. Once object is created, then it gets its address and stores that in a reference variable.

Q7 . What is This Keyword ?

Ans : It is a special reference variable that holds object address. This keyword gets created automatically.
This keyword points to current object running in the program.
We cannot use this keyword inside static method.
Using this keyword we can call constructor.

Q8 . What is Constructor Chaining ?

When we call a constructor from another constructor using this keyword then it is called Constructor Chaining.

Q9 . What is Instance Variables ?

Ans : Instance variables in Java are non-static variables which are defined in a class outside any method, constructor or block.

Q10 . What is Static Variable ?

Ans : Static variables can be accessed using class name.
      Static variables can be accessed by static and non-static methods.
      Static variable is like a global variable and is available to all methods.

Q11 . What is Non-Static Variable ?

Ans : Non-static variables can be accessed using instance of a class.
      Non-static variables cannot be accessed inside a static method directly.
      Non-static variable is like a local variable and can be accessed only through instance of a class.

Q12 . What is Inheritance ?

Ans : Here we inherit the members from parent class to child class with an intention of reusing them.

Q13 . What is Packages ?

Ans : Packages are nothing but folders created in Java where programs can be stored in an organized manner.
Packages resolve naming convention problem.

Q14 . What is Advantages of Inheritance ?

Ans : Inheritance minimizes identical code as it allows sharing of common code among subclasses.
 Inheritance makes the code flexible to change.
 With the help of inheritance, we can override the methods of base class.

Q15 . What is Polymorphism ?

Ans : Here we can develop a feature in a way that it can take more than one form.
Polymorphism is applicable only on methods.

There are two ways we can achieve polymorphism:
i) Overriding
ii) Overloading

Q16 . What is Overriding?

Ans : Here we inherit a method from parent class and modify its logic in child class by once again creating same method in child class.

Advantages of Polymorphism (Overriding)

If we inherit 10 methods but want to modify logic of some methods, then the option is overriding.

@Override
@Override annotation checks whether overriding is happening or not. If not, then it reports an error.

Q17. Can we override static method?

Ans: No. In Java static members are not overridden (they are hidden), because overriding is based on inheritance of instance methods.

Q18. What is Overloading ?

Ans: Developing more than one method in the same class provided that they have different number of arguments or different types of arguments is called Overloading.

Q19. Type Casting / Data Type

Ans: Converting particular data type into required data type is called type casting.

There are two types:
I. Auto Up Casting
II. Explicit Down Casting

Q20 . What is Auto Up Casting ?

Ans : Converting smaller data type to bigger data type is called Auto Up Casting. During auto up casting data loss does not happen.

Q21 . What is Explicit Down Casting?

Ans : Here we convert bigger data type to smaller data type. During explicit down casting, chances of data loss may happen.

Q22 . What is Class Up Casting?

Ans . Here we store child class object address into parent class reference variable.

Q23 . What is Class Down Casting ?

Ans . Here we store parent class reference into child class reference variable (after proper casting).

Q24 . What is Run-Time Polymorphism?

Ans . In run-time polymorphism we perform overriding with class upcasting.

Q25 . What is Interface?

Ans . Interface can consist of only incomplete methods in it.

Q26 . Can I create static incomplete method in an interface?

Ans: No. Interface does not support incomplete static method because static methods cannot be overridden.

Q27 . What is abstraction?

Ans: Hiding implementation details is called abstraction. The way we achieve this in Java is by using interface and abstract class.

Q28. What is Abstract Keyword?

Ans: When applied on a method it defines that the method is incomplete.
In an interface we can create incomplete method without using abstract keyword. Uses of abstract keyword here is optional.
When abstract keyword is applied on a class then it means class is incomplete.

Note: In Java, at interface level multiple inheritance is possible but at class level it is not possible.

Q29. What is Marker Interface?

Ans- An empty interface is called as marker interface.

Q30. What is Final Keywords ?

Ans : If we make variable final then its value cannot be changed. If we make static/no-static variable final
then initialization is mandatory. If we make a method final then overriding is not allowed.
 If we make class as final then inheritance of that class is not allowed.

Q31. Explain Java 8 new features.

Ans – Default Keyword: Default keyword was introduced in version 8 of java using which we can develop complete method in an interface. Functional Interface: It should consist of only one incomplete method in it.

In a functional Interface we can have any number of default methods but incomplete method should be only one.
Lamdas Expression: The advantage of lamdas expression is we can reduce number of times of code.

Note:
As we can access non-static member of the class using lamdas expression, it is also functional programming language since 1.8version of java.

When we create object to access non static member it becomes object
oriented programming language. We
create object in java using new keyword.



______________________________________________________________Page-2________________________________________________________



Q32. What is Abstract Class?

Ans : An abstract class can consist of both complete and incomplete method.
To define incomplete method in abstract class usage of abstract keyword is mandatory.

In an abstract class, we can create main method. Creating object in abstract class is not
allowed. Abstract classes do not support multiple inheritances.

In an abstract class we can create static variable as well as no static variable.

Q33. What is Data Hiding?

Ans- Here we make variable private so that it can’t be accessed outside the class.

Q34. What is Unary Operator

Ans- In java, the unary operator is an operator that can be used only with an operand. It is used to represent the positive or negative value, increment/decrement the value by 1 and complement a Boolean value.


Q35. What is Scanner Class?

Ans: Whenever a user wants to give input via keyboard, in java there is inbuilt class Called as a Scanner Class.

Q36. What is Encapsulation?
Ans: Bundling of data with methods which operate on that data avoiding direct access to the variable is called Encapsulation. To avoid direct access to the variable we makes variable private and to operate on those variable we create getter and setter.

Q37. What is the Differences between interface and abstract cla
































































































































Page -3


package com.debasish.arraypractice.oneDimensionalArray;

import java.util.Stack;

public class OneDimensionalArray84 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 85: ASTEROID COLLISION
        // ======================================

        // Step 1: create array
        int[] asteroids = {5, 10, -5};

        Stack<Integer> stack = new Stack<>();

        // Step 2: process asteroids
        for (int i = 0; i < asteroids.length; i++) {

            int current = asteroids[i];

            boolean exploded = false;

            // collision condition
            while (!stack.isEmpty()
                    && current < 0
                    && stack.peek() > 0) {

                int top = stack.peek();

                // top asteroid smaller
                if (Math.abs(current) > top) {
                    stack.pop();
                    continue;
                }

                // equal size
                else if (Math.abs(current) == top) {
                    stack.pop();
                }

                exploded = true;
                break;
            }

            // add asteroid if not exploded
            if (!exploded) {
                stack.push(current);
            }
        }

        // Step 3: print remaining asteroids
        System.out.println("Remaining Asteroids:");

        for (int val : stack) {
            System.out.print(val + " ");
        }

    }
}



package com.debasish.arraypractice.oneDimensionalArray;

import java.util.Stack;

public class OneDimensionalArray86 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 87: SIMPLIFY PATH
        // ======================================

        // Step 1: input path
        String path = "/a/./b/../../c/";

        // Step 2: split path
        String[] parts = path.split("/");

        Stack<String> stack = new Stack<>();

        // Step 3: process directories
        for (int i = 0; i < parts.length; i++) {

            String dir = parts[i];

            // ignore empty and current directory
            if (dir.equals("") || dir.equals(".")) {
                continue;
            }

            // go back
            else if (dir.equals("..")) {

                if (!stack.isEmpty()) {
                    stack.pop();
                }
            }

            // normal directory
            else {
                stack.push(dir);
            }
        }

        // Step 4: build simplified path
        String result = "";

        for (String dir : stack) {
            result = result + "/" + dir;
        }

        // Step 5: handle root
        if (result.equals("")) {
            result = "/";
        }

        // Step 6: print result
        System.out.println("Simplified Path: " + result);

    }
}





package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray88 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 89: LARGEST RECTANGLE IN BINARY MATRIX
        // ======================================

        // Step 1: create matrix
        int[][] matrix = {
                {1, 0, 1, 0, 0},
                {1, 0, 1, 1, 1},
                {1, 1, 1, 1, 1},
                {1, 0, 0, 1, 0}
        };

        int rows = matrix.length;
        int cols = matrix[0].length;

        // Step 2: height array
        int[] heights = new int[cols];

        int maxArea = 0;

        // Step 3: process each row
        for (int i = 0; i < rows; i++) {

            // update heights
            for (int j = 0; j < cols; j++) {

                if (matrix[i][j] == 1) {
                    heights[j] = heights[j] + 1;
                } else {
                    heights[j] = 0;
                }
            }

            // Step 4: find largest rectangle in histogram
            for (int start = 0; start < cols; start++) {

                int minHeight = heights[start];

                for (int end = start; end < cols; end++) {

                    if (heights[end] < minHeight) {
                        minHeight = heights[end];
                    }

                    int width = end - start + 1;

                    int area = minHeight * width;

                    if (area > maxArea) {
                        maxArea = area;
                    }
                }
            }
        }

        // Step 5: print result
        System.out.println("Largest Rectangle Area: " + maxArea);

    }
}








package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray89 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 90: MAXIMAL SQUARE
        // ======================================

        // Step 1: create matrix
        int[][] matrix = {
                {1, 0, 1, 0, 0},
                {1, 0, 1, 1, 1},
                {1, 1, 1, 1, 1},
                {1, 0, 1, 1, 1}
        };

        int rows = matrix.length;
        int cols = matrix[0].length;

        // Step 2: dp array
        int[][] dp = new int[rows][cols];

        int maxSide = 0;

        // Step 3: process matrix
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (matrix[i][j] == 1) {

                    // first row or column
                    if (i == 0 || j == 0) {
                        dp[i][j] = 1;
                    }

                    else {

                        dp[i][j] = 1 + Math.min(
                                dp[i - 1][j],
                                Math.min(dp[i][j - 1], dp[i - 1][j - 1])
                        );
                    }

                    // update max side
                    if (dp[i][j] > maxSide) {
                        maxSide = dp[i][j];
                    }
                }
            }
        }

        // Step 4: calculate area
        int area = maxSide * maxSide;

        // Step 5: print result
        System.out.println("Largest Square Area: " + area);

    }
}






package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray89 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 90: MAXIMAL SQUARE
        // ======================================

        // Step 1: create matrix
        int[][] matrix = {
                {1, 0, 1, 0, 0},
                {1, 0, 1, 1, 1},
                {1, 1, 1, 1, 1},
                {1, 0, 1, 1, 1}
        };

        int rows = matrix.length;
        int cols = matrix[0].length;

        // Step 2: dp array
        int[][] dp = new int[rows][cols];

        int maxSide = 0;

        // Step 3: process matrix
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (matrix[i][j] == 1) {

                    // first row or column
                    if (i == 0 || j == 0) {
                        dp[i][j] = 1;
                    }

                    else {

                        dp[i][j] = 1 + Math.min(
                                dp[i - 1][j],
                                Math.min(dp[i][j - 1], dp[i - 1][j - 1])
                        );
                    }

                    // update max side
                    if (dp[i][j] > maxSide) {
                        maxSide = dp[i][j];
                    }
                }
            }
        }

        // Step 4: calculate area
        int area = maxSide * maxSide;

        // Step 5: print result
        System.out.println("Largest Square Area: " + area);

    }
}







package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray90 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 91: SPIRAL MATRIX TRAVERSAL
        // ======================================

        // Step 1: create matrix
        int[][] matrix = {
                {1, 2, 3},
                {4, 5, 6},
                {7, 8, 9}
        };

        int top = 0;
        int bottom = matrix.length - 1;

        int left = 0;
        int right = matrix[0].length - 1;

        System.out.println("Spiral Order:");

        // Step 2: spiral traversal
        while (top <= bottom && left <= right) {

            // left to right
            for (int i = left; i <= right; i++) {
                System.out.print(matrix[top][i] + " ");
            }
            top++;

            // top to bottom
            for (int i = top; i <= bottom; i++) {
                System.out.print(matrix[i][right] + " ");
            }
            right--;

            // right to left
            if (top <= bottom) {

                for (int i = right; i >= left; i--) {
                    System.out.print(matrix[bottom][i] + " ");
                }

                bottom--;
            }

            // bottom to top
            if (left <= right) {

                for (int i = bottom; i >= top; i--) {
                    System.out.print(matrix[i][left] + " ");
                }

                left++;
            }
        }

    }
}

package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray91 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 92: ROTATE MATRIX 90 DEGREE
        // ======================================

        // Step 1: create matrix
        int[][] matrix = {
                {1, 2, 3},
                {4, 5, 6},
                {7, 8, 9}
        };

        int n = matrix.length;

        // Step 2: transpose matrix
        for (int i = 0; i < n; i++) {

            for (int j = i + 1; j < n; j++) {

                int temp = matrix[i][j];
                matrix[i][j] = matrix[j][i];
                matrix[j][i] = temp;
            }
        }

        // Step 3: reverse each row
        for (int i = 0; i < n; i++) {

            int left = 0;
            int right = n - 1;

            while (left < right) {

                int temp = matrix[i][left];
                matrix[i][left] = matrix[i][right];
                matrix[i][right] = temp;

                left++;
                right--;
            }
        }

        // Step 4: print rotated matrix
        System.out.println("Rotated Matrix:");

        for (int i = 0; i < n; i++) {

            for (int j = 0; j < n; j++) {

                System.out.print(matrix[i][j] + " ");
            }

            System.out.println();
        }

    }
}


package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray92 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 93: SET MATRIX ZEROES
        // ======================================

        // Step 1: create matrix
        int[][] matrix = {
                {1, 1, 1},
                {1, 0, 1},
                {1, 1, 1}
        };

        int rows = matrix.length;
        int cols = matrix[0].length;

        // Step 2: row & column marker arrays
        boolean[] zeroRow = new boolean[rows];
        boolean[] zeroCol = new boolean[cols];

        // Step 3: mark rows and columns
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (matrix[i][j] == 0) {
                    zeroRow[i] = true;
                    zeroCol[j] = true;
                }
            }
        }

        // Step 4: set zeroes
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (zeroRow[i] || zeroCol[j]) {
                    matrix[i][j] = 0;
                }
            }
        }

        // Step 5: print matrix
        System.out.println("Updated Matrix:");

        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                System.out.print(matrix[i][j] + " ");
            }

            System.out.println();
        }

    }



package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray93 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 94: SEARCH IN 2D MATRIX
        // ======================================

        // Step 1: create matrix
        int[][] matrix = {
                {1, 3, 5, 7},
                {10, 11, 16, 20},
                {23, 30, 34, 60}
        };

        int target = 16;

        int rows = matrix.length;
        int cols = matrix[0].length;

        boolean found = false;

        // Step 2: search element
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (matrix[i][j] == target) {
                    found = true;
                    break;
                }
            }
        }

        // Step 3: print result
        if (found) {
            System.out.println("Element Found");
        } else {
            System.out.println("Element Not Found");
        }

    }
}





package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray94 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 95: WORD SEARCH
        // ======================================

        // Step 1: create board
        char[][] board = {
                {'A', 'B', 'C', 'E'},
                {'S', 'F', 'C', 'S'},
                {'A', 'D', 'E', 'E'}
        };

        String word = "ABCCED";

        int rows = board.length;
        int cols = board[0].length;

        boolean found = false;

        // Step 2: search starting character
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (board[i][j] == word.charAt(0)) {

                    // simple horizontal + vertical check
                    if (j + word.length() <= cols) {

                        int k;

                        for (k = 0; k < word.length(); k++) {

                            if (board[i][j + k] != word.charAt(k)) {
                                break;
                            }
                        }

                        if (k == word.length()) {
                            found = true;
                        }
                    }

                    if (i + word.length() <= rows) {

                        int k;

                        for (k = 0; k < word.length(); k++) {

                            if (board[i + k][j] != word.charAt(k)) {
                                break;
                            }
                        }

                        if (k == word.length()) {
                            found = true;
                        }
                    }
                }
            }
        }

        // Step 3: print result
        if (found) {
            System.out.println("Word Found");
        } else {
            System.out.println("Word Not Found");
        }

    }
}


package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray94 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 95: WORD SEARCH
        // ======================================

        // Step 1: create board
        char[][] board = {
                {'A', 'B', 'C', 'E'},
                {'S', 'F', 'C', 'S'},
                {'A', 'D', 'E', 'E'}
        };

        String word = "ABCCED";

        int rows = board.length;
        int cols = board[0].length;

        boolean found = false;

        // Step 2: search starting character
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (board[i][j] == word.charAt(0)) {

                    // simple horizontal + vertical check
                    if (j + word.length() <= cols) {

                        int k;

                        for (k = 0; k < word.length(); k++) {

                            if (board[i][j + k] != word.charAt(k)) {
                                break;
                            }
                        }

                        if (k == word.length()) {
                            found = true;
                        }
                    }

                    if (i + word.length() <= rows) {

                        int k;

                        for (k = 0; k < word.length(); k++) {

                            if (board[i + k][j] != word.charAt(k)) {
                                break;
                            }
                        }

                        if (k == word.length()) {
                            found = true;
                        }
                    }
                }
            }
        }

        // Step 3: print result
        if (found) {
            System.out.println("Word Found");
        } else {
            System.out.println("Word Not Found");
        }

    }
}




package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray95 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 96: NUMBER OF ISLANDS
        // ======================================

        // Step 1: create matrix
        int[][] grid = {
                {1, 1, 0, 0},
                {1, 1, 0, 0},
                {0, 0, 1, 0},
                {0, 0, 0, 1}
        };

        int rows = grid.length;
        int cols = grid[0].length;

        int islands = 0;

        // Step 2: traverse matrix
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (grid[i][j] == 1) {

                    islands++;

                    // mark connected cells
                    markIsland(grid, i, j, rows, cols);
                }
            }
        }

        // Step 3: print result
        System.out.println("Number of Islands: " + islands);

    }

    // DFS method
    public static void markIsland(int[][] grid,
                                  int row,
                                  int col,
                                  int rows,
                                  int cols) {

        // boundary check
        if (row < 0 || col < 0
                || row >= rows || col >= cols
                || grid[row][col] == 0) {

            return;
        }

        // mark visited
        grid[row][col] = 0;

        // explore neighbors
        markIsland(grid, row + 1, col, rows, cols);
        markIsland(grid, row - 1, col, rows, cols);
        markIsland(grid, row, col + 1, rows, cols);
        markIsland(grid, row, col - 1, rows, cols);
    }
}

package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray95 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 96: NUMBER OF ISLANDS
        // ======================================

        // Step 1: create matrix
        int[][] grid = {
                {1, 1, 0, 0},
                {1, 1, 0, 0},
                {0, 0, 1, 0},
                {0, 0, 0, 1}
        };

        int rows = grid.length;
        int cols = grid[0].length;

        int islands = 0;

        // Step 2: traverse matrix
        for (int i = 0; i < rows; i++) {

            for (int j = 0; j < cols; j++) {

                if (grid[i][j] == 1) {

                    islands++;

                    // mark connected cells
                    markIsland(grid, i, j, rows, cols);
                }
            }
        }

        // Step 3: print result
        System.out.println("Number of Islands: " + islands);

    }

    // DFS method
    public static void markIsland(int[][] grid,
                                  int row,
                                  int col,
                                  int rows,
                                  int cols) {

        // boundary check
        if (row < 0 || col < 0
                || row >= rows || col >= cols
                || grid[row][col] == 0) {

            return;
        }

        // mark visited
        grid[row][col] = 0;

        // explore neighbors
        markIsland(grid, row + 1, col, rows, cols);
        markIsland(grid, row - 1, col, rows, cols);
        markIsland(grid, row, col + 1, rows, cols);
        markIsland(grid, row, col - 1, rows, cols);
    }
}





package com.debasish.arraypractice.oneDimensionalArray;

public class OneDimensionalArray96 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 97: FLOOD FILL
        // ======================================

        // Step 1: create image
        int[][] image = {
                {1, 1, 1},
                {1, 1, 0},
                {1, 0, 1}
        };

        int startRow = 1;
        int startCol = 1;

        int newColor = 2;

        int originalColor = image[startRow][startCol];

        // Step 2: perform flood fill
        fill(image,
                startRow,
                startCol,
                originalColor,
                newColor);

        // Step 3: print image
        System.out.println("Updated Image:");

        for (int i = 0; i < image.length; i++) {

            for (int j = 0; j < image[0].length; j++) {

                System.out.print(image[i][j] + " ");
            }

            System.out.println();
        }

    }

    // DFS method
    public static void fill(int[][] image,
                            int row,
                            int col,
                            int originalColor,
                            int newColor) {

        // boundary check
        if (row < 0 || col < 0
                || row >= image.length
                || col >= image[0].length
                || image[row][col] != originalColor
                || image[row][col] == newColor) {

            return;
        }

        // fill color
        image[row][col] = newColor;

        // move in 4 directions
        fill(image, row + 1, col, originalColor, newColor);
        fill(image, row - 1, col, originalColor, newColor);
        fill(image, row, col + 1, originalColor, newColor);
        fill(image, row, col - 1, originalColor, newColor);
    }
}



package com.debasish.arraypractice.oneDimensionalArray;

import java.util.LinkedList;
import java.util.Queue;

public class OneDimensionalArray97 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 98: SHORTEST PATH IN BINARY MATRIX
        // ======================================

        // Step 1: create grid
        int[][] grid = {
                {0, 1},
                {1, 0}
        };

        int n = grid.length;

        // Step 2: check blocked cells
        if (grid[0][0] == 1 || grid[n - 1][n - 1] == 1) {

            System.out.println("No Path");
            return;
        }

        // Step 3: directions (8 directions)
        int[] rowDir = {-1, -1, -1, 0, 0, 1, 1, 1};
        int[] colDir = {-1, 0, 1, -1, 1, -1, 0, 1};

        // queue -> row, col, distance
        Queue<int[]> queue = new LinkedList<>();

        queue.offer(new int[]{0, 0, 1});

        // mark visited
        grid[0][0] = 1;

        int shortest = -1;

        // Step 4: BFS traversal
        while (!queue.isEmpty()) {

            int[] current = queue.poll();

            int row = current[0];
            int col = current[1];
            int distance = current[2];

            // reached destination
            if (row == n - 1 && col == n - 1) {

                shortest = distance;
                break;
            }

            // explore neighbors
            for (int i = 0; i < 8; i++) {

                int newRow = row + rowDir[i];
                int newCol = col + colDir[i];

                // valid cell
                if (newRow >= 0 && newCol >= 0
                        && newRow < n && newCol < n
                        && grid[newRow][newCol] == 0) {

                    queue.offer(new int[]{
                            newRow,
                            newCol,
                            distance + 1
                    });

                    // mark visited
                    grid[newRow][newCol] = 1;
                }
            }
        }

        // Step 5: print result
        System.out.println("Shortest Path Length: " + shortest);

    }
}


package com.debasish.arraypractice.oneDimensionalArray;

import java.util.LinkedList;
import java.util.Queue;

public class OneDimensionalArray99 {

    public static void main(String[] args) {

        // ======================================
        // PROBLEM 100: COURSE SCHEDULE
        // ======================================

        // Step 1: number of courses
        int numCourses = 4;

        // prerequisite pairs
        int[][] prerequisites = {
                {1, 0},
                {2, 1},
                {3, 2}
        };

        // Step 2: create adjacency matrix
        int[][] graph = new int[numCourses][numCourses];

        // indegree array
        int[] indegree = new int[numCourses];

        // build graph
        for (int i = 0; i < prerequisites.length; i++) {

            int course = prerequisites[i][0];
            int prerequisite = prerequisites[i][1];

            graph[prerequisite][course] = 1;

            indegree[course]++;
        }

        // Step 3: add zero indegree nodes
        Queue<Integer> queue = new LinkedList<>();

        for (int i = 0; i < numCourses; i++) {

            if (indegree[i] == 0) {
                queue.offer(i);
            }
        }

        int completed = 0;

        // Step 4: BFS Topological Sort
        while (!queue.isEmpty()) {

            int current = queue.poll();

            completed++;

            for (int i = 0; i < numCourses; i++) {

                if (graph[current][i] == 1) {

                    indegree[i]--;

                    if (indegree[i] == 0) {
                        queue.offer(i);
                    }
                }
            }
        }

        // Step 5: print result
        if (completed == numCourses) {
            System.out.println("All Courses Can Be Completed");
        } else {
            System.out.println("Cycle Detected - Cannot Complete Courses");
        }

    }
}

