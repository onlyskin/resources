Testing

Dummy - method returns null, for when you know the method won’t actually be used
Stub - returns the correct value type but doesn’t actually do any of the normal things
Spy - implements the method and records if it’s been called/other info which is directly accessed e.g. checking the variable ‘x was called’ which is set in the spy’s x method
Mock - like a spy, except you don’t check the variable you just check a more semantic ‘verify’ method
Fake - has actual business behaviour but simplified, e.g. might login only ‘Sam’, can get very complicatedo

| Type  | Characteristics | Use |   |
|-------|-----------------|-----|---|
| Dummy |                 |     |   |
| Stub  |                 |     |   |
| Spy   |                 |     |   |
| Mock  |                 | | |
| Fake | | | |
