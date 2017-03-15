Remove a exclamation mark from the end of string.

```
function remove(s){
  if(s.charAt(s.length-1) == '!'){
    return s.substring(0, s.length-1)
  }else{
    return s; 
  }
}

```
