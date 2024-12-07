# Scala Bug: Silent Failure in Age Setter

This repository demonstrates a common error in Scala: improperly handling invalid input.  The code has a setter for age that throws an exception if the input is negative. However, the application does not handle this exception resulting in a crash rather than graceful error handling.  This example highlights the importance of robust error handling and the need to prevent the unexpected termination of the application.

## How to Reproduce

1. Clone this repository.
2. Compile and run `Main.scala`.
3. Observe the exception when a negative age is attempted.

## Solution

The solution is provided in a separate file.  It demonstrates the proper way to handle such cases, potentially using a `Try-Catch` or similar mechanisms for gracefully handling potential exceptions.