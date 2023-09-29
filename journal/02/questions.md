# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | var,let,const |

02. What is the definition of a function?

    > | functions are blocks of code that are made to preform a specific task or set of tasks. The code blocks of code contained in the function are only ran when invoked  |

03. What are the `SOLID` principles?

    > | S: Single Responsibility Principle
        O: Open-Closed Principle
        L: Liskov Substitution Principle    
        I: Interface Segregation Principle
        D: Dependency Inversion Principle 
     |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | delete fruit[2] |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | 
    you.friends[0] = you; 
    them.friends[0] = them;
      |

06. Give an example of a JavaScript `Conditional`:

    > | if(condition) {

    }else if(condition2){

    } 
      |

07. What is the main difference between `parameters` and `arguments`?

    > | parameters are place holders that are defined when a function is made they are used to reference the value. Arguments are the actual values that are passed to the function. |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | with chrome dev tools you are able to set breakpoints to pause your code on a specific line to see what's causing issues you can also manually write breakpoints in your code |

09. What is the difference between a `primitive` value and a `reference` value?

    > | primitive values are more simple like numbers or strings they don't reference or point to any value they are the value the actual data. Reference values are more complex they are referencing or pointing to data.  |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for(let i = -100; i <= 100; i++){
        console.log(i)
    }
      |
