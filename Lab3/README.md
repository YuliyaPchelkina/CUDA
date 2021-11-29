# Лабораторная работа 3. Bilateral filtering on GPU (Двусторонняя фильтрация).

### Task definition
Given the image of size MxN, implement and apply a CUDA version of 9-point bilateral filter and store the result to output image. 
Missing values for edge rows and columns are to be taken from nearest pixels. 
CUDA implementation must make use of texture memory.

### Implementation requirements
1. Input grayscale image in BMP format
2. Output data
- The time of image processing using GPU;
- The time of image processing using СPU;
- Resulting images in BMP format.
3. Implementation. The program is required to work on Linux machine. The resulting image could be exported in BMP format, using
many open-source libraries.
