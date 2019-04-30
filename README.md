# online-training-on-class-interface-and-oop


Goal of software engineering: 
We want to reduce the impact of change in our software.

open closed principle (OCP) -
Software entities should be open for extension but closed for modification.

Not to apply this principle everywhere but there are areas in our system where we see there is potential for change like in a user notification module (send notification via mail, text or real time while users are online)

How to implement OCP using an interface:

Think of abstraction first, after the video encoder done encoding, we need to send out a notification. class vidio encoder does not know how the notification was implemented. So in this class we need to think of a notification channel as an abstraction and that's where an interface comes in. Because the interface is just a role, a contract.

e.g. Chef in a restaurant, John is the chef or Mary is if John is off. John or Mary will be the concrete class and the role Chef will be the interface.

** further study on the same topic

event and delegate

Unit Test:
- isolate the class using an interface; arrange some preconditions 
- act on a method
- do assertions