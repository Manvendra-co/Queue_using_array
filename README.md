# Queue_using_array
A queue in C is basically a linear data structure to store and manipulate the data elements. It follows the order of First In First Out (FIFO). In queues, the first element entered into the array is the first element to be removed from the array. A queue is open at both ends. One end is provided for the insertion of data and the other end for the deletion of data.
A real-world example of queue can be a single-lane one-way road, where the vehicle enters first, exits first. More real-world examples can be seen as queues at the ticket windows and bus-stops.

# Operations Associated with a Queue in C:
enqueue(): It inserts elements to the end of the queue.
dequeue(): Removes the element from the frontal side of the queue.
Front: Pointer element responsible for fetching the first element from the queue
Rear: Pointer element responsible for fetching the last element from the queue

# Applications of Queue Data Structure
• CPU Scheduling

• Disk Scheduling

• Asynchronous data transfer between processors such as File IO, etc.

• Breadth-First Search Algorithm (BFS)

# Algorithm
Step 1: IF REAR = MAX - 1
Write OVERFLOW
Go to step
[END OF IF]

Step 2: IF FRONT = -1 and REAR = -1
SET FRONT = REAR = 0
ELSE
SET REAR = REAR + 1
[END OF IF]

Step 3: Set QUEUE[REAR] = NUM

Step 4: EXIT

# Output
![image](https://user-images.githubusercontent.com/76811184/234380330-3a2c7d53-fc51-42d6-bf5d-4f5c0acd255b.png)

