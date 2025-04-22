## looping over an array using forEach method
for example we we wanna loop over a movments array .
```javascript
movments.forEach(function(movment)){
}
```
**forEach method requires a callback function**in order to tell what to do 
* *its the foreach method that will call this callback function.* *
  forEach method loop over an array and in each iteration it will execute the call back function.
  also as the forEach method calls this callback function,in each iteration it will pass in the current element of the array as an argument.
  ## getting access to the current index of an array
  in fact foreach passes in the current element,the index and the entire array that we are looping.**we can specify them in our parameter list**
  ```javascript
  movements.forEach(function(movement,index,array)){}
  ```
  * *the order is important so the first parameters always need to be the current element second parameter is the current index and the third one is the entire array.* *
    ## forEach with maps and sets
   ### maps:
  ```javascript
  const currencies=new Map([]);
  currencies.forEach(function(value,key,map){});
    ```
  it has also three arguments the first one is current value in the current iteration,the second one is the key,and the third one is the entire map that is being looped over.
  ### set
```javascript
const currenciesUnique=new Set([]);
currenciesUnique.forEach(function(value,map));
  ```
**sets only has unique values.** 

  
  
  
  
