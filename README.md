# ES6_Features

## Constants

*Support for immutable varibales i.e which cannot be re-assigned new content. This only makes only Varibale itself immutable not the content itself*

```
  const name = "github"
  name = "node" // this will give you compile error
  
  const person = {}
  person.firstName = "firstNAME" //this will not

```

## Block Scope Varibales

  *javascript do not have scope. Variables in javascript are scoped to their nearest parent function or globally if there is no function present. ES6 gives us block scoping via to new keywords - let and const*
  
  ```
    for(let i=0; i<5; i++){
      console.log(i)
    }
    console.log("outside for loop:::::"+i) //prints undefined

    for(var i=0; i<10; i++){
       console.log(i)
    }
    console.log("outside for loop:::::"+i) //prints 10
  ```
