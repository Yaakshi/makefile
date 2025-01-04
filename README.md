### Assume n is the input number. Do the following tasks step by step.

#### 1) Create a dynamic library file(libsec.so) which contains the following functions:
   - #### Checking n is Armstrong number or not using conditional expression
   - #### Counting number of even digits in n

Creating libsec.c file with the above functions:

![image](https://github.com/user-attachments/assets/f071d877-51a4-4182-8e1d-66efc04f35c6)

Creating libsec.so:

![image](https://github.com/user-attachments/assets/8ad346c2-6d6b-49ad-9d09-349ed3fed18e)

#### 2) Create a static library file (libfirst. a) which contains the following functions
   - #### Checking n is divisible by 5 or not
   - #### Find the reversal of number n

Creating libfirst.c file with the above functions:

![image](https://github.com/user-attachments/assets/a93cd5f8-2fdb-454c-824c-f7f1f4f848b6)

Creating libfirst.a file:

![image](https://github.com/user-attachments/assets/f753057c-ed42-4441-a1b9-1eae802600f8)

#### 3) Create a main file (file.c) which calls the above functions defined in 1) and 2) with necessary header files.

Creating libsec.h header file:

![image](https://github.com/user-attachments/assets/4abffcc3-cf26-4aa6-a646-2ecfb848a0c2)

Creating libfirst.h header file:

![image](https://github.com/user-attachments/assets/b60301da-d981-42f1-a1b4-638bbe334f5b)

Creating file.c main file:

![image](https://github.com/user-attachments/assets/63be2fe7-cfe7-49d9-b5c6-75c5d4402471)

Export ./file to environment variable:

![image](https://github.com/user-attachments/assets/0abebdc7-0e2e-4cd9-a369-dcf4459c3336)

#### 4) Create a python program (Palidrome.py) for checking n is a Palindrome number or not

Creating palindrome.py file:

![image](https://github.com/user-attachments/assets/dec73323-28ba-4189-bffc-120e7ceaaf01)

#### 5) Write a shell script (check.sh) which sequentially executes the programs file.c and Palidrome.py

Creating check.sh file:

![image](https://github.com/user-attachments/assets/56be3eba-103f-419d-a2c4-069c74402cf8)

#### 6) The Makefile contains the following statements
   - #### Command for linking the library files (libfirst.a and libsec.so) with the object file of file.c
   - #### Command to give permission for check.sh to execute
   - #### Command to execute the script check.sh

![image](https://github.com/user-attachments/assets/921773bb-769f-4671-971c-8ba8a44c736e)

#### Display the outputs for the tasks (1.a, 1.b, 2.a, 2.b, 3 and 4) by a single make command in the CLI.

![image](https://github.com/user-attachments/assets/58b4d7ce-dd92-49bc-a441-9270802d0f3f)









