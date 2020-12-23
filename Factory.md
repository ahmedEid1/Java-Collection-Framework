<h1>Factories</h1>

<hr>
<a href="README.md">&lt;&lt; README </a>
<hr>

<h2>Factories :</h2>

- Create unmodified, immutable, empty or wrapping collections

- **Examples** :
    - `Collections.unmodifiableList()`
    - `Collections.unmodifiableMap()`
    
<hr>

- _**Encapsulation**_ :
    - **Unmodified**    
        - `Collections.Unmodified`: (unmodifiable view)
            - Reflect the changes in the backing collection
    - **Immutable** :
        - `Map.CopyOf` : (unmodifiable copy)
            - Unmodified but also does not  reflect the changes in the original list
        - `Map.of` : (key, value, key,  value …):  (immutable collection )
            - Unmodified map
    
<hr>

- Factory methods :
    - **Empty collection** :
        - example
            - `Collections.emptyList`
            - `Collections.emptyMap`
        - _Immutable_
        - _Used when you want to pass no value to a method that takes a collection_
        - _**Benefit**_ : refer to a static instance, so it saves memory 
    - **Singletons** :
        - Collections that contain one element 
        - Example :
            - `Collections.singletonMap`
            - `Collections.singleton` --> set
        - _Immutable_ 
        - _Memory efficient_
    - [].of :
        - Example :
            - `List.of`(e, a)
            - `Map.of`(k, v, k2, v2)
            - `Map.ofEntries(Map.entry(k, v)) `
        - _Runtime immutable_ 
        
    - [].`copyOf`:
        - _Immutable copy_
    
<hr>

- _**Operations**_ :
    - Useful collections algorithm
    -  examples :
        - Collections.`min`() or `max`():
            - Takes a collection and comparator
        - Collections.`addAll`():
            - Takes a collection, and the elements to add
        - Collections.`shuffle`():
            - Resort it randomly
        - Collections.`fill`():
            - _Takes a collection and one element and fill all the collection with this value_

<hr>


<hr>
<a href="README.md">&lt;&lt; README </a>
<hr>

