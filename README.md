  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 | Project Name: PortfolioProject2                   |
 | Author:       Casey Beins                         |
 | Date:         10/06/2024                          |
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

                                                      
 |~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~|
 | Link to GitHub Repository:                        |
 | github.com/CaseyBeins/CSC450_Portfolio_Project    |   
 |                                                   |
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 *Project Description:

 This project demonstrates basic concurrency concepts in Java using threads. 
 The application creates two separate threads: one counts up from 0 to 20, 
 and once it’s finished, the second thread counts down from 20 to 0. This 
 simple program showcases how threads work in Java and includes basic thread 
 synchronization to control the order of execution.

 *Features:

 - **Two Threaded Counters:** One thread counts up while the other counts down, 
 showing how you can run tasks independently.
 
 - **Thread Synchronization:** Uses `Thread.join()` to ensure the first thread completes 
 before the second thread starts.
 
 - **Basic Console Output:** Outputs the current count value for each thread, making 
 it easy to visualize the sequence.

 *How It Works:
 
 The program uses Java's `Thread` class to create and manage the two threads. 
 The threads are joined using `Thread.join()` to control the order in which they 
 complete. Each thread’s progress is printed to the console, providing a 
 step-by-step view of the counting process.

 ---------------------------------------------------------------------------------------
 In this repository you will find a src folder containing the source code for the 
 project. Additionally, you will find a Word document containing a detailed analysis, 
 of the project, screenshots of the project running in an IDE, source code, and 
 a detailed comparison between the performance implementations between the Java and C++ 
 versions of this application. 
 ---------------------------------------------------------------------------------------
