<div id="top">
<p align="center">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme#readme">Back to index</a>)</p>
<p align="left">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme/blob/main/WEEK2.md">Back to previous week</a>)</p>
<p align="right">(<a href="https://github.com/javiarriagag/core-code-from-scratch-readme/blob/main/WEEK1.md">Go to Next week</a>)</p
</div>
 
<div id="title ">
 
#  $$\textcolor{skyblue}{\text{WEEK 3}}$$

</div>

## **DAY 7, MONDAY 1/8/2022**


### **Who likes it**<br>
 
 #### Solution:
```javascript
function likes(names) {
  for (i=0; i<names.length;i++){
    if(names.length ===1){
      return  names+ ' '+ 'likes this';
    }
    if(names.length ===2){
      return  names[0]+ ' and '+ names[1]+ ' '+'like this';
    }
    if(names.length ===3){
      return  names[0]+ ', '+ names[1]+ ' and '+ names[2]+ ' ' +'like this';
    }
    
    if(names.length >=4){
      return  names[0]+ ', '+ names[1]+ ' ' + 'and '+ (names.length-2) +' others like this';
    }
  } 
  return 'no one likes this';
}

```

#### Result:
 ```javascript
(likes(['Peter']), 'Peter likes this');
(likes['Jacob', 'Alex']), 'Jacob and Alex like this');
(likes(['Max', 'John', 'Mark']), 'Max, John and Mark like this');
(likes(['Alex', 'Jacob', 'Mark', 'Max']), 'Alex, Jacob and 2 others like this');

```
 

### **Bit counting**<br>
 
 #### Solution:
```javascript
 let countBits = function(n) {
  let binary= n.toString(2);
  let numsArr = Array.from(String(binary), Number);
  let sum = 0;
  for (let i = 0; i <numsArr.length; i++) {
    sum += numsArr[i];
  }
  return sum;
}

```

#### Result:
 ```javascript
(countBits(0), 0);
(countBits(4), 1);
(countBits(7), 3);
(countBits(9), 2);
(countBits(10), 2);                                    

```
 

### **Your order, Please**<br>
 
 #### Solution:
```javascript

```

#### Result:
 ```javascript

``` 
 <p align="right">(<a href="#top">back to top</a>)</p>
 
 ## **DAY 8, TUESDAY 2/8/2022**


### **Simple Pig Latin**<br>
 
 #### Solution:
```javascript
 function pigIt (str) {
 let empt =['!', '¡', '?', '¿', '.', ',', ':', ';'];;
  str = str.split (' ');
  for (let i=0; i<str.length;i++){
    if (empt.indexOf(str[i]) >= 0) continue;
    str[i] = str[i].slice(1) + str[i].slice(0, 1) + 'ay';
      } 
  return str.join(' ');
}
 ```
 
 #### Result:
 ```javascript
pigIt('Pig latin is cool'),'igPay atinlay siay oolcay')
pigIt('This is my string'),'hisTay siay ymay tringsay')
``` 
 
### **Counting Duplicates**<br>
 
 #### Solution:
```javascript
 ```
 
 #### Result:
 ```javascript
``` 
 
 ### **Decode the Morse Code**<br>
 
 #### Solution:
```javascript
 ```
 
 #### Result:
 ```javascript
``` 
 
<p align="right">(<a href="#top">back to top</a>)</p>

 
  ## **DAY 9, WEDNESDAY 3/8/2022**


### **Valid Parentheses**<br>
 
 #### Solution:
```javascript
 
 ```
  #### Result:
 ```javascript
 
 
``` 
 
### **Convert string to camel case**<br>
 
 #### Solution:
```javascript
 
 ```
  #### Result:
 ```javascript
 
 
``` 
### **Unique in order**<br>
 
 #### Solution:
```javascript
 
 ```
  #### Result:
 ```javascript
 
 
``` 
 
<p align="right">(<a href="#top">back to top</a>)</p>
 
 
   ## **DAY 10, THURSDAY 4/8/2022**


### **Fold an array**<br>
 
 #### Solution:
```javascript
 
 ```
  #### Result:
 ```javascript
 
 
``` 
 
### **Encrypt this**<br>
 
 #### Solution:
```javascript
 
 ```
  #### Result:
 ```javascript
 
 
``` 
 
### **Corecode Challenge 1**<br> 
 ```javascript 

I’m Javi, I’m a inventive person, I center myself around integrity, honesty, ingenuity, passion and loyalty. 
I like to learn how the world works. My background is on design. I’ve been on interiors, garment design, digital design, 
etc. Currently I’m on the managing side of a wholesale company. I would love to find a place where I can merge my passion 
for design, with my developer skills, for example on a garment company that merges tech with products as Nike.
``` 
<p align="right">(<a href="#top">back to top</a>)</p>
