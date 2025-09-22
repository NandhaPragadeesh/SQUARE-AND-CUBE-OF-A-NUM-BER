# SQUARE AND CUBE OF A NUMBER
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
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR  
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END

```

## OUTPUT
<img width="1915" height="1018" alt="Screenshot 2025-09-22 215611" src="https://github.com/user-attachments/assets/d497e0ef-de32-4df9-a665-9a8a23ef6377" />
<img width="1427" height="699" alt="Screenshot 2025-09-22 215654" src="https://github.com/user-attachments/assets/fc18711c-078e-4127-b254-34a7ccdbd623" />


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
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END

```
## OUTPUT
<img width="1917" height="1015" alt="Screenshot 2025-09-22 220031" src="https://github.com/user-attachments/assets/bd247eee-3304-46b7-8fe8-8e87b21e866e" />
<img width="1197" height="627" alt="Screenshot 2025-09-22 220111" src="https://github.com/user-attachments/assets/046f7a9f-cbfb-44d6-b092-b3c51a2bcd7b" />
## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
