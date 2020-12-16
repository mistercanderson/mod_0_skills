## Object That Might Exist in a Restaurant

An instance of the `FrontOfHouse` class might be the `Server` object.

### Attributes of `Server` object:

1. `name = "Kelly"`
1. `activeParties = ["Johnson", "Smith", "Anderson"]`
1. `isFriendly = true`
1. `totalTips = 42.75`

### Methods of `Server` object:

1. `greetGuest` (logs `"Hi, I'm Kelly"` to the console)
1. `addNewParty("McDouglas")` (returns updated array `["Johnson", "Smith", "Anderson", "McDouglas"]`)
1. `spillDrink` (`isFriendly = false`)
1. `closeParty[0]` (`totalTips = 62.75` and the array of the `activeParties` is now `["Smith", "Anderson", "McDouglas"]`)
