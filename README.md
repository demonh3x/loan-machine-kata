Loan Machine Kata
====================
A kata to practice the interaction with the "real world"

Description:
--------------------
There is a machine that holds physical objects.
The machine can lend those objects to people.

Each object holder consists of two parts:
- A one-way locking latch mechanism:
  - If it is opened, when an object is inserted, the lock closes and locks the object automatically.
  - Can open the lock to release the object.
  - Detects if it is in closed or open position.
- An object identifier
  - Detects the holding object's id.

The client wants the machine to:
- Know where each object is at every moment. If the object is at an object holder or if some person has it.
- Able to lend an object to a person.
- Know how much time a person had an object.

Quite simple, isn't it?

Modifiers:
--------------------
- The object identifier has some delay detecting the objects.
  For example: it detects the object 1 second after it has been placed in the identifier range.
- The object identifier may stop detecting the objects temporarily.
- The one-way locking latch mechanism can be picked.
- The one-way locking latch mechanism may not open when you tell it to.
  For example: it is under pressure because of the object is in a bad position.
- The client also wants the machine to detect the malfunctions to later notify them to a technician.
