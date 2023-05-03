Download Link: https://assignmentchef.com/product/solved-cs2028-lab-3-classes-multi-file-programs-and-operator-overloading
<br>
The objective of this Lab is to create a class including constructors, using correct class file separation and implement operator overloading.

<strong>Task 1:  </strong>Design Class (.h file)

<ol>

 <li>Create a new project. You can name this whatever you like.</li>

 <li>Design a class to allow calculations on complex numbers (numbers with a real and an imaginary component). A refresher can be found at <a href="https://en.wikipedia.org/wiki/Complex_number">https://en.wikipedia.org/wiki/Complex_number</a>.

  <ol>

   <li>Declare a default constructor and an overload of a constructor that supports passing each of the attributes in Cartesian complex plane form and polar complex plane form (total of 3 constructor versions).</li>

   <li>Make all attributes (variables) private.</li>

   <li>Declare getters and setters for all attributes as appropriate.</li>

   <li>Declare a print member function to print out the value using cout.</li>

  </ol></li>

 <li>Include in the submission your rationale for all members you have in your class.</li>

</ol>

<strong>Task 2:  </strong>Implement the Class

<ol>

 <li>Write the implementation code for the methods declared in Task 1. The definitions should be in a separate .cpp file.</li>

 <li>Include in the lab report any changes you needed to make to the class declaration (.h file).</li>

</ol>

<strong>Task 3:  </strong>Extend the class.

<ol>

 <li>Modify the class declaration and definition to overload the +, -, *, / and == operators to correctly perform those calculations.

  <ol>

   <li>The + and – operators should accept an input parameter of the same class type and return void. This operation should update the contents of that instance.</li>

   <li>The * and / operators should accept an input parameter of the same type as the private variables holding the x and y values. This will be a scaler multiplication/division.</li>

   <li>The == operator should accept an input parameter of the same class type and return a bool indicating if the value is equivalent.</li>

  </ol></li>

 <li>Modify the class declaration and definition to include a member function returning the r and another returning the angle of the value phi (φ) in polar complex plane.</li>

 <li>Include in the lab report any changes you needed to make to the class declaration beyond the new functions being defined in this task</li>

</ol>

<strong>Task 4:  </strong>Test the class.

<ol>

 <li>Create a program that tests the class.

  <ol>

   <li>Prompt the user for x and y values for the complex number.</li>

   <li>Prompt the user for the operation to perform.</li>

   <li>Prompt the user for the values for other class instance or scaler to be used in the calculation.</li>

   <li>Display the results.</li>

   <li>Ask the user if they wish to continue. If so, loop to step b.</li>

  </ol></li>

 <li>Use your test program to test all member functions and ensure the class is working correctly.</li>

 <li>Include in the lab report a screen shot(s) of the output of a test of all operator overload functions.</li>

</ol>