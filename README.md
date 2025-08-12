# JAVA-PROGRAM-TO-PERFORM-ADDITION-OF-TWO-MATRICES-

## AIM:
To Perform addition of two matrices using Java programming language.

## APPARATUS REQUIRED:

Computer

Eclipse IDE

## THEORY:

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let programmers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the needto recompile. Java applications are typically compiled to bytecode that can run on any Java virtual machine (JVM) regardless of the underlying computer architecture. The syntax of Java is similar to C and C++, but has fewer low-level facilities than either of them. The Java runtime provides dynamic capabilities (such as reflection and runtime code modification) that are typically not available in traditional compiled languages. As of 2019, Java was one of the most popular programming languages in use according to GitHub, particularly for client–server web applications, with a reported 9 million developers.


## PROCEDURE:

1. Launch Eclipse IDE

o Open Eclipse.

o Select a workspace (folder for saving your projects).

2. Create a New Project

o Click File > New > Java Project

o Enter the project name.

o Click Finish.

3. Create a New Class 

o Right-click on your package → New > Class.

o Enter the class name (e.g., Main).

o Check public static void main(String[] args) (for Java).

o Click Finish.

4. Write Your Program

o Eclipse opens the code editor automatically.

o Type or paste your source code.

5. Save the Program

o Press Ctrl + S or click File > Save.

6. Compile and Run the Program

o Click the Run button (green ▶) on the toolbar.

o View output in the Console window.

7. Close Eclipse

o After finishing, click File > Exit to close Eclipse IDE.


## PROGRAM:
```
package addingnumbers;
public class MatrixAdditionExample{
public static void main(String args[]){
int a[][]={{1,3,4},{2,4,5},{3,4,2}};
int b[][]={{2,1,3},{2,1,4},{1,3,2}};
int c[][]=new int[3][3];
for(int i=0;i<3;i++){
for(int j=0;j<3;j++){
c[i][j]=a[i][j]+b[i][j]; 
System.out.print(c[i][j]+" ");
}
System.out.println();
}
}}
```

## OUTPUT:
<img width="1043" height="899" alt="Screenshot 2025-08-12 151648" src="https://github.com/user-attachments/assets/3010f84f-b0ff-4864-9a97-a8f1c31bfa11" />


## RESULT:

Thus, the program to add two matrices using a Java program is developed, and the output is verified. 


