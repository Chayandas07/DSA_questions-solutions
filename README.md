# DSA_questions-solutions
![DSA](https://user-images.githubusercontent.com/112325374/192339462-5fd11a63-444e-4494-89db-200ebb5872ec.gif)
# Read CONTRIBUTING.md for 'How to contribute ?'
# How to contribute ?

1.	Search about the the topic or domain on which you want to  contribute like course topic, provided by, platform, etc.
2.	Take the reference from below example and structure your  information similar to that .
3.	Check your code.
4.	Commit your change and go for pull request.
NOTE-Wrong syntax code can be rejected.
NOTE1 - Contribution must be done in the given format. Pull request wont be accepted if the format is wrong.
# Example



       {
      
      "id":"1".
      
      "topic":"DSA - Array",
      
      "question":"W. A. P. to find addition of matrices",
      
      "answer_link":"https://stackoverflow.com/questions/33059430/matrix-addition-using-c"
      
      }
      {
      
      "id":"121",
      
      "topic":"DSA - Array",
      
      "question":"How do you declare an Array?",
      
      "answer_link":"https://www.geeksforseeks.com/how-do-you-declare-array/"
      
      }
       {
      
      "id":"100",
      
      "topic":"DSA - Array",
      
      "question":"W. A. P. to find subtraction of matrices",
      
      "answer_link":"https://www.c-sharpcorner.com/blogs/subtract-matrix-in-c-programming"
      
      }
      // C++ program for addition
// of two matrices
#include <bits/stdc++.h>
using namespace std;
#define N 4

// This function adds A[][] and B[][], and stores
// the result in C[][]
void add(int A[][N], int B[][N], int C[][N])
{
	int i, j;
	for (i = 0; i < N; i++)
		for (j = 0; j < N; j++)
			C[i][j] = A[i][j] + B[i][j];
}

// Driver code
int main()
{
	int A[N][N] = { { 1, 1, 1, 1 },
					{ 2, 2, 2, 2 },
					{ 3, 3, 3, 3 },
					{ 4, 4, 4, 4 } };

	int B[N][N] = { { 1, 1, 1, 1 },
					{ 2, 2, 2, 2 },
					{ 3, 3, 3, 3 },
					{ 4, 4, 4, 4 } };

	int C[N][N]; // To store result
	int i, j;

	// Function Call
	add(A, B, C);

	cout << "Result matrix is " << endl;
	for (i = 0; i < N; i++) {
		for (j = 0; j < N; j++)
			cout << C[i][j] << " ";
		cout << endl;
	}

	return 0;
}

// This code is contributed by rathbhupendra


