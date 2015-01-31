Loan Machine Kata
====================
A kata to practice the interaction with the "real world"

Description:
--------------------
There is a machine that holds physical objects.
The machine can lend those objects to people.

Each object holder consists of two parts:
- A one-way locking latch mechanism:
  - When an object is inserted, locks the object automatically.
  - Can open the lock to release the object.
- An object identifier
  - Detects the holding object's id.

You have to interact with the machine to:
- Detect when an object is received.
- Lend an object.

Quite simple, isn't it?

Modifiers:
--------------------
- The object identifier has some delay detecting the objects.
  For example: it detects the object 1 second after it has been placed in the identifier range.
- The one-way locking latch mechanism can be picked.
- The one-way locking latch mechanism may not open when you tell it to.
  For example: it is under pressure because of the object is in a bad position.
