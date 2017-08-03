### Types of Doubles

| Type  | Characteristics | Use |
|-------|-----------------|-----|
| Dummy | the method called returns null | use when you know the method won't get called at all, you just need an instance of the right type |
| Stub  | the method blindly returns the correct type value, but doesn't actually do anything to get it | when this method will be called but you're not testing it |
| Spy   | the method records in a variable on the spy when it has been called / other info, this information is later directly accessed | checking that a method was called to / other details about the call |
| Mock  | same as spy, except that instead of checking the variable directly, you use the Mock's verify method | same as spy but when you want it to be more semantic |
| Fake | has actual business behaviour but simplified (e.g. login only one user) | when you want to get more complicated |
