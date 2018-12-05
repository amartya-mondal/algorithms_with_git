# Circular Queue

This program implements the algorithm for circular queue in a menu driven way.


### Input Format

- User needs to enter choice from the menu provided and thereby enter the values required.


### Output Format

A message predicting the work that the selected option has done.

### Sample Input

```
------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit

Enter choice...1
Enter ITEM for insertion34

Enter choice...3

Enter choice...1
Enter ITEM for insertion45

Enter choice...3

Enter choice...2

Enter choice...3

Enter choice...1
Enter ITEM for insertion34

Enter choice...3

Enter choice...4

```

### Sample Output

```
------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit
Your Circular Queue is: 


Circular Queue is:
 (Front shown as ->> and Rear as <<- and Free Spase as -)

->> 34 <<-


------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit

Circular Queue is:
 (Front shown as ->> and Rear as <<- and Free Spase as -)

->> 34 <<-


------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit
Your Circular Queue is: 


Circular Queue is:
 (Front shown as ->> and Rear as <<- and Free Spase as -)

->> 34 <- 45 <<-


------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit

Circular Queue is:
 (Front shown as ->> and Rear as <<- and Free Spase as -)

->> 34 <- 45 <<-


------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit

Element delete is:  34

Circular Queue is:
 (Front shown as ->> and Rear as <<- and Free Spase as -)

* ->> 45 <<-


------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit

Circular Queue is:
 (Front shown as ->> and Rear as <<- and Free Spase as -)

* ->> 45 <<-


------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit
Your Circular Queue is: 


Circular Queue is:
 (Front shown as ->> and Rear as <<- and Free Spase as -)

* ->> 45 <- 34 <<-


------------------ Circular Queue Menu---------------


1->Insert
2->Delete
3->Display
4->Exit

Circular Queue is:
 (Front shown as ->> and Rear as <<- and Free Spase as -)

* ->> 45 <- 34 <<-


```

### Implemented in:

- [Python](circularQueue.ipynb)
