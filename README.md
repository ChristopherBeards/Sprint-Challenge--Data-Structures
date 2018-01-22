# Assessing your Data Structures Fu
* The purpose of this exercise is to get you used to being quizzed on _Interview Questions_ commonly asked about Data Structures and their implementation in the JavaScript Language.
* Answers to your written questions will be recorded in *Answers.md* 
* This is to be worked on alone but you can use outside resources. You can *reference* any old code you may have, and the React Documentation, however, please refrain from copying and pasting any of your answers. Try and understand the question and put your responses in your own words. Be as thorough as possible when explaining something. 
* **Just a friendly Reminder** Don't fret or get anxious about this, this is a no-pressure assessment that is only going to help guide you here in the near future. This is NOT a pass/fail situation. 

## Questions
1. What are the order of insertions/removals for the following data structures?
   - **Stack**
   #First In First Out
   - **Queue**
   #Last In First Out
2. What is the retreival time complexity for the following data structures?
   - **Linked List** 

   Linear O(n) // As the input size increases, the runtime increases.

   - **Hash Table** 

   Constant O(1) // As the input size increases the number of operations performed never changes.

   - **Binary Search Trees** 

   Logorithmic / O(log n) // With every operation performed, it cuts the input in-half.

2. What are some advantages to using a Hash Tables over an array in JavaScript?

Some advantages of using a Hash Table over an Array in JavaScript are search efficiency and possible improved data organization. If you want to locate something within an Array, you may have to search through the entire Array either forwards or backwards. This can be a lengthy process if there is a lot of data stored. A Hash Table works differently, by storing the exact location of the data. This works sort of like valet parking, where the vehicle receives a specific number attached to the drivers name. When you want to retrieve your car, all they have to do is go to the exact location associated with the vehicle. If no other cars are in said location, the answer is obvious, but if the location is a separate lot, it still cuts down on the amount of search time required to locate the vehicle. 

## Challenge
If you take a look at the hash-table.js file you'll notice that it has solution code in it. You'll also notice that if you run the tests, they all pass. Your job is to refactor this hash table solution to use **linked lists** for buckets instead of arrays. You're welcome to add another class to the helper file, following the pattern used with LimitedArray.