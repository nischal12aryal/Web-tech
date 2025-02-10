Task 1
Password cracking using multithreading 
In this task, you will be asked to use the “crypt” library to decrypt a password using This project demonstrates how to crack a password encrypted using SHA-512 with the help of the crypt library in C. The program uses multithreading to distribute the password cracking task, significantly speeding up the process of finding the correct password. The password consists of 2 capital letters followed by 2 digits, in the format "LetterLetterNumberNumber" (e.g., "HP93").



Task 2
Matrix Multiplication using multithreading
This program performs matrix multiplication using multithreading. It reads matrices from a supplied file, multiplies them using dynamic memory allocation, and stores the result in an output file. The multiplication task is split across multiple threads for parallel computation, which enhances performance for larger matrices.

Task3
Password Cracking using CUDA
This program demonstrates password cracking using CUDA, where we utilize the power of GPU processing to efficiently crack encrypted passwords. The password cracking process is accelerated by running many threads on the GPU in parallel, which is suitable for breaking passwords with many possible combinations. The password will be decrypted using multiple blocks and threads, making the process much faster than a single-threaded CPU solution.
Box Blur Using CUDA
This program applies a Box Blur filter to an image using CUDA for parallel processing. The Box Blur filter smoothens the color distribution across the image by averaging the pixel values in a 3x3 neighborhood around each pixel. This program reads a PNG image, applies the Box Blur using GPU threads, and writes the blurred image back to a file.
