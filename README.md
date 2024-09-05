# questions
Q1: What happens if you do not define a constructor in the Room class? What does the compiler do in this case?

A: If no constructor is defined in the Room class, the compiler automatically generates a default constructor. This default constructor does nothing beyond basic memory allocation; the member variables (length and breadth) could contain garbage values. This is why it is essential to define a constructor if you want to initialize variables with specific values.

Q2: 
