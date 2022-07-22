<p align="right">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme#readme">back to index</a>)</p>


#  $$\textcolor{skyblue}{\text{WEEK 1}}$$


## **DAY 1, TUESDAY 19/7/2022**


### **Interpreted And Compiled Programming Languages :**<br>
- An interpreted language is the one that can be modified by several people in different locations with a specific translator, it might be slower and needs more steps than a compiled language. A compiled language can only be modified by one person at a time, if there's a modification or something that needs to be improved, it has to be written all over again, although it doesn't  need an additional step to be actionable by the computer. Also an interpreted language is easy to read, because it uses terminology of natural human languge.


### **Is Java compiled or interpreted, or both?**<br>
- Java can be both. Usually it is interpreted since it works with high level language and has to be interpreted by two steps JVM which compiles the information and Jit that executes directly, sometimes it will skip the JVM step to execute directly.

### **Pseudocode Currency Converter:**
```javascript
START
PRINT ("Welcome to  The bitcalculator")
Bitcoin<-- 45000
Dollars<--PRINT ("Indicate the amount of dollars you would like to exchange")
Dollars<-- GET
Dollars<-- READ
CONVERT <-- Dollars/Bitcoin
PRINT ("Your amount from Dollars to Bitcoin is ": CONVERT)
PRINT ("Thank you for using Thebitcalculator")
END
```

### **High and Low level languages:**

- A high level Language is one that's  understood , easy to read  and write by humans. Also, a high level language  might be the base language or older version of the new language for example c++ is a low level language  for Python. A Low level language is one that's  easily understood  by the computer, it is simple and can't imply much or give complex set of instructions. 
<br>
<p align="right">(<a href="#top">back to top</a>)</p>
<br>
<br>

## **DAY 2, WEDNESDAY 20/7/2022**
<br>

### **Your date of birth in the matrix?**
```javascript
Decimal: 1990 Binary: 11111000110
```

### **MIPS exercise:**<br>
```javascript
  .data 
        Intro: .asciiz "\n==== What numbers would you like to add? =====\n"
        result: .asciiz "\nThe result is: "
        number_one_msg: .asciiz "\nEnter the first number: "
        number_two_msg: .asciiz "\nEnter the second number: "
  .text
        main:
   li $v0, 4
   la $a0, welcome
   syscall
   li $v0, 4
   la $a0, number_one_msg
   syscall 
   li $v0, 5
   syscall 
   move $t0, $v0
   li $v0, 4
   la $a0, number_two_msg
   syscall     
   li $v0, 5
   syscall       
   move $t1, $v0
   add $t2, $t0, $t1
   i $v0, 4
   la $a0, result
   syscall
   li $v0, 1
   move $a0, $t2
   syscall
             
 ```           
<p align="right">(<a href="#top">back to top</a>)</p>


<br>


## **DAY 3, THURSDAY 21/7/2022**
<br>

### **Print special numbers:**
```javascript
for (let i = 0; i <=100; i++) {
 while (i%2) {
  i++;
}
console.log(i);
}
```
#### Solution:
```javascript
0
2
4
6
8
10
12
14
16
18
20
22
24
26
28
30
32
34
36
38
40
42
44
46
48
50
52
54
56
58
60
62
64
66
68
70
72
74
76
78
80
82
84
86
88
90
92
94
96
98
100
```

### **Bad code 1**
```javascript
var cond = false;

if ((cond = true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
```
The code is lacking "===". The use of triple equals guarantees that the computer will be doing 
the comparison with exactitude, while using just one "=" implies  that the computer will be matching only the class, in this case String.
<br>

#### Solution:
```javascript
var cond = false;

if ((cond === true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
```

### **Bad code 2**
```javascript
var n = 100;

if (n == 100) {
  console.log('This is a special number!');
}
if (n < 1000) {
  console.log('');
} else {
  console.log('Just a regular number');
}
if (n % 10 == 0) {
  console.log('This number is multiple of 10');
}
```
The code is lacking "===". The use of triple equals guarantees that the computer will be doing 
the comparison with exactitude, while using just one "=" implies  that the computer will be matching only the class, in this case String.
<br>

#### Solution:
```javascript
var n = 100;


if (n === 100) {
   console.log('This is a special number!');
 }
else if (n<1000 && n%10===0 && n!=100)
  {
     console.log('This is almost special' );

} else {
  console.log('Just a regular number');
  
}
```
