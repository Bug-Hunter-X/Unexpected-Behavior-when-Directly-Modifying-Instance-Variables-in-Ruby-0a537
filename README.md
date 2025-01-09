# Unexpected Behavior when Directly Modifying Instance Variables in Ruby

This repository demonstrates an uncommon bug in Ruby related to the way instance variables are handled.  Direct modification of an instance variable from outside its defining class will not change the variable's value unless a setter method is explicitly provided.

The `bug.rb` file shows the problematic code, while `bugSolution.rb` demonstrates how to correctly modify instance variables using setter methods.

This is a subtle error that can be easily overlooked.  Understanding the implications of this behavior is crucial for writing robust and predictable Ruby code.
