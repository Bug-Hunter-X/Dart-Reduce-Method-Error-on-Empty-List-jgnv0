# Dart Reduce Method Error on Empty List

This repository demonstrates an uncommon error in Dart when using the `reduce` method with an empty list. The `reduce` method requires at least one element in the list; otherwise, it throws a `StateError`. The solution shows how to handle this scenario by adding a check for an empty list before using `reduce`.

## Bug
The `bug.dart` file contains code that attempts to use `reduce` on an empty list, resulting in a `StateError`.

## Solution
The `bugSolution.dart` file shows a solution that checks if the list is empty before applying the `reduce` method. If the list is empty, it returns a default value (0 in this case).