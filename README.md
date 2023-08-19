### Analog Clock

This is an analog clock that shows the time in hours, minutes, and seconds.

### Instructions

To use the clock, simply open the index.html file in a web browser. The clock will automatically update to the current time.

### Code Explanation

The clock is made up of three main parts: the spikes, the minutes, and the hour. The spikes are the small lines that surround the clock face. They are created using the `<i>` element and the `.spike` class. The minutes are the larger lines that surround the clock face. They are created using the `<div>` element and the `.minutes` class. The hour is the number in the center of the clock face. It is created using the `<div>` element and the `.hour` class.

The clock is animated using the `setInterval()` function. This function calls the `getTime()` function every 1000 milliseconds (1 second). The `getTime()` function gets the current time from the `Date()` object and updates the clock accordingly.

### Conclusion

This analog clock is a simple but effective way to show the time. It is easy to use and can be customised to fit any need.
