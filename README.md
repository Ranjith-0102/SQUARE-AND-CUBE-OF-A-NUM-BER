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
<img width="1920" height="1200" alt="Screenshot 2025-09-29 214351" src="https://github.com/user-attachments/assets/e087beba-b822-4ef9-8b3a-01d02069f4d3" />
<img width="902" height="633" alt="Screenshot 2025-09-29 214325" src="https://github.com/user-attachments/assets/40107b4e-61b4-4c46-b9b8-080219b8f3fc" />


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
<img width="1920" height="1200" alt="Screenshot 2025-09-29 214804" src="https://github.com/user-attachments/assets/b50a3bc5-e996-4e4e-9ea2-3a29cac1a5bf" />
<img width="857" height="680" alt="Screenshot 2025-09-29 214822" src="https://github.com/user-attachments/assets/8ca90080-8028-4bc2-8313-2d947684737c" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
