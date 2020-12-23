<h1>Streams</h1>
<hr>
<a href="README.md">&lt;&lt; README </a>
<hr>

- Def :
    - A way of supporting functional-style operation on collections 
        - (functional-style operations) :
            - Aggregate operations that work on a set of values 
<hr>

- Stream is an interface with lots of functions on it 
<hr>


<h2>Examples for Functions on streams </h2>

- `filter`()

    - Takes a predict
    - Remove elements from the stream that does not match the predict
    
- `sorted`()

    - Takes a comparator or no arguments
<hr>

- `map`()

    - Transform element from one value to another
    - Takes a method reference
    
- `flatMap`()

    - Transform elements from one value to zero, 1 or more values
<hr>

- `forEach`()
<hr>

- `anyMatch`()

    - Takes a predict
    - Return true if any element match the predict
    
- `noneMatch`() 

    - Return true if no elements match the predict
    
- `allMatch`() 

    - Return true if all element match the Predict
<hr>

- `skip`(long n)

    - Discard next n elements
    
- `limit`(long n)

    - return next n elements
<hr>

- `min`()

    - Take a comparator or nothing
    - Return the minimum element in the stream
- `max`()

    - Take a comparator or nothing
    - Return the maximum element in the stream
<hr>

- `findFirst`()

    - Return the first element in the stream
    
- `findAny`()

    - Return a random element
<hr>

- `count`()

    - Return the number of elements in the streams
<hr>


- `reduce`()

    - Combine elements together using a combination function
    
    - Takes:
            - An initial value for the accumulator and a function
        
              - The combination function takes :
        
                    - The accumulator and the  next element   
<hr>


<h2>Collectors :</h2>
- Part of the stream api that allow you to build finial values that are big and complex from a stream

- Example :

    - collect()
             - Takes a collector
             
                - Examples for a collectors
                
                    - collecting as a list :
                    
                      - `Collectors.toList()`
                      
                    - Collecting as a map :
                    
                        - `Collectors.groupingBy(the thing to group by)`
    
- ---------------------------

<h2>Are streams always better than loops?</h2>

- Streams are:

    -  high level construct    
    - Optimized framework
    - General better readability
    - Some corner worse cases :
    
            - Are worse readability
            - Are worse performance
            
- Loops :
    - Low level construct
    - Can be faster
    - Readability is subjective 
    - Nicer with check exceptions
    
- ----------------------------

<hr>
<a href="README.md">&lt;&lt; README </a>
<hr>


