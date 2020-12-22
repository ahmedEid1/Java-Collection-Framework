<h1>Lists</h1>
<hr>

- Has a defined iteration order
- Every element has an index
<hr>

- _**Features**_ :
    
    - `add`:
  
            add(E e)
            add(int index, E e)
    
    - `addAll`(int index, Collection c)

    - `get`(int index)

    - `remove`(int index)

    - `set`(int index, E e) :
  
            Update the element at this index

<hr>

- **_Use cases_** :
    - Sorting a list :

            My_list.sort(Comparator c)

	- Sub list from a list :
		
            My_list.subList(start_index, end_index (exclusive))
	
	- Finding the index of an element :
      
            My_list.indexOf(element)

<hr>

- **_List implementations_** :
    - Array List
        - Has a backing array
        - Good general purpose implementation
        - CPU cache sympathetic
    
    - Linked List
      - Backed by a doubly linked List 
      - Wort performance in most cases
      - Use when :
                
            Adding to the start

            Adding and removing a lot

      - Implement the queue interface :
                
        * So it provides some feature that the ArrayList does not

<hr>
- _**Performance comparison :**_

<table>
<tr>
<th></th>
<th>Get</th>
<th>Add</th>
<th>Contain</th>
<th>Next(iteration)</th>
<th>remove</th>
</tr>

<tr>
<td>Array List</td>
<td>O(1)</td>
<td>O(n) but Ω(1)</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(n)</td>
</tr>

<tr>
<td>Linked List</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(n)</td>
</tr>
</table>

<hr>
<a href="README.md">&lt;&lt; README </a>
<hr>
