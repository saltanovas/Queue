# Queue Data Structure

<p>A Queue is a linear structure which follows a particular order in which the operations are performed. The order is First In First Out (FIFO).</p>


```c 
struct Queue* create() // creates an empty queue with size = 0
```
```c 
int is_empty(struct Queue *x) // returns 1 if the queue is empty, else 0
```
```c 
int is_full(struct Queue *x) // returns 1 if the queue is empty, else 0
```
```c 
void enqueue(struct Queue *x, int value) // adds an item to the queue. If the queue is full, appropriate message is printed out
```
```c 
void dequeue(struct Queue *x) // removes an item from the queue. If the queue is empty, safely returns from the procedure
```
```c 
int first_element(struct Queue *x) // returns the first element from the queue. If the queue is empty, returns 0
```
```c 
int amount_of_data(struct Queue *x) // returns the number of elements are stored in the queue
```
```c 
void delete(struct Queue *x) // safely deletes created queue
```
```c 
void output_queue(struct Queue *x) // prints out the queue. If the queue is empty, appropriate message is printed out
```
