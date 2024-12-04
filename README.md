java c
MAEG 5030: 
Geometry Computing for Design and Manufacturing 
Remarks on Coding Assignment  Project 
Project and Oral Presentation
 Topics for course project (oral presentation):
 Form. a group of 3 students;
 Selected from your own research project/related field that connected with geometry computing (design, manufacturing, robotics, …);
 Or selected topics from given papers, available at
 https://www.dropbox.com/scl/fo/vmleua68rvr8mrl5f5qxy/h?rlkey=b9agoqzzzgvy9w16n1fx1p7x5dl=0
 Oral Presentation will be 7 mins + 3 mins QA, it should cover
 What task is solved and how did authors formulate it as geometry processing problem
 Which algorithm is proposed
 What’s the technical contribution of the work and why it outperform. with existing work
Project and Oral Presentation 
 Oral Presentation (each student should present 1-2 parts)
 Project report (2-3 pages, IEEE standard, double column, pdf format):
 Introduction of the problem
 Formulation of geometry computing problem
 Pseudocode of the algorithm
 Analysis of the method and contribution
 Provide the contribution statement.
 Example: xx: Writing – xx section; Discussion xx; Slicer making xx page xx-xx; Coding Implementation xx; Algorithm Writing xx;
Coding Assignment (C++/python) 
 CRML-code: using CMAKE for cross-platform. building.
 Cmake: https://cmake.org/download/
 Eigen Library: https://eigen.tuxfamily.org/index.php?title=Main_Page
 Suggest to use Visual Studio 2022 for the project.
 https://visualstudio.microsoft.com/vs/community/
 Make sure you have the c++ for desktop development installed.
 Qt visualizer (Ver. 5.12!)
 https://download.qt.io/archive/qt/5.12/5.12.3/
 Recommended install position: C:\Qt\Qt5.12.3
 Make sure you select MSVC 2017 64-bit during the installation
 Qt creator – write function and add button.
 Sample function will be provided.
Usage of coding framework 
 Select the folder of source code and build direction.
 Push Configure bottom and select x64 as the optional platform.
 Add the path in line 41 of Cmake fil代 写MAEG 5030: Geometry Computing for Design and ManufacturingC/C++
代做程序编程语言e
 set(CMAKE_PREFIX_PATH "${CMAKE_PREFIX_PATH}
 C:\\Qt\\Qt5.12.3\\5.12.3\\msvc2017_64\\lib\\cmake\\Qt5")
 Click Generate and open project in visual studio
 Right click “CRML” in solutions and set as start up project
 Generate Solutions
 Note: You can also finish the assignment with coding language you feel comfortable with.
Coding Assignment 1 
 Handle documents (pdf file) with screenshot of the code, and graphics pictures demonstrate the result.
 Hint on Assignment 1:
 1. Search Data Structures (30%): To build the hash data structure of point set (e.g., 20 x 20 x 20 boxes)
 2. Search k-neighbors of each point (30%)
 3. Using Principal Component Analysis (PCA) to compute the normal of every point by its neighbors (30%)
 4. Display the point set with normal estimated from PCA (10%)
 5. Bonus: ICP-based algorithm for two point clouds (30%)
Coding Assignment 2 
 Handle documents (1 pdf file) with screenshot of the code, and graphics pictures demonstrate the result.
 Hint on Assignment 2:
 1. Read point cloud, and corresponding UV coordinate (10%)
 2. Build sparse matrix A for B-spline surface fitting (40%)
 3. Construct matrix b and solve linear system (10%)
 4. Uniformly sample vertex on b-spline surface, build topology connection, and create vertex table and face table. (30%)
 5. Construct triangle meshes for point cloud 1 - 4 (20%)
 6. Bonus: Compare the performance of different parameters (number of control points and order) of a B-spline surface.
Evaluate the fitting error. (30%)
Coding Assignment 3 
 Handle documents (1 pdf file) with screenshot of the code, and graphics pictures demonstrate the result.
 Hint on Assignment 3
 1. Write iterative way of surface smoothing – based on connectivity (40%)
 2. Using Laplace operator for surface smoothing (40%)
Hint: Build sparse matrix A as Laplacian Operator
 3. Compare the performance between two method with different iteration time (20%)
 4. Bonus: Implementing cotangent weights of Laplacian Operator. (30%)





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
