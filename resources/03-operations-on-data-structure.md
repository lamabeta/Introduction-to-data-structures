# Operations On Data Structure
**Operations** on `data structures` involve a **set of actions** that can be **performed to manipulate the data**.These operations include traversing, insertion, deletion, and more.
  Operations on data structures involve a set of actions that can be performed to manipulate the data.These operations include traversing, insertion, deletion, and more.
## Concept
The most important operations that we can perform on all types of data structures are: 
- Traversing:
>Visiting **each element** of the data structure to **perform specific operations** like searching or sorting.
- Insertion:
>The process of **adding elements** to the data structure at any location.
- Deletion:
>The process of **removing an element** from the data structure. 
- Searching:
>The process of **finding the location** of an element within the data structure.
- Sorting:
>The process of **arranging** the **data** structure in a specific order.
- Merging:
>When two data structures, A and B of size M and N respectively, of **similar type of elements**, **joined to produce the third data structure**, C of **size (M+N)**, then this process is called merging.

## Example
- Adding an element to an array. 
```java
    public static void main(String[] args) {
        int[] array = {1, 2, 3, 4, 5};
        int newElement = 6;
        
        // Creating a new array with increased length
        int[] newArray = new int[array.length + 1];
        
        // Copying elements from the original array to the new array
        for (int i = 0; i < array.length; i++) {
            newArray[i] = array[i];
        }
        
        // Adding the new element at the end of the new array
        newArray[newArray.length - 1] = newElement;
    }
```
- Sorting elements in an array using the sort() function.
```java
    public static void main(String[] args) {
        int[] array = {5, 2, 9, 1, 4};
        
        Arrays.sort(array);
    }
```
