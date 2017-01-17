var n = 1212; 

function count (n){ 
  //we are feeding n into our function to be used 
  for(var i = 1; i < n + 1; i++){
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
  }
  
  
  
};
count(n);
//calling our function here
