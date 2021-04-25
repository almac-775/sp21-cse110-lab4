# Lab4 Part1

## Part1a  
```
    1. values added: 20
    
    2. values added: 20
    
    3. values added: 20
    
    4. Error, since result is in the scope of the if block.
    
    5. values added: 0
    
    6. Error, since result is in the scope of the if block.
```

## Part1b
```
    1. 3
    
    2. 150
    
    3. 150
    
    4. [50, 100, 150]
    
    5. Error, since *i* is in scope only within the for block.
    
    6. Error, since *discounted price* is not in scope.
    
    7. 0
    
    8. []
    
    9. Error, since *i* is out of scope.
    
    10. 3
    
    11. Error, since in line 8 we're trying to push to an unchangeable array.
    
    12. A. student.name
        B. student["grad year"]
        C. student.greeting()
        D. student.greeting("Favorite Teacher".name)
        E. courseLoad[0]
    
    13. A. 32, integers map to their exact string representation
        B. 1, for same reason above
        C. 3, since null maps to 0
        D. 3null, since both are strings
        E. 4, since true is mapped to 1
        F. 0, since false and null are mapped to 0
        G. 3undefined, since both are strings
        H. NaN, undefined is not a valid number

    14. A. true, since '2' is converted to a number
        B. false, since '2' and '12' are converted to numbers
        C. true, since '2' is converted to a number
        D. false, since 2 and '2' are different types
        E. false, since true is mapped to 1
        F. true, since the value passed in is not 0 or null, so Boolean returns true

    15. === is used for comparing without converting data type, whereas == lets converts variables before comparing.

    17. [2,4,6]
        The array passed in as an argument contains small numbers, so all I had to do was see how the callback function was used. I noticed that in line 4, each value in [1,2,3] were passed in as arguments in doSomething, which returns the value at each index multiplied by 2. Basically, I stepped into doSomething each time it was called, then kept track of the values that were returned by the callback and pushed into newArr.

    19. 1342
```