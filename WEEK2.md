<div id="top">
<p align="center">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme#readme">Back to index</a>)</p>
<p align="left">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme/blob/main/WEEK1.md">Back to previous week</a>)</p>
<p align="right">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme/blob/main/WEEK1.md">Go to Next week</a>)</p
</div>
 
<div id="title ">
 
#  $$\textcolor{skyblue}{\text{WEEK 2}}$$

</div>

## **DAY 4, TUESDAY 26/7/2022**


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

## **DAY 5, WEDNESDAY 27/7/2022**


### **Holiday VIII - Duty Free**<br>

#### Solution:
```javascript
function dutyFree(normPrice, discount, hol){

  let holiday = (hol/(normPrice*discount))*100;
  let result = Math.floor(holiday);
  
  return result;
}
```

#### Result:

```javascript
 (dutyFree(12, 50, 1000), 166);
 (dutyFree(17, 10, 500), 294);
 (dutyFree(24, 35, 3000), 357); 
 
```
 
 ### **Holiday VIII - Duty Free**<br>

#### Solution:
```javascript
function twiceAsOld(dadYearsOld, sonYearsOld) {
   return Math.abs(dadYearsOld-(sonYearsOld+sonYearsOld));
}
```

#### Result:

```javascript
("Testing for dad's age: 36 and son's age: 7", (twiceAsOld(36,7) , 22);
 
("Testing for dad's age: 55 and son's age: 30", (twiceAsOld(55,30) , 5);

("Testing for dad's age: 42 and son's age: 21", (twiceAsOld(42,21) , 0);

("Testing for dad's age: 22 and son's age: 1",  (twiceAsOld(22,1) , 20);
 
("Testing for dad's age: 29 and son's age: 0",  (twiceAsOld(29,0) , 29);
 
 ```
 
  ### **Valid Spacing**<br>

#### Solution:
```javascript
// que no hayan espacios de inicio y final-false
// que no hayan espacios dobles o triples, en medio de las letras-false
// que si lea las mayusculas 
// que lea los strings vacios como true

function validSpacing(s) {
  let vowels = s.toLowerCase();
   let string = vowels.split('');
  for (i=0; i<string.length; i++){
    if ( string[0] ===' '||string[string.length-1] ===' '
        ||string[i] ==='   '|| string[i+1] === i){
     return false;
    }
    else {return true;}
  
}
}

console.log (validSpacing("Hello  world"));
```

#### Result:

```javascript
 ```
 
   ### **Fake Binary**<br>

#### Solution:
```javascript
function fakeBin(x) {
  let bin = x.split ('');
  for (i=0; i< bin.length; i++ ){
    if (bin [i]<5 ){
      bin [i]=0;
    }
    else {bin[i] =1;}
  }
  
  return bin.join('');
 }
```

#### Result:

```javascript
(fakeBin('45385593107843568'), '01011110001100111');
(fakeBin('509321967506747'), '101000111101101'); 
(fakeBin('366058562030849490134388085'), '011011110000101010000011011');
 ```
<p align="right">(<a href="#top">back to top</a>)</p>
