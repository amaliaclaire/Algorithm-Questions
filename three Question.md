function ordinal_up_to(num){
  var result = "";
  
  for(var i = 1; i <= num; i++){
    if(i ===num){
      result += fizzBuzz(i)
    }else{
      result += fizzBuzz(i) + ","
    }
  }return result; 
  
}

var n = 1; 

function count (i){ 
  //we are feeding n into our function to be used 


    
    //for(var i = 1; i < n +1; i++){
    // we are starting at 1 because we don't need 0. we are doing n + 1 because we want to run all the way through the last number 
   var lastNum = i % 10;
   //using moduluo operator to get the last number - the remainder of the number divided by 10
    if(i === 11){
       console.log(i + "th");
    }else if (i === 12){
      console.log(i + "th")
    }else if (i === 13){
      console.log(i + "th")

      // 11/12/13 are edge cases since they don't fit the logic. 

    }else if(lastNum === 1){
      console.log(i + "st");

    } else if(lastNum === 2){
        console.log(i + "nd");
    } else if(lastNum === 3){
        console.log(i + "rd");

    } else{
        console.log(i + "th");
    }
 // }



}


var fizzBuzz = function (number){
  
  for(var i = 1; i <= number; i++){
    if(i % 3 === 0 && i % 5 === 0){
      console.log("fizzbuzz");
    }else if(i % 3 === 0){
      console.log("fizz");
    }else if(i % 5 ===0){
      console.log("buzz");
  }else{
    // console.log(count(i));
    count(i)
  }
} 

} 



fizzBuzz(100);
