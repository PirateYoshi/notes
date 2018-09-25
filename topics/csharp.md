# C # #

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
