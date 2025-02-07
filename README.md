# Ruby Bug: Unexpected Attribute Modification

This repository demonstrates a subtle bug in Ruby related to the unexpected behavior when trying to modify an object's attribute through a getter method. The code attempts to change the value of an object's attribute using the getter method, but this does not work as intended.

The `bug.rb` file contains the buggy code, and `bugSolution.rb` provides a corrected version. The issue and its solution are explained in the file descriptions.

## How to Reproduce

1. Clone the repository.
2. Navigate to the directory.
3. Run `ruby bug.rb` to see the unexpected behavior.
4. Run `ruby bugSolution.rb` to see the correct behavior.

## Solution

The solution involves creating a `setter` method to explicitly modify the object's attribute. This provides a clear and expected way to update the value.