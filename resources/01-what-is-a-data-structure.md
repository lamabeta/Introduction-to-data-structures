# What Is A Data Structure ?
The `data Structures` **provide** a systematic way to **structure** and **manage** `data` such as numbers, text, or objects. 

## Concept
Data structure is a 
>way of **organizing** and **storing** `data` in a computer's `memory`.

Think of `data structures` as different types of **containers** that **hold** and **organize** data in a **specific format**, They **allow** for **efficient storage**, **retrieval**, and **manipulation** of `information`.  
and they **help optimize** the **performance** and **efficiency** of `algorithms` **by providing** ways to **store** and **access** `data` in a structured manner. Depending on how you choose to organize your data, your program may run significantly faster or slower. 

## Example
Imagine you have a collection of words , and you want to store each of them :
```java
public class Words {
    public static void main(String[] args) {
        String firstWord = "Good ";
        String secondWord = "morning";
        System.out.println(firstWord + secondWord);
    }
}
```
```java
public class WordList {
    public static void main(String[] args) {
        String[]wordList ={"Good ","morning"};
        System.out.println(wordList[0] + wordList[1]);
    }
}
```
In this scenario, the `data` itself remains **constant**, while the `method` of storing the data has **changed**.
