# Towers-of-Hanoi-Stack-Implementation

Tower of Hanoi is a classic mathematical puzzle game that tests players' problem-solving skills and patience. The game consists of three rods and a number of disks of different sizes, which can slide onto any rod. At the start of the game, all the disks are stacked in ascending order of size on one rod, with the smallest disk at the top and the largest at the bottom.

## How to Install

1. **Clone the repository:**
    ```bash
    git clone https://github.com/RECodeVault/Towers-of-Hanoi-Stack-Implementation-.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Towers-of-Hanoi-Stack-Implementation-
    ```

3. **Start the application:**
    ```bash
    python main.py
    ```

## Rules
1. Only one disk can be moved at a time.
2. Each move consists of taking the top disk from one stack and placing it onto another stack.
3. No disk may be placed on top of a smaller disk.
4. Get all disks from the left-most stack to the right-most stack.

### Example:
![Towers of Hanoi](https://1.bp.blogspot.com/-4R0ZfbGOspM/XVaYRFnk16I/AAAAAAAAIP8/xFG876BVNi4VZiOy8DCH0dZoBw2ecZhSgCLcBGAs/w1600/towerofhanoi.png)

## Extra information about the stack implementation:

### What is a stack? and why use a Linked list for this?:
A stack is a linear data structure that follows the Last In, First Out (LIFO) principle, where elements are added and removed from one end known as the top of the stack. The linked list data structure allows dynamic memory allocation and efficient insertion and deletion operations, making it suitable for implementing a stack.

## Implementation details:

### Node Class: 

**set_next_node(self, link_node):** Sets the reference to the next node in the linked list.

**get_next_node(self):** Retrieves the reference to the next node in the linked list.

**get_value(self):** Retrieves the value stored in the current node.

### Stack Class: 

**push(self, value):** Adds a new element with the given value to the top of the stack if there is space available.

**pop(self):** Removes and returns the element from the top of the stack if the stack is not empty.

**peek(self):** Returns the value of the element at the top of the stack without removing it if the stack is not empty.

**has_space(self):** Checks if there is space available in the stack to add more elements.

**is_empty(self):** Checks if the stack is empty.

**get_size(self):** Returns the current size of the stack.

**get_name(self):** Returns the name of the stack.

**print_items(self):** Prints the elements of the stack from top to bottom.
