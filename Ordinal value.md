//write a function called ordinalUpTo() that returns a string with ordinal values for each number from 1 up to n (an argument of this function), formatted like this "1st", "2nd", "3rd"

function ordinalUpTo(num){ // we are making a function called "ordinalUpTo"
  var result = ""; //it is a variable because we're going to add on later
  for(var i = 1; i < num + 1; i++){ // i = 1; and the for loop runs while i is less than the num. The for loop will stop when i is = to num, so when it turns false, the loop will stop. 
    //console.log(i);// we want to test the [i];
    if (i === num ){ // is i equal to num? did we get to the last number? 
      result += ordinal(i) // i DOES equal num === true
    }else {
      result += ordinal(i) + ","; // we want to separate the numbers because there will be more numbers
      
    }
        
  }
return result; // we want to return the result when the for loop is finished
}
function ordinal (x){ // this function ordinal takes ONE input (which is a number) we want this function to take the number we give it & then add on a string. ie "th" or "st" or "nd" 
  return x + "th";  //  or return `${x}th`; 
 
}


console.log(ordinalUpTo(10));





w/out all the comments 
function ordinalUpTo(num){
  var result = "";
  
  for(var i = 1; i < num + 1; i++){
    if (i === num){
      result += ordinal(i)
    }else{
      result += ordinal(i) + ","
    }
  }
return result; 
}
function ordinal (x){
  return x + "th";
}

console.log(ordinalUpTo(20));
