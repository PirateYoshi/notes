# Object Oriented Programming

### Principles
**Abstraction:**
<br>the most important or essential aspects of something while ignoring the less important details. Abstraction is dependent on perspective - what is important in one context may not be in another. We model our problem domain using abstractions.

**Encapsulation:**
<br>The hiding of implemented features/information behind a private access level. However, implemented functionality is exposed through public functions.

*An example of this would be allowing the private property `FirstName` to be accessed via the public method of `getFirstName()`.*

**Inheritance:**
<br>organization of abstractions according to some order (e.g. complexity, responsibility, etc.).

**Polymorphism:**
<br>substitute variables or objects of one type with variables or objects of another type. Polymorphism gives us the ability to switch components without loss of functionality.

### Planning

#### Example of a Class
- **Class:** Course
- **Properties:** Name, Location, Days Offered, Credit Hours, Professor
- **Methods:** Add Student, Delete Student, Get Course Roster, Determine If Full

#### 1. Identifying Classes
When determining classes, start with nouns. Look at each noun, in the requirements, and determine if it should be defined as a class.

There may be several nouns per requirement.

**Building the class**
<br>It is beneficial to use Test Driven Programming (TDD) concepts when building your classes:
1. Before writing functional code, write a test that fails.
* Run the test.
* Code the functionality to pass the test
* Run the test again.

Steps 3 and 4 should be repeated until the class passes the current and all previous tests.


#### 2. Separating Responsibilities
*Principle of separation of concerns*
<br>When you class has too much responsibility, it can become difficult to maintain.

**Minimizing Coupling**
<br>The degree classes are dependent on each other.

It is easier to maintain and update a class when there are less dependencies. Try to separate them out.

**Maximizing Cohesion**

**Simplifying Maintenance**

**Improving Testability**


#### 3. Establishing Relationships

#### 4. Leveraging Reuse
