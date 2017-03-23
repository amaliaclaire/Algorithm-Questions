```
let pets = {
  Joey: "Dog",
  Jtessica: "Cat",
  John: "Rabbit",
}

let iceCreamMenu = {
  toppings: ['chocolate', 'sprinkles', 'fudge'],
  flavors: ["vanilla", "strawberry"],
  singleScoopCost: 3.44,
}

for(const key in iceCreamMenu){
  if(key === 'toppings'){
    iceCreamMenu[key].forEach((topping)=>{
      console.log(topping)
    });
      
    }else if(key === 'flavors'){
      iceCreamMenu[key].forEach((flavor)=>{
        console.log(flavor)
      })
      
    }else{
      console.log(iceCreamMenu[key])
    }
    
  }
  ```
