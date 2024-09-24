# EXPERIMENT--01-ALP-FOR-8086
## Name : D.B.V. SAI GANESH

## Roll no : 212223240025

## Date of experiment : 24-09-2024





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
 ![image](https://github.com/user-attachments/assets/9af052dd-9318-4a40-8019-4f8d7a79852a)

## Subtraction   of 8 bit numbers  ALP 
 ```
mov al,24h
mov bl,14h
sub al,bl
hlt

```
## Output:
![image](https://github.com/user-attachments/assets/d8704e66-a0c4-4285-a3b6-eacc13cb24bd)

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

![image](https://github.com/user-attachments/assets/280bfe56-ee5e-4651-bb84-e5dc78d780b0)

## Division alp 
```
org 100h
mov al,40h
mov bl,2h
div bl
hlt
ret
```
## Output:
![image](https://github.com/user-attachments/assets/b87b0cb6-5114-4496-a49b-68ba3d9ba5b3)

## Programs for logical operators

## AND :
```
MOV [SI],AX;
MOV AX,0A32H;
MOV BX,0B13H;
AND AX,BX;
```

## Output:
![image](https://github.com/user-attachments/assets/95bcbc4c-1a54-47c6-8fd0-95aece5d22a3)

## OR :
```
org 100h

MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
ret
```

## Output:
![image](https://github.com/user-attachments/assets/0edd40cc-b2fa-4f73-a0ad-e7ea524a6f8d)

## NOT :
```
MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
```

## Output:
![image](https://github.com/user-attachments/assets/bf54d622-f647-4d20-bacf-af78c9fdb255)

## XOR :
```
org 100h

MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
ret
```

## Output:
![image](https://github.com/user-attachments/assets/325879ea-6e2c-43d4-9525-132737c4a5bd)

## Result :
Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.










