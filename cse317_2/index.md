# CSE 317 Sec 2 | Numerical Method

## Instructor
### Mohammad Motiur Rahman
Email: motiur@iub.edu.bd
* * *
## Unofficial Teaching Assistants

### [Rezaul Khan Ahad](mailto:1830187@iub.edu.bd) 

[Google Meet](meet.google.com/txg-rebq-noi)

Office Hour Time: By appointment

* * *
## Class Timing


* * *
## Grading Scheme (Tentative)
Assignments - 10 marks

Quiz - 20 marks

Midterm Exam - 30 marks

Final Exam - 40 marks
* * *


## Code of conduct
Plagiarism will absolutely not be tolerated.

[Rules regarding plagiarism](https://www.plagiarism.org/article/what-is-plagiarism)

Also read the following code of conduct expected from IUB authorities: Page 38 and Page 39 of http://www.iub.edu.bd/files/Greenbook,sp19.f.pdf.

Couple of other important rules and regulation: 

<b>a.</b>You are expected to keep your video feed all the time during the class time. Use background blur in Google Meet and/or burqa to preserve your privacy. However, I
want to see your video feed all the time during the class hour.

<b>b.</b>You are expected to have extendable webcam with you. If you fail to have it your exam copies will not be evaluated due to absence of proper proctoring environment.
You can find extendable webcams [here](https://www.startech.com.bd/accessories/webcam) and [here](https://www.ryanscomputers.com/category/camera-webcam).

<b>c.</b>You are expected to have a properly lighted room during evaluation. For dimly lighted you are requested to buy a reading desk lamp. Failure to have a proper proctoring
environment will force me to not evaluate your exam copies.

<b>d.</b>If you are found guilty of plagiarism during quiz or assignments you will get a 0 mark. If you are found guilty of showing your answer to some one else during Midterm, you will be downgraded two successive grades, if you again show copy during Final Exam you will be given an F. Students who copies answer from other students will simply get 0 marks , no questions asked. 

<b>e.</b>You are expected to mute your microphone by default. If you have a question, type it in the chatbox on the right hand side of the Google Meet window, or raise your hand. I will check the chatbox on regular intervals. If your question is not answered adequately, you may open your microphone and ask the question verbally.

<b>f.</b>You are also expected to show decent behavior while the class is being conducted. You shall not be permitted such behaviors in the classrooms which are not permitted in Bangladeshi society. Remember even though you are online your behavior might affect other students as well as the instructor who is taking the class. The classes will be recorded, so please maintain decency.

<b>g.</b>There has been reports that students showed reluctance in wearing decent clothes while taking online classes. So be aware of that. What are decent clothes you may ask. These are attires which you would normally wear in a physical classroom of IUB. It does not has to fancy, it just has to be decent.

<b>h.</b>If you are not comfortable with the workings of this class , you can email the head of the Department [Dr. Mahady Hasan](mailto:mahady@iub.edu.bd ) and then the Dean of Department [Dr Yusuf Mahbubul Islam](mailto:ymislam@iub.edu.bd ). If you feel you need to complain to more "important" entities besides these two personnel, I would request you to rethink taking this course.
* * *   


## Course Outline

<b> Course Objective </b>

The objective of this course is to introduce the student computational methods required by engineers, mathematicians, physicists and economists to explore complex systems. Mathematical models developed to explore complex systems can be rarely “solvable” algebraically and hence computational methods have been developed. This course introduces such methods that range from techniques for system of linear equations, nonlinear equations, approximation of functions, interpolation, clustering, least square data fitting and classification, differentiation and integration. More emphasis will be put on applied linear algebra topics which are prerequisite for Artificial Intelligence, Machine Learning, and other advanced courses. We will make use of Matlab programming to implement and analyze the methods.

<b> Learning Outcomes </b>

<b>1.</b>Demonstrate understanding of the Linear algebra theory that underlies the many of common computational methods and how the methods are used to obtain approximate solutions to otherwise intractable mathematical problems.

<b>2.</b>Apply numerical methods to obtain approximate solutions to mathematical problems.

<b>3.</b>Derive numerical methods for various mathematical operations and tasks, such as interpolation, differentiation, integration, the solution of linear and nonlinear equations, and least square optimization used in clustering, data fitting, and classification.

<b>4.</b>Implement numerical methods in Python.

<b>5.</b>Write efficient, well-documented Python code and present numerical results in an informative way. 


## Tentative Syllabus

| Chapter      |Topic                                                                                                           | 
|:-------------|:---------------------------------------------------------------------------------------------------------------|
|              |<b>Approximation errors and approximating single variable functions</b>                                         |
| Ch 3, 4 NME  | Floating point number system and error in number representation, review of derivatives, Taylor Series, finding optima of single variable functions|
| Ch 5, 6 NME  | Finding roots of single variable functions – Bisection, Secant and Newton-Raphson Method                       |
|              |<b>Vectors and Matrices</b>|
|Ch 1,2 VMLS   |Vectors - review of vector notation, vector operations, linear and affine multivariable functions, complex vectors, complexity of vector computations, applications: vector representation of data (e.g., images, documents, timeseries, features), vector representation of linear and affine functions (e.g., regression, Linear (Taylor) approximation of multivariable function functions)|
|Ch 3,4 VMLS   |Norms and distances - Euclidean norm and distances, properties (Cauchy-Schwarz and triangle inequalities, Pythagorean theorem), statistical measurements of data: average, rms, standard deviation, and angle between vectors and correlation, covariance; representation of hyperplanes, application: single variable linear regression, k-means clustering|
|              |<b>Direct Methods for Solving System of Linear Equations</b>|
|Ch 8 VMLS|Solving system of linear equations using LU decomposition, application: Polynomial interpolation and Vandermonde matrix, applications of solving system of linear equations|
|Ch 5, 11 VMLS |Matrix Inverses: Left and right inverses, solving system of linear equations using matrix inverses, Gram matrix and Pseudo-inverse|
|              |<b>Orthogonality and Least Square Methods</b>|
|Ch 5, 10, 11 VMLS|Basis, orthogonality and inner products: basis and change of basis, Orthogonal basis, Gram-Schmidt, modified-Gram Schmidt algorithms, QR decomposition of matrices, Householder reflections, application: solving system of linear equations using QR factorization, lower dimensional data representation|
|Ch 12-14 VMLS; Ch 17 NME|Linear least-Squares: solution to over-determined systems, normal equation and pseudo inverse of a matrix, computing pseudo inverse using QR and Cholesky factorization, solving least squares using matrix-vector derivates, application: data fitting and least-square regression, feature engineering, Least-square classification, regularized least square data fitting, least square function approximation |
|              |<b>Interpolation</b>|
|Ch 18 NME     |Interpolation using monomial and Lagrange bases will be discussed in Linear equation lecture. Interpolation using other basis functions: Newton, Legendre, Chebyshev bases, Hermite interpolation, cubic spline interpolation|
|              |<b>Numerical Differentiation and Integration</b>|
|Ch 22, 23 NME|Finite divided difference approximation of derivatives, Trapezoidal rule, Simpson’s rule|
|Ch 6, 7 (notes)	2|<b>Problem Condition, Algorithm Stability	</b>|



## Class Schedule

| Class   | Topics       | Notes                                                                                                          | 
|:--------|:-------------|:---------------------------------------------------------------------------------------------------------------|
| 1       | Introduction | [Google Jamboard]()                                                                                            |
|         |              | [Youtube Link](https://youtu.be/8t2vPziP56Q)                                                                    |
| 2       | Python       | [Google Jamboard]()                                                                                            |
|         |              | [Youtube Link](https://youtu.be/iuzdZeYbHBs)                                                                    |
| 3       | Python Cont  | [Google Jamboard]()                                                                                            |
|         |              | [Youtube Link](https://youtu.be/Ox8pdtlAFok)                                                                    |
| 4       | Matrix Add Multiply  | [Google Jamboard](https://jamboard.google.com/d/1qUqCsfOmrK9Swo-NkNgNy6lFwEhlWn9vndhXyvSB3YY/edit?usp=sharing)  |
|         |              | [Youtube Link](https://youtu.be/T6igLP4DPk8)                                                                      |
| 5       | Ax = b       | [Google Jamboard](https://jamboard.google.com/d/1t0rtGV5oL-m8wHdq4agcK6sz9A9xCc3CWs-NbSmvlE4/edit?usp=sharing)  |
|         |              | [Another Applied Linear Algebra Book](http://phys.uri.edu/nigh/NumRec/)  |
|         |              | [Youtube Link](https://youtu.be/MIZEAP3RvYs)                                                                      |
| 6       | Ax = b Cont. | [Google Jamboard](https://jamboard.google.com/d/1t0rtGV5oL-m8wHdq4agcK6sz9A9xCc3CWs-NbSmvlE4/edit?usp=sharing)  |
|         |              | [Youtube Link](https://youtu.be/ZS6Bp6EAl8U)                                                                      |
|         |              | [Google Jamboard](https://jamboard.google.com/d/1KqmfE0mfoz355-2am-xsVBi8fHwFIbaHijmWV5y4PsY/edit?usp=sharing)   |
| 7       | Ax = b Cont. | [Google Jamboard](https://jamboard.google.com/d/1jFWTpaUwABMGV6-g_9aGQnkZOCbTyxrtauNeZg3PWa8/edit?usp=sharing)  |
|         |              | [Youtube Link](https://youtu.be/alAe7EEDC9k)                                                                      |
| 8       | Ax = b Cont. | [Google Jamboard](https://jamboard.google.com/d/11Znrf9TpjLcVrcg-NPsHXdeStSIKPfdb1cusJUXSnV0/edit?usp=sharing)  |
|         |              | [Youtube Link](https://youtu.be/B4U8U8JQb8U)                                                                      |


## Slides

| [Lecture Slides in PDF](https://github.com/mohammadmotiurrahman/mohammadmotiurrahman.github.io/tree/main/cse317_2/slides)  |                             
|:----------------------------------------------|
| [Chapter 1](/)    |


## Google Colab

| Lecture code in C++                               |                                                
|:--------------------------------------------------|
| [Python](https://colab.research.google.com/github/mohammadmotiurrahman/mohammadmotiurrahman.github.io/blob/main/cse317_2/monday.ipynb) | 
| [Numpy ....](https://colab.research.google.com/github/mohammadmotiurrahman/mohammadmotiurrahman.github.io/blob/main/cse317_2/linear_algebra.ipynb)|


## Reference Books

<b>0.</b> [Introduction to Linear Algebra, Fifth Edition (2016), by Gilbert Strang](https://math.mit.edu/~gs/linearalgebra/)

<b>1.</b> [VMLS] [Introduction to Applied Linear Algebra - Vectors, Matrices, and Least Squares, by S. Boyd and L. Vandenberghe](https://web.stanford.edu/~boyd/vmls/)

<b>2.</b> [notes] [Additional notes to Applied Numerical Computing](http://www.seas.ucla.edu/~vandenbe/133A/133A-notes.pdf)

<b>3.</b> [NME] Numerical Methods for Engineers, by S. Chapra, 7th ed., McGraw Hill


* * *

## Other essential references

<b>0.</b> [Introduction to Applied Linear Algebra Stanford ENGR108](https://www.youtube.com/watch?v=oR6G1MUMveE&list=PLoROMvodv4rMz-WbFQtNUsUElIh2cPmN9)

<b>1.</b> [Introduction to Linear Algebra MIT 18.06](https://www.youtube.com/watch?v=7UJ4CFRGd-U&list=PLE7DDD91010BC51F8)

<b>2.</b> [Matrix Methods in Data Analysis, Signal Processing, and Machine Learning MIT 18.065](https://www.youtube.com/watch?v=Cx5Z-OslNWE&list=PLUl4u3cNGP63oMNUHXqIUcrkS2PivhN3k)

<b>3.</b>[Applied Numerical Computing, Prof. L. Vandenberghe, UCLA](http://www.seas.ucla.edu/~vandenbe/133A/)

Applied Numerical Methods with MATLAB for Engineers and Scientists, by S. Chapra, 3rd ed., McGraw Hill.

Coding the Matrix - Linear Algebra through Applications in Computer Science, by P. Klein (resources: codingthematrix.com)


* * *

Be curious
