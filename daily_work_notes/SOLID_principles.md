Robert C. Martin

To manage and maintain:

# Single Responsibility
A class should have only a single responsibility.
A C# interface should serve only one purpose.

# Open-Closed Principle
A class should be open for extension but closed for modification.
By reusing existing code, we can prevent the introduction of new bugs.

# Liskov's substitution Principle
A subclass should behave in such a way that it will not cause problems when used in place of its superclass.
I should not turn immutable code into mutable code.
A circle object should not inherit from a rectangle object.


### Best practices
Always create a baseline for refactoring.
Refactor in small chunks, commit, and run tests.
Use a separate branch for major refactoring.
Long methods should be broken into smaller steps.
Avoid nested loops.
Simplify math: multiply instead of dividing when possible.
The naming convention should be maintained systematically.
Document the code.
All functions should be separated and imported as needed.