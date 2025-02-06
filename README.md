# Uncommon HTML Bug: Incorrect getElementById usage

This repository demonstrates a subtle yet easily missed bug in HTML/JavaScript related to using `getElementById`.  The incorrect usage can lead to unexpected behavior, especially in more complex code.

## Bug Description
The `getElementById` method does not require a '#' prefix when retrieving an element by its ID.  Including the '#' prefix will cause the method to return `null`, leading to potential errors if the code does not properly handle this case.

## Bug Solution
The correct usage is simply to pass the ID string as an argument to the `getElementById` method without a '#' prefix.