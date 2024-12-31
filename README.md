# Elixir List Modification Bug

This repository demonstrates an uncommon error in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  The issue stems from the immutability of Elixir data structures.  Attempting to modify the list within the `Enum.each` loop does not affect the original list, resulting in an unexpected outcome.

The `bug.ex` file showcases the problem. The `bugSolution.ex` provides a corrected approach using `Enum.filter` or `Enum.reduce` for modifying a list while iterating. 

This example is useful for understanding the nuances of Elixir's immutability and how to work with lists effectively.