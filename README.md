# Halcon-Practical-Programs

MVTec HALCON is the comprehensive standard software for machine vision with an integrated development environment (HDevelop) that is used worldwide. It enables cost savings and improved time to market. HALCON’s flexible architecture facilitates rapid development of any kind of machine vision application [1].

HALCON is the standard software solution for industrial image processing (machine vision) and features an integrated development environment (IDE). As one of the world's most comprehensive vision toolboxes, HALCON reduces costs and ensures improved time-to-market. HALCON's flexible software architecture enables rapid application development for industrial and medical image processing and image analysis. In addition to superior performance and GPU acceleration, HALCON also provides extensive support for multi-core platforms and instruction set extensions such as SSE2, AVX and AVX2 [2].

HALCON provides a large number of functions for implement of image processing algorithms and working with images like OpenCV. Although it has massive number of procedures and commands for various tasks but till version 18.11 it doesn't have built-in functions like .csv file creator and PLC connector.

In current repository, I have provided some practical and useful programs which can be used in HALCON-based machine vision programs. Some primary programs of repository include:

- **button**: Quick menu buttons creator for using in HALCON window

- **csv creator**: Creating .csv file with arbitrary headers and adding random records to it  

- **image to matrix**: Converting an image to matrix (2D array) with two different methods

- **multi-threading**: Converting an image to matrix (2D array) using multi-thread programming

- **os operators**: Two simple method for creating folders and renaming of images

- **plc connection**: Connecting to PLC using OPC server and communicating with registers

- **room lighting (fun)**: A fun program with integrating codes like button and multi-threading

  "room lighting" is a program that you can control lights of a room using buttons in a sample image. First time you run the program, HALCON window will be seen as below:
  
  ![1](https://user-images.githubusercontent.com/41106741/233988150-a0246cdd-e764-44a2-95ab-92623111e65a.png)

  When you hit the "Light ON" button, room lights will be on with an image histogram equalization algorithm in image processing:
  
  ![2](https://user-images.githubusercontent.com/41106741/233989510-aeb0d89a-6571-4410-8e8d-4ccfd3b8817a.png)

  By hitting the "Light OFF" button, room lights will be off again. Using "Board ON"/"Board OFF" you can turn on/off LED of boards on wall with a template matching algorithm:
  
  ![3](https://user-images.githubusercontent.com/41106741/233990676-a855e71c-22de-4a85-ae40-c5db8fadb25f.png)
  
  Also you can see a screenshot of HALCON enviornment for this program here:
  
  ![Capture](https://user-images.githubusercontent.com/41106741/233993403-7a3dd9e0-b213-4a94-82cc-df72ddba08b9.PNG)



**References:**

[1] https://www.mvtec.com/products/halcon

[2] https://www.theimagingsource.com/zh-hant-tw/product/mvtec/halcon/#:~:text=porting%20existing%20code-,What%20is%20HALCON%3F,images%20from%20a%20capture%20device.
