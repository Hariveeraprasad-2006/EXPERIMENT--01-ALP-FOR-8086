# EXPERIMENT--01-ALP-FOR-8086
# Name : Arikatla Hari Veera Prasad
# Roll no :212223240014
# Date of experiment :22-08-2024





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
org 100h
mov al,024h;
mov bl,al;
add bl,al;
mov [0123h],bl;
ret
```


## Output  
 ![image](https://github.com/user-attachments/assets/687f6d30-adbf-4d56-8d38-4b4b8eefd351)

## Subtraction   of 8 bit numbers  ALP 
 ```
mov al,24h
mov bl,14h
sub al,bl
hlt

```
## Output  
![image](https://github.com/user-attachments/assets/f910925d-634b-46a7-88ac-22a386e7941a)



## Multiplication alp 
```
org 100h
mov al,10h
mov bl,6h
mul bl
hlt
ret
```

 ## Output  

![image](https://github.com/user-attachments/assets/3653d06d-6951-43e3-ab16-d2d7825e9a58)



## Division alp 
```
org 100h
mov al,40h
mov bl,2h
div bl
hlt
ret
```
## Output  

![image](https://github.com/user-attachments/assets/75e0d9e2-0a02-4074-b5d2-f45964eef0b4)



## Programs for logical operators

# AND
```
MOV [SI],AX;
MOV AX,0A32H;
MOV BX,0B13H;
AND AX,BX;
```

# OUTPUT
![image](https://github.com/user-attachments/assets/7f08c772-00d6-40aa-b14d-1505a009cbdf)


# OR
```
org 100h

MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
ret
```

# OUTPUT
![image](https://github.com/user-attachments/assets/a8c05c1f-f3ea-42ad-a62e-b01cff6f2dac)

# NOT
```
MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
```
# OUTPUT
![image](https://github.com/user-attachments/assets/21bbbb81-5f0a-46bf-9337-eb4399ee64b3)

# XOR
```
org 100h

MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
ret
```
# OUTPUT
![image](https://github.com/user-attachments/assets/8b89a041-1d9b-4501-ab20-701b5d155b9c)


## Result :
 Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.







