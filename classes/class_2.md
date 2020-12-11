## Class That Might Exist in a Restaurant

`BackOfHouse` class

### Attributes of `BackOfHouse` class:

1. `menuItem` (string)
1. `openTickets` (array of integers)
1. `closedTickets` (array of integers)
1. `isAngry` (boolean)

### Methods of `BackOfHouse` class:

1. `callItem` (logs `"Order up! We need a " + menuItem` to the console)
1. `ringNewTicket` (adds a new ticket number to the end of the `openTickets` array)
1. `completeTicket[]` (removes indexed value of `openTickets` and adds that same value to the end of `closedTickets`)
1. `frustrateChef` (Specifies a threshold for value of `openTickets` attribute. If this threshold is crossed, it changes the value of `isAngry` for all instances of `BackOfHouse` class to `true`. If the value goes below the specified threshold, it changes `isAngry` to `false`.)
