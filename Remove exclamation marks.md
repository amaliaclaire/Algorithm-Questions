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


.join() used to join all elements in an array together into one big string. 
.split() splits into an array of strings by separating the string into substrings.
