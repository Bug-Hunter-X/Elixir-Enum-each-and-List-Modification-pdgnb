# Elixir Enum.each and List Modification

This example demonstrates a common mistake when using `Enum.each` in Elixir to modify a list.  The code attempts to remove the element `3` from the list, but due to Elixir's immutability, it fails to alter the original list. The solution shows how to correctly handle this scenario using other functional approaches.