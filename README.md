# EXPERIMENT--01-ALP-FOR-8086
Name :NIDISHKUMAR S
Roll no :212224040218
Date of experiment :01.09.2025





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AL,0BH
MOV BL,05H
ADD AL,BL
```




## Output  
<img width="1598" height="686" alt="Screenshot 2025-09-01 212546" src="https://github.com/user-attachments/assets/d5d65ca8-6aa9-4bce-870b-578b354ea0a5" />

 
## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL,0BH
MOV BL,05H
SUB AL,BL
```

 
## Output  
<img width="1705" height="618" alt="image" src="https://github.com/user-attachments/assets/3dcb9720-0eeb-4d13-8370-e23f92c3a449" />


## Multiplication alp 
```
MOV AL,0BH
MOV BL,05H
MUL AL,BL
```
 ## Output  
 <img width="1676" height="576" alt="image" src="https://github.com/user-attachments/assets/a07de7a1-d213-4ae7-8fe6-a4a153885bd3" />



## Division alp 
```
MOV AL,0AH
MOV BL,05H
DIV BL
```

## Output  
<img width="1629" height="636" alt="image" src="https://github.com/user-attachments/assets/7da3e617-f164-4685-9442-57b7bf3defa4" />

## AND alp
```
MOV AL,0BH
MOV BL,05H
AND AL,BL
```

## Output
<img width="1611" height="639" alt="image" src="https://github.com/user-attachments/assets/289c29cc-5fa0-4b3b-b491-1a3954459336" />



## OR alp
```
MOV AL,0BH
MOV BL,05H
OR AL,BL
```

## Output

<img width="1563" height="625" alt="Screenshot 2025-09-01 213802" src="https://github.com/user-attachments/assets/50e06ec3-1e0d-4051-97e3-f47b1974f552" />


## NOT alp
```
MOV AL,0BH
MOV BL 05H
NOT AL
```

##  Output

<img width="1647" height="526" alt="Screenshot 2025-09-01 213834" src="https://github.com/user-attachments/assets/ace29ca1-72ca-45c8-8408-a03182e29db0" />


## XOR alp
```
MOV AL,0BH
MOV BL,05H
XOR AL,BL
```

## Output

<img width="1709" height="634" alt="Screenshot 2025-09-01 213903" src="https://github.com/user-attachments/assets/54807c2a-f873-4045-a5c9-88430d5fcd40" />


## NAND alp
```
MOV AL,0BH
MOV BL,05H
AND AL,BL
NOT AL
```

## Output

<img width="1652" height="625" alt="Screenshot 2025-09-01 213929" src="https://github.com/user-attachments/assets/0bb9d19f-7720-4515-82dd-1fef0f912eee" />


## Result :
 
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.


















