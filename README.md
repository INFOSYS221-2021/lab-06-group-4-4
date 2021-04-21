### Lab 6.8
#### Members: Andrew Bolton, Daniyal Mahmood, Nick Challinor, Rhea Rao

##### 1: What is the type of collection used in the exercise?
- 5.6.1
    - Queue
- 5.6.2
    - List

##### 2: What are the different ways of iterating through a collection?
- 5.6.1
    - Cannot Iterate through Queues
- 5.6.2
    - For Loops
    - While Loops

##### 3: How do you find out the size of a collection?
- 5.6.1
    - queue.qsize()
- 5.6.2
    - .length

##### 4: How do you add an item to a collection? What happens if you try to add an item to a collection that is already full?
- In java we use the .add() method to add members, the same goes for javascript, where add = .push() and python which is .ammend(). Essentially they all so the same thing, just diffefent syntax.
- In 5.6.1 we can see in the java example they used the add and remove method below:
- queue.add(item);

##### 5: How do you remove an item to a collection? What happens if you try to remove an item that does not exist in the collection?
- In java we use the .remove() method to remove members. In javascript it is .unshift() for remove and in python it is .remove() also.
- In 5.6.1 we can see in the java example they used the add and remove method below:
- queue.remove();

##### 6: Change the implementation of a FIFO queue to a LIFO queue in 5.6.1.
- // remove from the queue and make sure LIFO
    lifoDestack(miqVoucherQ);
    System.out.println(miqVoucherQ);
