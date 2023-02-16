1. Define the current hour, properly display hours throughout the day

var currentHour
var blockHour
        // eventually use parseInt()

$('.time-block).each(function() {
    if(blockHour < currentHour) {

    } else if (blockHour === currentHour) {

    } else {

    }
})

2. Allow the user to save notes within individual timeblocks, have the data save to local storage, and utilize local storage each time the page loads to have persistent data

var value
var selectedHour

3. Display the current date in the header