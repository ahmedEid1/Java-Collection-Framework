<h1>Notes</h1>

<hr>
<a href="README.md">&lt;&lt; README </a>
<hr>

<hr>

- if you try to modify a collection while iterating  over it using (for each) :
  - You get Concurrent Modification Exception
  - _**Use a regular iterator if you want to modify**_

<hr>

- Encapsulate collections into your business domain class
- _A functional interface_ :
    - An interface with  single abstract method
      - Example : `Comparator --> compare`

<hr>


- _Interfaces_ :
    - Define behaviors
- _Implementation_ :
    - Determine performance

<hr>

- Can I use null as a key ?
  - Depend on the map implementation
    - **Hash map** can have null key and null values
    - **Tree map** can have null values only
    
<hr>

- Objects allow more flexible generic contract

<hr>

- Java does not have a pair type :
    - So we use the Map.Entry interface

<hr>

- Don’t **mutate** the key in the hash map:
  - **_Make sure the key hashCode return the same value every time_**

<hr>

- Predict :
  - A function that return true or false 
<hr>


<hr>
<a href="README.md">&lt;&lt; README </a>
<hr>