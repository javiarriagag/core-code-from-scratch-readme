<p align="right">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme#readme">back to index</a>)</p>


#  $$\textcolor{skyblue}{\text{WEEK 2}}$$



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
