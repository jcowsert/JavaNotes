# Java Notes

- Access Modifiers
    -Public
        -Class: Yes
        -Package: Yes
        -World: Yes
    -Protected
        -Class: Yes
        -Package: Yes
        -World: No
    -Private
        -Class: Yes
        -Package: No
        -World: No

- Encapsulation
    - Encapsulation is the bundling of related data and behaviors that operate on that data, usually with restricted access to internal, non-public data and behaviors.
        - Always use the most restrictive Access Modifier that you can. This will reduce the chance of important variables being changed and breaking your code.
-Constructor Overloading
    -We can provide multiple constructors for a given class in order to allow for different initialization scenarios. 
    -When providing multiple constructors, we must ensure that each has a different collection of arguments, as determined by the number, order, and type of the constructor arguments.

> The single responsibility principle states that every module or class should have responsibility over a single part of the functionality provided by the software, and that responsibility should be entirely encapsulated by the class.

-Getters and Setters
    -Are used to access private fields. 
``` Java
    public String getName() {
    return name;
}

public void setName(String aName) {
    name = aName;
}
```