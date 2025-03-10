# EXPERIMENT--01-ALP-FOR-8086
Name : karthick v

Roll no : 212223040086

Date of experiment : 10/03/2025





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
MOV AL, 74h
MOV BL, 69h
ADD AL, BL
HTL
```



## Output  
![Screenshot 2025-02-28 083028](https://github.com/user-attachments/assets/03bb0235-66c4-42f6-8ba5-5fe2e47070e1)

 
## Subtraction   of 8 bit numbers  ALP 
```
MOV al, 74
MOV bl, 69
SUB al, bl
HTL
```

 
## Output  
![Screenshot 2025-02-28 083935](https://github.com/user-attachments/assets/5a6a22cf-a0bb-4221-9d4a-43ed5e117423)

## Multiplication alp 
```
org 200h
MOV al, 75
MOV bl, 32
MUL al, bl
HTL
ret
```

 ## Output  

![Screenshot 2025-02-28 084653](https://github.com/user-attachments/assets/fccbbae4-3094-4f0f-85c5-ba717b051911)

## Division alp 
```
MOV al, 68
MOV bl, 18
DIV al, bl
HTL
ret
```

## Output 

![Screenshot 2025-02-28 084956](https://github.com/user-attachments/assets/26037c4b-cf1a-48e0-9509-37a2826119f3)

## And of 8 bit numbers ALP
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## output 

![Screenshot 2025-02-28 085825](https://github.com/user-attachments/assets/72f146a3-28ac-4ca7-9213-7012013e09f3)

## OR of 8 bit numbers ALP
```
MOV AL,33H
MOV BL,44H
OR AL,BL
HLT
```
## output

![Screenshot 2025-02-28 090133](https://github.com/user-attachments/assets/db5ba230-8656-46ee-bfbc-4aa468ae1730)

## NOT of 8 bit number ALP
```
MOV AL,65H
NOT AL
HLT
```

## output
![Screenshot 2025-02-28 090359](https://github.com/user-attachments/assets/c57eee7a-b6e6-4815-8775-0cc3ec0f4282)



## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








