<p align="center">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme#readme">Back to index</a>)</p>
<p align="left">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme/blob/main/WEEK1.md">Back to previous week</a>)</p>
<p align="right">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme/blob/main/WEEK1.md">Go to Next week</a>)</p

 
<div id="top">
 
#  $$\textcolor{skyblue}{\text{WEEK 2}}$$

</div>

## **DAY 4, TUESDAY 25/7/2022**


### **Multiply**<br>

#### Faulty code:
```javascript
function multiply(a, b){
 a * b
}
```




#### Solution:

```javascript
function multiply(a, b){
 return a * b;
}

``` 


### **ASCII Total**<br>

#### Solution:
```javascript
function uniTotal (string) {
  
  
  if (string != '' ){
  let strSplit = string.split('');
   let res = strSplit.map(l => l.charCodeAt());
   let reducer = (accumulator, curr) => accumulator + curr;
   let fin =(res.reduce(reducer));
   return fin;}
  else {return 0;}
  

 }

```

#### Result:

```javascript
"", 0;
"a", 97;
"b", 98;
"c", 99;
"d", 100;
"e", 101;
"aaa", 291;
"Mary Had A Little Lamb", 1873;
```



### **Char From ASCII Value**<br>

#### Solution:
```javascript
function getChar(c){
  let a = String.fromCharCode(c);
   return a;
}
```

#### Result:

```javascript
(getChar(55),'7')
(getChar(56),'8')
(getChar(57),'9')
(getChar(58),':')
(getChar(59),';')
(getChar(60),'<')
(getChar(61),'=')
(getChar(62),'>')
(getChar(63),'?')
(getChar(64),'@')
(getChar(65),'A')
```


### **Binary Addition**<br>

#### Solution:
```javascript
function addBinary(a,b) {
let i = (a +b).toString(2);
  return i;
}

```

#### Result:

```javascript
(addBinary (1,2), '11')
(addBinary (45,55), '1100100')
(addBinary (28,7), '100011')
```


### **Student's Final Grade**<br>

#### Solution:
```javascript
function finalGrade (exam, projects) {

if (exam >90 || projects >10)
   { return 100;} 
if (exam >75 && projects >=5)
    {return 90;}
if (exam >50 && projects >=2)
   { return 75;} 
else {return 0;}
}
```

#### Result:

```javascript
(finalGrade (100, 12 ), 100)
(finalGrade (99, 0), 100)
(finalGrade (10, 15), 100)
(finalGrade (85, 5), 90)
(finalGrade (55, 3), 75)
(finalGrade (55, 0), 0)
(finalGrade (20, 2), 0)
```
<p align="right">(<a href="#top">back to top</a>)</p>
