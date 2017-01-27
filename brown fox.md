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

```
var sentence = "JavaScript For Kids A Playful Introduction To Programming";

function findLongWord(inputSentence){
  var wordArr = inputSentence.split(" ");
  var longLength = 0; 
  var longestWord = ""; 

for(var i = 0; i < wordArr.length; i++){
 
  if(longLength < wordArr[i].length){
    longlength = wordArr[i].length;
    longestWord = wordArr[i]; 
    
  }
}
  
  console.log(longlength);
  console.log(longestWord);
  
}

findLongWord(sentence); 
```
