# mpmc-expt-3 
3.Square-cube-of-given-number
8051 Square Program

**AIM**

To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

**APPARATUS REQUIRED**

Personal computer
Keil μVision IDE

**ALGORITHM**

Enter the Assembly language program.
Provide the input value to Port 0 (P0).
Execute the program.
The output square value is stored in Port 2 (P2).

**PROGRAM**

ORG 0000H

MOV R0,#50H

MOV A,@R0

MOV B,@R0

MUL AB

INC R0

MOV @R0,A

END

**OUTPUT**

<img width="957" height="217" alt="image" src="https://github.com/user-attachments/assets/301f3d73-2cc3-4764-b5b2-1285a73fd335" />

**RESULT**

Thus, the square of the given data is calculated using 8051 Keil.

8051 Cube Program

**AIM**

To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

**APPARATUS REQUIRED**

Personal computer
Keil μVision IDE

**ALGORITHM**

Enter the Assembly language program.
Provide the input value.
Execute the program.
The output cube value is stored in a memory location.

**PROGRAM**

ORG 00H

MOV R0,#50H

MOV A,@R0

MOV B,A

MUL AB

MOV B,@R0

MUL AB

INC R0

MOV @R0,A

INC R0

MOV @R0,B

END

**OUTPUT**

<img width="961" height="257" alt="image" src="https://github.com/user-attachments/assets/49a54b33-f131-4bbc-bf49-063f56d6e38f" />

**RESULT**

Thus, the cube of the given data is calculated using 8051 Keil.
