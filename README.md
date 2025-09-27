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
<img width="1919" height="1081" alt="image" src="https://github.com/user-attachments/assets/f75ad6e1-6491-454d-9894-60fad09931b7" />
<img width="297" height="232" alt="image" src="https://github.com/user-attachments/assets/db905643-5b94-42ed-945b-587eb693eb14" />



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
<img width="1919" height="1125" alt="image" src="https://github.com/user-attachments/assets/65db8f7f-5465-42a4-bb3a-b0b27d268674" />

<img width="240" height="231" alt="image" src="https://github.com/user-attachments/assets/790b3d9d-8125-487f-b79d-97ef495a5fd8" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
