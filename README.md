# algorithms
## maintained by adam specker

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

### Pseudocode a function that will read a given set of numbers then calculate and return the average
* for loop to rotate through numbers in array
* at each step of the loop at the number at index i to var sum
* after loop is done, divide sum by array.length
* output the result of previous calculation
```
        var numArray = [];
        var sumAvg =  function (numArray){
            var sum = 0;
            var arrLength = numArray.length;
            for (var i =0; i<arrLength;i++){
                sum += numArray[i];
            }
            var avg = sum/arrLength;
        $(".printHere").append("The average of "+numArray+" is "+avg+". <br>");
        }
        sumAvg ([3,6,7,9,5,2]);
```

### Write a function that takes in a string and outputs the string in reverse
```
        $("#add-string").on("click", function() {
            event.preventDefault();
            var string = $("#string-input").val().trim();
            var stringArr = string.split("");
            console.log(stringArr);
            var reverseArr = [];
            for (var i=stringArr.length-1;i>=0;i--){
                reverseArr.push(stringArr[i]);
            }
            console.log(reverseArr);
            reverseString = reverseArr.join("");
            $("#string-output").text(reverseString);
      });
 ```
