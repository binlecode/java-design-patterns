

Decorator pattern allows a user to add new functionality to an existing object without altering its structure. This type of design pattern comes under structural pattern as this pattern acts as a wrapper to existing class.

This pattern creates a decorator class which wraps the original class and provides additional functionality keeping class methods signature intact.


We're going to create a `Shape` interface and concrete classes implementing the Shape interface. We will then create an abstract decorator class ShapeDecorator implementing the Shape interface and having Shape object as its instance variable.

RedShapeDecorator is concrete class implementing ShapeDecorator.

![pattern diagram](./images/decorator_pattern_uml_diagram.jpg)

Demo class:

[../src/main/java/sample/designpattern/decorator/Demo.java](../src/main/java/sample/designpattern/decorator/Demo.java)

