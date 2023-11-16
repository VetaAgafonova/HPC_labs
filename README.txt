https://drive.google.com/file/d/1c5lZPUTqBVe4_yetr568exljKw9ZqVPv/view?usp=sharing


Задача: Given the image of size M×N, implement and apply a CUDA version of 9-point bilateral filter and store the
result to output image. Missing values for edge rows and columns are to be taken from nearest pixels. CUDA
implementation must make use of texture memory.
Входные данные: Input grayscale image in BMP format, σ values;
Выходные данные: The time of image processing using GPU; The time of image processing using СPU; Resulting images in BMP format


Одна нить обрабатывает один пиксель и сохраняет значение  в выходной массив.
