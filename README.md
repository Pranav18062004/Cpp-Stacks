# Stack Data Structure

A stack is a fundamental data structure in computer science that follows the Last-In-First-Out (LIFO) principle. This means that the most recently added item is the first one to be removed. Stacks can be visualized as a collection of elements arranged in a linear structure, with two primary operations: **push** and **pop**. The push operation adds an element to the top of the stack, and the pop operation removes the top element.

## Characteristics of a Stack

1. **LIFO Principle**: The last element added to the stack is the first to be removed.

2. **Operations**:
    - **Push**: Adds an element to the top of the stack.
    - **Pop**: Removes the top element from the stack.

3. **Peek**: Examine the top element without removing it from the stack.

4. **Empty Stack**: A stack can be empty, indicating it contains no elements.

5. **Fixed or Dynamic Size**: Stacks can have a fixed size or a dynamic size.

## Implementing a Stack

In C++, you can implement a stack using various data structures like arrays or linked lists. A basic approach to implement a stack involves using an array and managing the stack's size manually. Here's a brief outline of the steps:

1. **Declare an Array**: Create an array to store the stack's elements.

2. **Top Pointer**: Maintain a pointer (an integer) that represents the top of the stack. Initialize it to -1 for an empty stack.

3. **Push Operation**: To push an element onto the stack, increment the top pointer and store the element in the array at that index.

4. **Pop Operation**: To pop an element from the stack, access the element at the top index and decrement the top pointer.

5. **Peek Operation**: To peek at the top element, simply access the element at the top index without changing the top pointer.

6. **Check for Empty Stack**: Ensure that you handle cases where the stack is empty (top pointer is -1) before popping or peeking.

7. **Dynamic Sizing**: If you want a dynamic-sized stack, consider resizing the array when it becomes full or using a linked list to avoid size limitations.

Remember that this is a basic outline, and you may need to add error handling and other features depending on your specific use case. In practice, C++ provides a more convenient way to work with stacks using the Standard Template Library (STL) stack container, as demonstrated in the previous code example in the README.
