# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```asm
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
INC R0
MOV @R0,A
END

```

## CALCULATION
![WhatsApp Image 2026-02-23 at 5 57 05 PM](https://github.com/user-attachments/assets/350572c1-7660-4920-8cf0-b1a785b12a10)


## OUTPUT
<img width="984" height="592" alt="image" src="https://github.com/user-attachments/assets/28a30fe5-9217-43f6-b8dc-5b29dda888c0" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```asm
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
MOV @R0,A
END

```
## CALCULATION
![WhatsApp Image 2026-02-23 at 5 57 37 PM](https://github.com/user-attachments/assets/cf2a2f18-6494-473c-8341-0080349bfff1)


## OUTPUT
<img width="984" height="592" alt="image" src="https://github.com/user-attachments/assets/88d4bef1-8685-47bf-9dc4-8fbd779e8f15" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


