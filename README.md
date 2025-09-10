# 🌀 Queue using Linked List - Insert, Display, and Delete

## 🎯 Aim

To write a Python program that:
- Inserts elements into a queue.
- Displays all inserted elements.
- Deletes the first element.
- Displays the updated queue after deletion.

---

## 🧠 Algorithm

1. **Create a Queue**:
   - Initialize an empty list named `queue`.

2. **Insert Elements**:
   - Use the `append()` method to insert elements `'a'`, `'b'`, and `'c'` into the queue.

3. **Display Initial Queue**:
   - Print the message `"Queue after elements are inserted:"` followed by the queue contents.

4. **Delete First Element**:
   - Use `pop(0)` to remove the first inserted element (FIFO - First In First Out).
   - Print the message `"Deleting the first element inserted:"` and the element removed.

5. **Display Updated Queue**:
   - Print the message `"Queue after the first element is deleted:"` followed by the updated queue contents.

---

## Program
Add Code Here
```
  queue = []
  queue.append('a')
  queue.append('b')
  queue.append('c')
  print('Queue after elements are inserted:')
  print(queue)
  print('Deleting the first element inserted:')
  print(queue.pop(0))
  print('Queue after the first elements is deleted:')
  print(queue)
```
## Output
![image](https://github.com/user-attachments/assets/fb45b2c2-2364-43d6-8863-ecd4f082f597)

## Result
Thus, the program has been execueted successfully.


# 🔁 Queue using Linked List: Display Front and Rear Elements of a Queue

## 🎯 Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

## 🧠 Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
Add code here
```
  queue = []
  queue.append('a')
  queue.append('b')
  queue.append('c')
  queue.append('d')
  print('Initial Queue: ' + str(queue))
  front=queue[0]
  rear=queue[3]
  print("\nElement at the front of the queue is..... ", front)
  print("\nElement at the rear of the queue is .....", rear)
```
## Output
![image](https://github.com/user-attachments/assets/b883a7cf-c5d7-44e7-864b-a55a2bc43397)

## Result
Thus, the program has been execueted successfully.


# # 📚 Stack using Linked List: Check and Display Whether the Stack is Full or Not

This Python program demonstrates how to check if a stack (using `LifoQueue` from the `queue` module) is full or not. It uses the `full()` method to determine the stack's status and then displays the appropriate message.

## 🎯 Aim

To write a Python program that:
- Creates a stack with a fixed size.
- Adds elements to the stack.
- Checks if the stack is full.
- Displays a message indicating whether the stack is full or not.

## 🧠 Algorithm

1. **Import the LifoQueue class**:
   - Import `LifoQueue` from the `queue` module to create the stack.

2. **Create a Stack**:
   - Instantiate a `LifoQueue` with a maximum size (e.g., 4).

3. **Add Elements to the Stack**:
   - Add elements (e.g., 'a', 'b', and 'c') to the stack using the `put()` method.

4. **Check if the Stack is Full**:
   - Use the `full()` method of `LifoQueue` to check if the stack has reached its maximum capacity.

5. **Display the Status**:
   - Print "Stack is full" if the stack is full.
   - Otherwise, print "Stack is not full".

## 📝 Program
Add Code here
```
  from queue import LifoQueue
  stack = LifoQueue(maxsize=4)
  stack.put('a')
  stack.put('b')
  stack.put('c')
  ifstack.full():
  print("Stack isfull")
  else:
  print("Stack is not full")
```
## Sample Input & Output
![image](https://github.com/user-attachments/assets/461c38a5-f0cd-4873-acdb-9665923cc938)

## Result
Thus, the program has been execueted successfully.


# 📚 Stack using Linked List: Check and Print the Index Value of the Elements Stored in the Stack

This Python program demonstrates how to:
1. Create a stack using a list.
2. Add elements to the stack.
3. Print the index and corresponding value of each element in the stack.

## 🎯 Aim

To write a Python program that:
- Creates a stack using a list.
- Adds elements to the stack.
- Prints the index values of the stack elements along with the corresponding values.

## 🧠 Algorithm

1. **Create an Empty Stack**:
   - Initialize an empty list `stack` to store elements.

2. **Add Elements to the Stack**:
   - Append elements (e.g., 'a', 'b', 'c') to the stack using the `append()` method.

3. **Print the Initial Stack**:
   - Print the contents of the stack with a message "Initial stack: ".

4. **Iterate through the Stack**:
   - Use a `for` loop with `range()` to iterate through the stack.
   - Print the index value and corresponding element at that index.

5. **Print Index and Value**:
   - For each element in the stack, print the index and the value at that index.

## 📝 Program
Add Code here
```
  stack = []
  stack.append('a')
  stack.append('b')
  stack.append('c')
  print('Initial stack: ' + str(stack))
  for i in range(len(stack)):
     print(i, end=" ")
     print(stack[i])
```
## Sample Input & Output
![image](https://github.com/user-attachments/assets/23981b48-1e1e-4d96-9de2-39f0ba0857ae)

## Result
Thus, the program has been execueted successfully.


# EX.NO:12(E) Stack using Linked List: Stack Implementation (Top Element Display)

##  Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.



##  Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**



##  Program
```
stack = [] 
stack.append('a') 
stack.append('b') 
stack.append('c') 
print ('Initial stack: ' + str(stack))
for i in range(len(stack)): 
    print(i,stack[i])
```

## Output
![image](https://github.com/user-attachments/assets/18bd9505-dc7f-4e3b-93de-47bcb509d6fc)

## Result
Thus, the given program is implemented and executed successfully. 

