# 12 c Queue Using Linked List – Display, Peek, and Pop

## Aim

To write a Python program to insert elements into a queue, display all elements, and then display the queue after deleting the first element (front).


## Algorithm

1. Start
2. Create an empty queue using deque
3. Insert elements using append()
4. Display all inserted elements
5. Remove the first element using popleft()
6. Display the queue after deletion
7. Stop


## Program

```python
#Reg.NO:212222040120
#Name:PRASANNA R
queue = []

queue.append('a')
queue.append('b')
queue.append('c')

print('Queue after elements are inserted:')
print(queue)

print('Deleting the first element inserted:')
print(queue.pop(0))

print("Queue after the first elements is deleted:")
print(queue)
```

## OUTPUT
![LAB12 DAY3](https://github.com/user-attachments/assets/64ea3acd-fee1-46d6-a790-9a72f7ecc617)

## RESULT
Thus, the given program is implemented and executed successfully .
