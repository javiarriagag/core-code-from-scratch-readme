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
 ```
 
 #### Result:
 ```javascript
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
