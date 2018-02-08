# algorithms
## maintained by adam specker
## last updated 2/5

### Farmer, fox, goose, bag of beans 
* Farmer takes goose across the river S: F B   E: G
* Farmer goes back to start alone  S: F B   E: G
* Farmer takes the fox across the river  S: B   E: G
* Farmer takes the goose back across with him   S: B   E: F
* farmer takes beans and leaves the goose on the original side S: G   E: F
* farmer takes beans across and leaves them with the fox S: G   E: F B
* farmer returns across the river  S: G   E: F B
* farmer takes the goose across the river, S:   E: F B G
* Everyone is happy and intact

### Write pseudocode how to print all multiples of 5 between 1 and 100
* create a for loop that invokes numbers 1 to 100 (or user input)
* use the remainder (%) function comparing i to 5
* if i % 5 is equal to zero
* output/add to array i
