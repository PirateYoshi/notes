# Object Oriented Programming

### Class
A class is an object template. It defines the properties and methods for the object.

```csharp
public class Customer
{
  // Properties
  // The properties define the data managed by the
  // class
  public int CustomerId { get; set; }

  public string EmailAddress { get; set; }

  public string FirstName { get; set; }

  public string LastName { get; set; }

  // Methods
  // The methods determine how the data is managed
  // by the class
  public bool Validate()
  {
    ...
  }
}
```

### Object
An object (AKA: class instance) is an entity based on a class.

Objects can be created using the `new` keyword.

When an class instance is assigned to a variable, a reference is stored instead of the class instance.

Using the reference, the class instance can be accessed.

```cSharp
// Creating a Customer object
Customer cust1 = new Customer();

cust1.FirstName = "John";

// The reference is duplicated instead of the class
// instance. Now both `cust1` and `cust2`, reference
// the same class instance.
Customer cust2 = cust1;

cust2.FirstName = "Jane";

cust1.FirstName === "Jane"; //true
```

### Principles
**Abstraction:** the most important or essential aspects of something while ignoring the less important details. Abstraction is dependent on perspective - what is important in one context may not be in another. We model our problem domain using abstractions.

**Encapsulation:** physical localization of features into a single blackbox abstraction that hides their implementation behind a public interface. "Information hiding" is a corollary concept that indicates data fields are hidden from the user but the functionalities as implemented through functions are exposed.

**Inheritance:** organization of abstractions according to some order (e.g. complexity, responsibility, etc.).

**Polymorphism:** substitute variables or objects of one type with variables or objects of another type. Polymorphism gives us the ability to switch components without loss of functionality.

### Planning

#### Example of a Class
- **Class:** Course
- **Properties:** Name, Location, Days Offered, Credit Hours, Professor
- **Methods:** Add Student, Delete Student, Get Course Roster, Determine If Full

#### 1. Identifying Classes
When determining classes, start with nouns. Look at each noun, in the requirements, and determine if it should be defined as a class.

There may be several nouns per requirement.




#### 2. Separating Responsibilities

#### 3. Establishing Relationships

#### 4. Leveraging Reuse
