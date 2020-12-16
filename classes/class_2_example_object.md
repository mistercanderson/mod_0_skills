## Object That Might Exist in a Restaurant

An instance of the `BackOfHouse` class might be the `LineCook` object.

### Attributes of `LineCook` object:

1. `menuItems = ["calamari", "halibut", "chocolate cake"]`
1. `openTickets = [201, 202, 203]`
1. `closedTickets = [198, 199, 200]`
1. `isAngry = false`

### Methods of `LineCook` object:

1. `callOutNewItem[1]` (logs `"Order up! We need another halibut"` to the console)
1. `ringNewTicket` (adds `204` to the end of the `openTickets` array)
1. `completeTicket[2]` (removes `203` from `openTickets` array and adds that same value to the end of `closedTickets`)
1. `frustrateChef` (The threshold for `openTickets` was `1`, so now the value of `isAngry` gets changed to `true`. I think this should be an `if/else` statement)
