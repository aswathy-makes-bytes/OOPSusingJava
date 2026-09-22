# OOPSusingJava
Custom Exception in Java — InvalidBMIException

A small Java program that demonstrates custom exception handling by validating a calculated BMI (Body Mass Index) value. If the BMI works out to zero or negative, a custom checked exception, InvalidBMIException, is thrown instead of returning a meaningless result.

📌 Objective

To create a custom checked exception InvalidBMIException and throw it whenever the calculated BMI value is zero or negative, demonstrating how Java's exception handling mechanism can be extended to enforce domain-specific validation rules.

⚙️ Algorithm

🧩Define class InvalidBMIException extending Exception with a constructor that takes a message.

🧩Define a method calculateBMI(weight, height) that declares throws InvalidBMIException.

🧩Inside the method, compute BMI = weight / (height * height).

🧩Check if BMI <= 0; if true, throw new InvalidBMIException("...").

🧩Otherwise, return the valid BMI value.

🧩In main(), call calculateBMI() inside a try block.

🧩Catch InvalidBMIException in the catch block and print the error message; otherwise print the BMI.

📚 Reference

Balagurusamy, E. Object Oriented Programming with Java, McGraw Hill — Chapter on Exception Handling.
Oracle Java Documentation — "Creating Exception Classes"
