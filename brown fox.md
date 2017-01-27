take a sentence and return the longest word in the sentence
"The Quick Brown Fox Jumps Over a Lazy Dog"
use array to find answer 
clarifying question words of the same length; which one do you want me to output - first or last or all? 
var for lenght + var for length name 

```
var sentence = "The Quick Brown Fox Jumping Over a Lazy Dog";

function longestWord(sentence){
 
 var sentenceArr = sentence.split(" "); 
 var length = 0; 
 var curLongWord = ""; 
   
 
 for(var i = 0; i < sentenceArr.length; i++ ){
   

   if(length < sentenceArr[i].length ){
      length = sentenceArr[i].length; 
      curLongWord = sentenceArr[i]; 
    
  }
  
 }
  
  console.log(length);
console.log(curLongWord);
}


longestWord(sentence);
```
