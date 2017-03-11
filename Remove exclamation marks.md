Write function removeExclamationMarks which removes all exclamation marks from a given string.

``` 
function removeExclamationMarks(s){
  var newString = s.split("!").join("");
  
  return newString; 
}

removeExclamationMarks('value');
```


```
function removeExclamationMarks(string){
  return string.split('!').join(''); 
}

removeExclamationMarks('HELLO!!!')

```
