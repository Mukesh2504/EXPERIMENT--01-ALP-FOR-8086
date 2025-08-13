# EXPERIMENT--01-ALP-FOR-8086
Name :
Roll no 
Date of experiment :





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
```nasm
org 100h

mov ax, 4535h
mov bx, 733fh
add ax,bx  

ret
```
## Output  
<img width="820" height="487" alt="Screenshot 2025-08-13 091647" src="https://github.com/user-attachments/assets/dd77caa1-5078-48d0-9061-49c35333f325" />
<img width="636" height="337" alt="image" src="https://github.com/user-attachments/assets/faabbd0e-6089-47b0-bf74-67fa571540c9" />

## Subtraction   of 8 bit numbers  ALP 
```nasm
org 100h

mov ax, 4535h
mov bx, 733fh
sub ax,bx  

ret
```
## Output 
<img width="636" height="337" alt="Screenshot 2025-08-13 092000" src="https://github.com/user-attachments/assets/ff937b30-914a-4da8-bab7-094b19898da9" />
<img width="820" height="487" alt="image" src="https://github.com/user-attachments/assets/818ee1d4-df73-48a5-b0bd-43df83975325" />

## Multiplication alp 
```nasm
org 100h

mov ax, 3h
mov bx, 2h
mul ax

ret
```
 ## Output  
 <img width="636" height="337" alt="image" src="https://github.com/user-attachments/assets/46170837-6775-4bce-845b-92a8c04d1d92" />
 <img width="708" height="545" alt="image" src="https://github.com/user-attachments/assets/9538aa5c-8e7c-4486-9748-94831c3b65c0" />


## Division alp 

## Output  


## Result :
 








