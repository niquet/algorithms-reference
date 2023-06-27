# Elementary Data Structures
This file provides a comprehensive collection of elementary data structures implemented in the Python programming language. Whether you're a beginner learning the basics of data structures or an experienced developer looking for a quick reference, this README aims to be your go-to starting point.

## Structure
The repository is organized into sections, each representing a specific data structure. Within each section, you will find implementations of the data structure in the Python programming language. The code is well-commented and follows industry best practices to ensure readability and maintainability.

The following data structures are being discussed in this file:
- [Stacks](#stacks)
- [Queues](#queues)
- [Linked Lists](#linked-lists)
- [Pointers](#pointers)
- [Objects](#objects)
- [Rooted Trees](#rooted-trees)

## Stacks
A stack is a dynamic collection of items that follows a "last-in, first-out" (LIFO) policy [1]. In a stack, the element removed through the "DELETE" operation is predetermined [1]. Let's explore its properties and the operations involved:

Properties:
- Stacks operate on a LIFO policy, where the most recently inserted element is the one removed [1].
- The analogy of physical stacks, like spring-loaded plate stacks in cafeterias, helps explain the concept.
- The order in which plates are popped from the stack is the reverse of how they were pushed onto it.
- A stack can be implemented using an array, with the "S.top" attribute indicating the index of the most recent element.
- The stack consists of elements from S[1] (bottom) to S[S.top] (top).
- An empty stack is indicated when S.top is 0.
- A stack can be checked for emptiness using the "STACK-EMPTY" query operation.
- If attempting to pop an empty stack, it results in a stack underflow, considered an error.
- If S.top exceeds the maximum capacity of the stack (n), it leads to a stack overflow.

Operations (in a stack):
- PUSH: Adds an element to the top of the stack.
- POP: Removes the topmost element from the stack.

[1] Reference: (IEEE)

## Reference
[1] T. H. Cormen, C. E. Leiserson, R. L. Rivest, and C. Stein, "Introduction to Algorithms," 3rd ed. Cambridge, MA: MIT Press, 2009, pp. 232-235.

[2] T. H. Cormen, C. E. Leiserson, R. L. Rivest, and C. Stein, "Introduction to Algorithms," 3rd ed. Cambridge, MA: MIT Press, 2009, pp. 236-240.

