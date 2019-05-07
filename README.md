# NumericalMethods
Provides tools for common linear algebra Vector/Matrix operations as well as functional and calculus approximations. 

  This repository is designed around math and computer science courses taken at Concordia University and mostly uses methods learned in this curriculum. The tools provided are often used to solve questions posed in math courses using methods (often approximation mathods) learned in computer science courses or while doing research for said courses.

  This API uses the Function abstract class to define, solve and find the (approximate) solution of a mathematical function. This class will also provide approximations of derivatives and integrals through polynomial methods. All approximations can be set to a given decimal accuracy but can use recursive or iterational approaches to reach given accuracy. 
  Matrices and Vectors are data classes which output a brand new data object for most major modification operation (including row operations). Both the Matrix class and Vector class provide all basic operations which can be performed on them, such as multiplication and addition, but are extended by subclasses which describe data more specifically and provide more specialized operations to be performed on them, such as SquareMatrix providing a determinant and inverse method.
  
 Note: This api is not meant for use with large data and can reduce in efficiency as well as accuracy of approximations the larger the size of the data gets or the more operations performed on them.
 Note 2: This API was origionally created as a studying tool for COMP 361 of Concordia University but has since been modified to have more general applications and be a bit cleaner. 
