//every number divisble by 7 replace with cat. every number divisibe by 3 replace with dog. every number divisible with both please do catDog
 

```
function catDog(number){
  
  for(var i = 1; i < number + 1; i++){
    if( i%7 === 0 && i%3 ===0){
      console.log('catdog');
      
    }else if(i%3 ===0){
      console.log(i + ' dog'); 
    }else if(i%7 === 0){
      console.log(i + ' cat');
    }else{
      console.log(i + '');
    }
    
  }
  
  
}

catDog(100); ```

